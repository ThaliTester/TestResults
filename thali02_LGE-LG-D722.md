#### Test 575312430087a60_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
--------- beginning of system
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): init target 500000
V/JNIHelp ( 5539): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 300, mChargingStatus=5, mChargingStop=false
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
W/MainApplication( 5168): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
D/WifiController(  834): battery changed pluggedType: 2
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/charger_monitor(  489): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 298, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
W/MainApplication( 5168): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/ActivityThread( 5539): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5539): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f335ea8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5539): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5539): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5539): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5539): Reading stored module config
D/PackageBroadcastService( 5539): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 5539): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5539): Loading module APK com.google.android.play.games
D/NativeLibraryUtils( 5539): Install completed successfully. count=14 extracted=0
I/art     ( 5539): CheckpointMarkThreadRoots callback created = 0xb042d3b0
I/art     ( 5539): CheckpointMarkThreadRoots callback created = 0xb042d390
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/AndroidRuntime( 5575): 
D/AndroidRuntime( 5575): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5575): CheckJNI is OFF
D/ChimeraCfgMgr( 5539): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5539): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 5539): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 5539): Submit a task: k
D/ChimeraCfgMgr( 5539): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5539): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/Icing   ( 5539): Storage manager: low false usage 1.72MB avail 2.37GB capacity 4.06GB
D/k       ( 5539): Processing package: com.test.thalitest
I/PeopleDatabaseHelper( 5539): cleanUpNonGplusAccounts done.
D/GassUtils( 5539): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 5539): Found info for package com.test.thalitest in db.
W/BaseAppContext( 5539): Using Auth Proxy for data requests.
I/art     ( 5539): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5539): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/BaseAppContext( 5539): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 5539): Using Auth Proxy for data requests.
D/WearableService( 1731): callingUid 10006, callindPid: 1731
E/MDM     ( 1731): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5539): Restart initialization of location
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
D/AndroidRuntime( 5575): Calling main entry com.android.commands.am.Am
I/ActivityManager(  834): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5631 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  834): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  834): setTaskToReturnTo : TaskRecord{1c34b2e0 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  834): setTaskToReturnTo : TaskRecord{1c34b2e0 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  834): AppWindowTokenEx init.. 
D/ContextHelper(  834): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  834): Focus left window: Window{2e3f6b72 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/AndroidRuntime( 5575): Shutting down VM
D/SplitWindow(  834): check instance of lgWin Window{32ab386a u0 Starting com.test.thalitest}
I/ActivityManager(  834): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5653 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/BaseAppContext( 5539): Using Auth Proxy for data requests.
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/WindowStateAnimator(  834): Starting window displayed
I/SystemUI[Framework](  834): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
W/PhoneWindowManagerEx(  834): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  834): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  834): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  834): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@25baff,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  834): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BarTransitions( 1369): draw background and invalidate : color = a000000
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
D/BarTransitions( 1369): draw background and invalidate : color = 13121212
W/BaseAppContext( 5539): Using Auth Proxy for data requests.
,W/BaseAppContext( 5539): Using Auth Proxy for data requests.
W/BaseAppContext( 5539): Using Auth Proxy for data requests.
I/HotwordDetector( 1937): Closing mic
W/ActivityThread( 1876): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1876): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1876): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1876): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1876): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1876): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1876): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1876): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1876): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/BaseAppContext( 5539): Using Auth Proxy for data requests.
I/MicrophoneInputStream( 1937): mic_close com.google.android.apps.gsa.speech.audio.u@2af5d26f
V/AudioRecord( 1937): stop()
D/AudioRecord( 1937): AudioRecord->stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioFlinger(  283): Record stopped OK
V/AudioPolicyManager(  283): stopInput() input 17
V/AudioPolicyService(  283): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  283): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  283): ThreadBase::setParameters() routing=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3a11000
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/audio_hw_primary(  283): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  283): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  283): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  283): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  283): disable_audio_route: exit
E/audio_hw_primary(  283): disable_snd_device: enter 144
D/hardware_info(  283): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  283): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  283): stop_input_stream: exit: status(0)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  283): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  283): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  283): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyService(  283): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  283): inserting command: 3 at index 0, num commands 0
W/IcingInternalCorpora( 5539): getNumBytesRead when not calculated.
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  283): setParameters(): io 17, keyvalue hotword_active=0, calling pid 283
V/AudioFlinger(  283): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3a11000
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
I/ActivityManager(  834): Activity reported stop, but no longer stopping: ActivityRecord{106e7308 u0 com.lge.launcher2/.Launcher t221}
D/ContextHelper( 5653): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): releasing 16 from 1937 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): RecordThread::stop
V/AudioFlinger(  283): purging stale effects
V/AudioPolicyManager(  283): releaseInput() 17
V/AudioPolicyManager(  283): closeInput(17)
V/AudioFlinger(  283): closeInput() 17
V/AudioSystem(  283): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1749): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): ThreadBase::exit
V/AudioSystem( 1937): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioSystem( 1984): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): RecordThread 0xb3a11000 exiting
V/AudioSystem(  834): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  283): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  283): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): releaseInput() exit
V/AudioSystem( 1369): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2007): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3229): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  283): removeClient_l() pid 1937, calling pid 283
I/HotwordRecognitionRnr( 1937): Stopping hotword detection.
I/HotwordRecognitionRnr( 1937): Hotword detection finished
I/WebViewFactory( 5653): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5653): Time to load native libraries: 9 ms (timestamps 4088-4097)
I/LibraryLoader( 5653): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5653): Binding Chromium to main looper Looper (main, tid 1) {3ec70d0}
I/LibraryLoader( 5653): Expected native library version number "",actual native library version number ""
I/chromium( 5653): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/BrowserStartupController( 5653): Initializing chromium process, singleProcess=true
W/art     ( 5653): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 5539): Background sticky concurrent mark sweep GC freed 16836(1537KB) AllocSpace objects, 15(240KB) LOS objects, 11% free, 12MB/14MB, paused 3.580ms total 107.344ms
I/Icing   ( 5539): updateResources: need to parse f{com.google.android.gms}
E/SysUtils( 5653): ApplicationContext is null in ApplicationStatus
W/chromium( 5653): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5653): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5653): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5653): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5653): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5653): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5653): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5653): Remote Branch: 
I/Adreno-EGL( 5653): Local Patches: 
I/Adreno-EGL( 5653): Reconstruct Branch: 
I/Gmail   ( 5631): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AudioPolicyService(  283): registerClient() client 0xb4027480, uid 10316
D/BluetoothManagerService(  834): Message: 20
D/BluetoothManagerService(  834): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5f12241:true
,D/BluetoothAdapterService(703580668)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@39e81732
W/GAV2    ( 5631): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5631): Error finding the version of the Email provider.....
E/Gmail   ( 5631): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5631): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5631): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5631): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5631): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5631): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5631): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5631): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5631): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5631): getAccountsCursor
W/ActivityManager(  834): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5631): Observing account changes for notifications
,W/art     ( 5653): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5653): onDetachedFromWindow called when already detached. Ignoring
,I/ActivityManager(  834): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5721 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/art     ( 5539): Background sticky concurrent mark sweep GC freed 11301(824KB) AllocSpace objects, 7(112KB) LOS objects, 7% free, 13MB/14MB, paused 8.947ms total 40.598ms
D/ChimeraCfgMgr( 5539): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5539): Module APK com.google.android.play.games already loaded
D/SystemWebViewEngine( 5653): CordovaWebView is running on device made by: LGE
,W/art     ( 5653): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5653): Attempt to remove local handle scope entry from IRT, ignoring
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5539): Internal init done: storage state 0
,I/Icing   ( 5539): Post-init done
,I/NotificationManager( 5539): com.google.android.gms: cancel(10436) by com.google.android.gms
I/Activity( 5653): Activity.onPostResume() called 
D/OpenGLRenderer( 5653): Render dirty regions requested: true
I/OpenGLRenderer( 5653): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5653): Enabling debug mode 0
D/Atlas   ( 5653): Validating map...
,D/SplitWindow(  834): check instance of lgWin Window{14935b07 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5653): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  834): Killing 5311:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/PhoneMonitor( 5721): Register our PhoneStateListener
,W/libprocessgroup(  834): failed to open /acct/uid_10011/pid_5311/cgroup.procs: No such file or directory
D/InputDispatcher(  834): Focus entered window: Window{14935b07 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  834): Killing 5328:com.android.gallery3d/u0a23 (adj 15): empty #11
I/Gmail   ( 5631): notifyAccountChanged
I/Gmail   ( 5631): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5631): getAccountsCursor
,D/PhoneMonitor( 5721): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/Gmail   ( 5631): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/TelephonyAutoProfiling( 5721): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5721): [parse] Load xml
V/TelephonyAutoProfiling( 5721): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5721): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5721): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/InputMethodManagerService(  834): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/Gmail   ( 5631): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5631): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Timeline( 5653): Timeline: Activity_idle id: android.os.BinderProxy@1cf02ddf time:84989
W/libprocessgroup(  834): failed to open /acct/uid_10023/pid_5328/cgroup.procs: No such file or directory
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  834): Displayed com.test.thalitest/.MainActivity: +1s533ms
I/Timeline(  834): Timeline: Activity_windows_visible id: ActivityRecord{a309999 u0 com.test.thalitest/.MainActivity t222} time:85003
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BindingManager( 5653): Cannot call determinedVisibility() - never saw a connection for the pid: 5653
,I/art     ( 5468): Explicit concurrent mark sweep GC freed 7949(400KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 967us total 73.063ms
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 5539): Checkin interval check for package: unspecified last checkin: 1454091923659 min interval config: 0 actual interval: 7371
,W/GCoreFlp( 1731): No location to return for getLastLocation()
,W/FusedLocationProvider( 1731): location=null
I/CheckinService( 5539): Disabling old GoogleServicesFramework version
,I/Gmail   ( 5631): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 3180): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@f9e2ae1 on behalf of 5539
D/JsMessageQueue( 5653): Set native->JS mode to OnlineEventsBridgeMode
,I/art     ( 5539): Background sticky concurrent mark sweep GC freed 8087(646KB) AllocSpace objects, 14(224KB) LOS objects, 4% free, 13MB/14MB, paused 16.080ms total 121.710ms
,W/InstanceID/Rpc( 5539): Found 10006
W/InstanceID/Rpc( 5539): Found 10006
D/InitAlarmsService( 3775): Clearing and rescheduling alarms.
I/ActivityManager(  834): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5773 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 26.354ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.609ms
,V/DownloadManager( 3180): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@226f0006 on behalf of 5539
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.302ms
V/DownloadManager( 3180): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@5e906c7 on behalf of 5539
I/CheckinService( 5539): Checking schedule, now: 1454091931404 next: 1454091953617
I/CheckinService( 5539): active receiver: disabled
,W/ResourcesManager( 5773): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5773): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@5533f7
,I/ActivityManager(  834): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5791 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/CalendarProvider2( 5773): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5773): Created com.android.providers.calendar.CalendarAlarmManager@3ec70d0(com.android.providers.calendar.CalendarProvider2@5533f7)
,D/CalendarProvider2( 5773): Scheduling check of next Alarm
,D/CalendarProvider2( 5773): SCHEDULE_ALARM_REMOVE
I/ActivityManager(  834): Killing 3775:com.android.calendar/u0a13 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/libprocessgroup(  834): failed to open /acct/uid_10013/pid_3775/cgroup.procs: No such file or directory
W/ResourcesManager( 5791): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Icing   ( 5539): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/jxcore_app_log( 5653): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426135552
,I/chromium( 5653): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/Icing   ( 5539): Loaded CLD2 Version V2.0 - 20141016
,I/art     ( 5653): CheckpointMarkThreadRoots callback created = 0x9f5465a0
,I/Icing   ( 5539): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/art     ( 5653): CheckpointMarkThreadRoots callback created = 0x9f546570
,I/Babel_SMS( 5791): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5791): MmsConfig.loadMmsSettings
I/Babel_SMS( 5791): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5791): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5791): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5791): MmsConfig.loadFromResources
E/Babel_SMS( 5791): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5791): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 5791): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5791): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5791): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5791): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5791): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5791): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5791): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5791): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5791): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5791): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5791): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5791): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5791): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5791): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5791): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5791): found sensor: Motion Accel, handle=46
,I/art     ( 5791): CheckpointMarkThreadRoots callback created = 0xaaf38490
,I/art     ( 5791): CheckpointMarkThreadRoots callback created = 0xaaf38460
,I/art     (  834): Explicit concurrent mark sweep GC freed 34549(1621KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.351ms total 190.470ms
,I/ActivityManager(  834): Process com.lge.bnr (pid 5168) has died
W/Settings( 5791): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5791): startup - clean
I/Babel   ( 5791): deleted: false for 0
,I/CalendarProvider2( 5773): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5773): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/AudioCapabilities( 5791): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5791): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5791): Unsupported mime audio/g726
W/AudioCapabilities( 5791): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5791): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5791): Unsupported mime video/mjpg
W/VideoCapabilities( 5791): Unsupported mime video/theora
,W/AudioCapabilities( 5791): Unsupported mime audio/evrc
W/AudioCapabilities( 5791): Unsupported mime audio/qcelp
W/VideoCapabilities( 5791): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5791): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5791): Unsupported mime audio/qcelp
W/AudioCapabilities( 5791): Unsupported mime audio/evrc
W/VideoCapabilities( 5791): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5791): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5791): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5791): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5791): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5791): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5791): onServiceConnected
,W/Babel   ( 5791): Attempted to change video mute state without an active call.
W/ResourcesManager( 5791): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5791): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5791): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  834): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5825 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5092): getMode name:com.lge.qremote
,I/AudioManager( 5092): getMode name:com.lge.qremote
,I/AudioManager( 5092): getMode name:com.lge.qremote
,W/System  ( 5791): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5791): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5791): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AudioManager( 5092): getMode name:com.lge.qremote
I/AudioManager( 5092): getMode name:com.lge.qremote
,D/LocationInitializer( 5539): Restart initialization of location
,E/MDM     ( 1731): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,D/UEI.SmartControl( 5825): Quickset Services start...
I/UEI.SmartControl( 5825): Manufacture = LGE
D/UEI.SmartControl( 5825): File observer start...
,E/UEI.SmartControl( 5825): IR Port is disabled: false
D/UEI.SmartControl( 5825): Starting file observer...
D/UEI.SmartControl( 5825): Extracting JNI libs...
D/UEI.SmartControl( 5825): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  834): Process com.google.android.apps.docs (pid 5401) has died
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
I/AudioManager( 5092): getMode name:com.lge.qremote
,I/AudioManager( 5092): getMode name:com.lge.qremote
,I/NotificationManager( 5791): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  834): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5852 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/UEI.SmartControl( 5825): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5825): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5825): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/AppUp4:AppBoxCP( 5852): onCreate
,W/AppUp4:DB( 5852):  [AppBoxDatabaseHelper] construct
I/UEI.SmartControl( 5825): --- Selecting new region: 2
I/UEI.SmartControl( 5825): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5825): Platform has CIR...
,D/UEI.SmartControl( 5825): NO CIR support, need to check package...
I/UEI.SmartControl( 5825): Model: LG-D722 uses JNI
I/AppUp4:DB( 5852):  setFingerPrint start
I/AppUp4:DB( 5852):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/UEI.SmartControl( 5825): QS Service created
I/AppUp4:DB( 5852):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5852):  SDK version = 0
I/AppUp4:DB( 5852):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5852): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5852): onReceive
I/AppUp4:CustModeStarterReceiver( 5852): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5852): Context : android.app.ReceiverRestrictedContext@15064982
D/AppUp4:CustFacade( 5852): isCustomizationCompleted : false
,E/UEI.SmartControl( 5825): QS start get config
D/AppUp4:CustFacade( 5852): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5852): begin check event
I/AppUp4:CustModeStarterReceiver( 5852): Event For Nothing, skip.
W/jxcore-log( 5653): Initializing JXcore engine
,W/jxcore-log( 5653): JXcore engine is ready
I/ActivityManager(  834): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5871 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/UEI.SmartControl( 5825): Loading JNI Libs...
,D/UEI.SmartControl( 5825):  configuring local db...
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ActivityManager(  834): Process com.android.vending (pid 5488) has died
,I/[SystemUI]QPairHandler( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,W/Thread-671( 5810): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6052]" dev="sockfs" ino=6052 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-671( 5810): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/Thread-671( 5810): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8220]" dev="sockfs" ino=8220 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-671( 5810): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,W/Thread-671( 5810): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-671( 5810): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26784]" dev="sockfs" ino=26784 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
W/jxcore-log( 5653): Starting JXcore engine
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/InputReader(  834): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 5871): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5871): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5871): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/administrator(  834): Handling package changes for user 0
W/jxcore-log( 5653): Platform android
W/jxcore-log( 5653): 
W/jxcore-log( 5653): Process ARCH arm
W/jxcore-log( 5653): 
,I/NotificationService(  834): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  834): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  834): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  834): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  834): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  834): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1350c09b
D/UEI.SmartControl( 5825):  ---- Has DB8: true
,D/UEI.SmartControl( 5825): QS start statue = true Error code = 0
D/UEI.SmartControl( 5825): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5825): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,I/AppConfig( 5871): Total System Memory = 906309632
D/UEI.SmartControl( 5825): IRRCDataComm has AudioManager!!!!.
I/GalleryUtils( 5871): Application Heap = 96 MB
I/AppConfig( 5871): App Tier : NOT_DEF
W/irrc_jni( 5825): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5825): IrrcClient ++ 
D/irrcClient( 5825): getIrrcService ++ 
,D/irrcClient( 5825): getIrrcService -- 
D/irrcClient( 5825): IrrcClient -- 
W/irrc_jni( 5825): IRRCPlayer_nativeInit -- 
W/ResourcesManager(  834): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5825): Services init done
D/SystemHelper( 5871): region [EU], country [EU], operator [OPEN], sub-operator []
D/UEI.SmartControl( 5825): QS Service init finished
D/UEI.SmartControl( 5825): QS Service version name: 0.1.73
D/UEI.SmartControl( 5825): QS Service version code: 1073
D/UEI.SmartControl( 5825): Service requested: Control
,I/UEI.SmartControl( 5825): Device manager: loading config....
D/UEI.SmartControl( 5825): Config is loaded...
,D/UEI.SmartControl( 5825): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5825):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5825): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5825): -----IControl: 11
D/UEI.SmartControl( 5825): Caller: com.lge.qremote
D/UEI.SmartControl( 5825): ------------ IControl registerCallback...
I/UEI.SmartControl( 5825): Registering callback...
,D/UEI.SmartControl( 5825): -----IControl: 19
D/UEI.SmartControl( 5825): Internal service binding...
D/UEI.SmartControl( 5825): Caller: com.lge.qremote
I/UEI.SmartControl( 5825): Registering Services Ready callback...
I/UEI.SmartControl( 5825): Notify client services are ready...
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/UEI.SmartControl( 5825): -----IControl: 8
D/UEI.SmartControl( 5825): Caller: com.lge.qremote
I/ActivityManager(  834): Killing 5384:com.lge.eula/1000 (adj 15): empty #11
,D/LockScreenSettings( 5366): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5366): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5366): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5366): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5366): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
W/ResourceType(  834): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_5384/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  834): applying state to connected service
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  834): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5897 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
I/ActivityManager(  834): Killing 5631:com.google.android.gm/u0a53 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 173 ms] updated apps [took 173 ms] 
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  834): failed to open /acct/uid_10053/pid_5631/cgroup.procs: No such file or directory
I/jxcore-log( 5653): JXcore Cordova bridge is ready!
I/jxcore-log( 5653): 
W/jxcore-log( 5653): JXcore engine is started
,V/AlarmManager(  834): RTC_WAKEUP set : Alarm{24c95157 type 0 when 1454091934653 com.google.android.googlequicksearchbox} when 1454091934653
,I/jxcore-log( 5653): Toggling radios to true
I/jxcore-log( 5653): 
,D/BluetoothAdapter( 5653): enable(): BT is already enabled..!
D/WifiServiceImplEx(  834): setWifiEnabled: true pid=5653, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  834): setWifiEnabled: true pid=5653, uid=10316
D/WifiServiceImplEx(  834): disconnect pid=5653, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  834): reconnect pid=5653, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5653): Radios toggled
I/jxcore-log( 5653): 
I/jxcore-log( 5653): My device name is: LGE-LG-D722
I/jxcore-log( 5653): 
D/Finsky  ( 5897): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/wpa_supplicant( 2742): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2742): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,E/WifiStateMachine(  834): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  834): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1802): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,D/LGWifiP2pService(  834): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  834): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  834): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  278): Clearing all IP addresses on wlan0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/WifiHS20(  834): hidePasspointNotification off =false
V/NativeCrypto( 1731): Read error: ssl=0xaaedf000: I/O error during system call, Connection timed out
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  834): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  834): ignoring duplicate network state non-change
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
,E/WifiStateMachine(  834): Start Disconnecting Watchdog 1
I/wpa_supplicant( 2742): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:35.047 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:35.056 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  834): hidePasspointNotification off =false
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  834): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  834): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  834): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/CommandListener(  278): Clearing all IP addresses on wlan0
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  834): hidePasspointNotification off =false
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:35.071 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
V/NativeCrypto( 1731): SSL shutdown failed: ssl=0xaaedf000: I/O error during system call, Broken pipe
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
,I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
,D/ConnectivityService(  834): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/WifiNetworkAgent(  834): NetworkAgent: NetworkAgent channel lost
,I/ActivityManager(  834): Process com.lge.qremote (pid 5092) has died
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): ValidatedState{ when=-5ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): DefaultState{ when=-37ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): Forcing reevaluation
D/WifiHS20(  834): hidePasspointNotification off =false
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:35.172 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:35.173 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  834): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  834): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  834): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  834): setSupplicantStateSCANNING
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
,D/ConnectivityService(  834): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  834): disableDataServiceNotify
D/DSQN    (  834): stop dsqn bin
D/Finsky  ( 5897): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/ConnectivityService(  834): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DhcpStateMachine(  834): StoppedState
D/DhcpStateMachine(  834): StoppedState{ when=-196ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  834): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  834): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): Disconnected - quitting
W/Settings( 5897): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5897): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/CSLegacyTypeTracker(  834): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  834): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/NotificationManager( 5897): com.android.vending: cancel(-1050172287) by com.android.vending
D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/Tethering(  834): MasterInitialState.processMessage what=3
V/NetworkPolicy(  834): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1836): |CORE| No family connected
D/ConnectivityService(  834): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  834): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  834): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  834): MasterInitialState.processMessage what=3
D/TelephonyNetworkFactory-1( 1749): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  834): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  834):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
V/NetworkPolicy(  834): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = -1
D/NetworkManagementService(  834): Removing idletimer
W/Settings(  834): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/DownloadManager( 3180): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@932b4f4 on behalf of 5897
D/Ads     ( 5897): Skipping gmscore version check
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/Finsky  ( 5897): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/Finsky  ( 5897): [1] Libraries$2.run: Finished loading 1 libraries.
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/PackageBroadcastService( 5539): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5897): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  834): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5956 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 5539): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5539): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 5897): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 5956): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  834): Message: 20
D/BluetoothManagerService(  834): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1beb3e47:true
,D/BluetoothAdapterService(703580668)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@39e81732
D/BluetoothAdapterService(703580668)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@39e81732
V/LGMDMManager( 5956): Create singleton instance
,I/AudioManager( 5956): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5825): -----IControl: 11
,D/UEI.SmartControl( 5825): Caller: com.lge.qremote
D/UEI.SmartControl( 5825): ------------ IControl registerCallback...
I/UEI.SmartControl( 5825): Registering callback...
D/UEI.SmartControl( 5825): -----IControl: 19
D/UEI.SmartControl( 5825): Caller: com.lge.qremote
I/UEI.SmartControl( 5825): Registering Services Ready callback...
I/UEI.SmartControl( 5825): Notify client services are ready...
D/UEI.SmartControl( 5825): -----IControl: 8
D/UEI.SmartControl( 5825): Caller: com.lge.qremote
E/lowmemorykiller(  243): Error writing /proc/5871/oom_score_adj; errno=22
,I/ActivityManager(  834): Process com.android.gallery3d (pid 5871) has died
,V/SetupWizard( 5721): Connected to Gservices successfully
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  834): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationInitializer( 5539): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1731): [124] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  834): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5992 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1731): No location to return for getLastLocation()
,W/FusedLocationProvider( 1731): location=null
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2742): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/LocSvc_java(  834): onReceive
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:36.232 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  834): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  834): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:36.238 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2742): wlan0: Associated with c0:ff:d4:d3:aa:48
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/WifiServerServiceExt(  834): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  834): setSupplicantStateASSOCIATED
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/wpa_supplicant( 2742): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2742): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/ActivityManager(  834): Process com.android.contacts (pid 5347) has died
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:36.332 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/WifiServiceExtension(  834): setVHTCapabilityType  : false
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:36.337 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/WifiServerServiceExt(  834): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  834): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  834): setSecurityType  : 2
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:36.381 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:36.385 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
,D/ConnectivityService(  834): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  834): Got NetworkAgent Messenger
D/ConnectivityService(  834): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  834): NetworkAgent connected
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
E/WifiConfigStore(  834): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  834): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/CommandListener(  278): Setting iface cfg
E/WifiStateMachine(  834): Start Dhcp Watchdog 2
D/DhcpStateMachine(  834): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  834): WaitBeforeStartState
D/WifiServerServiceExt(  834): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  834): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  834): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  834): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  834): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/Gmail   ( 5992): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5992): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/WifiStateMachine(  834): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  834): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  834): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/LGWifiP2pService(  834): InactiveState{ when=-2ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d3b69a7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  834): P2pEnabledState{ when=-3ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d3b69a7 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  278): Setting iface cfg
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/DhcpStateMachine(  834): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  834): DHCP Start wake lock is acquired.
D/CommandListener(  278): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  834): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  834): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  834): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  834): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  834): setSupplicantStateCOMPLETED
D/ConnectivityService(  834): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  834): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  834): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ConnectivityService(  834): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  834): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  834): ignoring duplicate network state non-change
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:36.553 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:36.556 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  834): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/ConnectivityService(  834): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  834): [PASSPOINT] passpointNotification: hs20AP list is checked
,E/WifiStateMachine(  834): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{3c7d1ed4 type 2 when 90706 com.android.providers.calendar} when 90706
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:36.574 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  834): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/ConnectivityService(  834): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  834): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  834): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:36.586 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/Netd    (  278): netlink response contains error (File exists)
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  834): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  834): addLocalRoutetoDefaultNetwork
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
D/Connect,ivityService(  834): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  834): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
E/Gmail   ( 5992): Error finding the version of the Email provider.....
E/Gmail   ( 5992): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5992): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5992): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5992): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5992): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5992): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5992): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5992): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[SystemUI]StatusBar.NetworkController( 1369): mWifiConnected = true, mWifiLevel = 2
W/EmailMigration( 5992): We do not support migrating this version of the Email provider.
D/Nat464Xlat(  834): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  834): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  834): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  834): rematching NetworkAgentInfo [WIFI () - 101]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  834):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): Connected
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  834):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  834):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  834):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  834): currentScore = 0, newScore = 20
D/ConnectivityService(  834):    accepting network in place of null
D/ConnectivityService(  834): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1369): Remote
D/TelephonyNetworkFactory-1( 1749): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  834): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  834): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  834): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  834): [e] list.add(nai) empty : false size: 1
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  834): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  834): validation of new default Network = false
D/ConnectivityService(  834): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  834): enableDataServiceNotify 
D/DSQN    (  834): start dsqn bin
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = 1
D/WIFI    (  834): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  834):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/Tethering(  834): MasterInitialState.processMessage what=3
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): [LWD] Start DNSResolver start to wait
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): [LWD] wait 500ms before dns check
,V/NetworkPolicy(  834): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  834): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  834): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524290
D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
I/DSQN    ( 6033): DSQN samuel.seo ver 141203
E/DSQN    ( 6033): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6033): created command queue thread
I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/DSQN    ( 6033): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6033): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/Icing   ( 5539): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/Gmail   ( 5992): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  834): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Icing   ( 5539): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/DhcpStateMachine(  834): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  834): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  834): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6042): version 5.5.6 starting
,E/dhcpcd  ( 6042): get_duid: Read-only file system
I/dhcpcd  ( 6042): wlan0: rebinding lease of 192.168.1.134
,I/art     (  834): Explicit concurrent mark sweep GC freed 67635(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.176ms total 200.231ms
,I/Gmail   ( 5992): Observing account changes for notifications
I/ActivityManager(  834): Process com.android.providers.calendar (pid 5773) has died
,W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): [LWD] DNSResolver start dns
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/dhcpcd  ( 6042): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out(  834): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/dhcpcd  ( 6042): wlan0: leased 192.168.1.134 for 86400 seconds
I/DSQN    ( 6033): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6033): restart monitoring
,D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6033): dsqn report finish
D/DSQN    (  834): DSQM DsqnNotification wlan0  1
D/DSQN    (  834): start to monitor internet connection
I/art     ( 1731): Explicit concurrent mark sweep GC freed 30676(1826KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 13MB/22MB, paused 1.903ms total 130.025ms
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 29 Jan 2016 18:25:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454091937246], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454091937214]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): Validated
D/ConnectivityService(  834): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  834): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  834):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  834):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  834):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  834): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  834): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  834): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  834): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524290
D/WIFI    (  834): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  834):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1749): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  834): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  834): set CMD_CAPTIVE_CHECK_COMPLETED
,D/TelephonyIcons( 1369): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1369): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  834): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6074 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 5992): notifyAccountChanged
,I/Gmail   ( 5992): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/ResourcesManager( 6074): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Gmail   ( 5992): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5992): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5992): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5992): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CalendarApplication( 6074): CalendarApplication.onCreate()
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  834): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  834): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  834): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  834): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  834): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  834): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  834): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  834): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  834): RunningState
D/PreferenceKeysParser( 6074): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6074): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@85efccd, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@15064982, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3a9f1893, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3ec70d0, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@6eb98c9, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2f537bce, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2598aaef, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@29efc9fc, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1f8bf885, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@102f86da, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@5ef070b, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@186d89e8, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@18189801, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@128f36a6, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@340508e7, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@38855c94, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2175b33d, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@39e81732, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@18f4c83, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3a5ae00, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1c8f4639, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@197c747e, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1cf02ddf, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@19b7aa2c, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@33150cf5, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@24675a8a, lg_preferences_home_tz_enabled=com.android.cale,ndar.adaptation.PreferenceKey$KeyData@e53c8fb, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@e0b3d18, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3ff68371, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@32689556, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2a8bf9d7, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@170312c4, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@39ee5ad, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@570b0e2, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@17ac5c73, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@c809730, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1ff12fa9, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1becf92e, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3f664ccf, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@210ff65c, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@18041d65, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1bd37a3a,
D/GeneralPreferenceUtils( 6074): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 6074): [init]
I/Config  ( 6074): LGCalendar ver.4.40.17
I/Config  ( 6074): start check model
I/Config  ( 6074): start check native_ca
I/Config  ( 6074): Config Operator=OPEN, Country=EU
D/Config  ( 6074): [setDefaultValuesToPref]
D/Config  ( 6074): [parseProfiles]
,D/ProfilesParser( 6074): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6074): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6074): [updateProfiletoCountryInfo]
D/GeneralPreference( 6074): [checkAndMigrateOldPreference]
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/AlertReceiver( 6074): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6074): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6074): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 6074): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
D/ConnectivityService(  834): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/Gmail   ( 5992): getAccountsCursor
I/AlertUtils( 6074): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6074): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AlertUtils( 6074): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6074): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6074): onHandleIntent
,D/HolidayDataLoader( 6074): readJsonAsset : holiday.json
D/AlertService( 6074): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6074): [updateWidgets] 
D/MonthWidgetProvider( 6074): [onReceive]
D/CalendarWidgetProvider( 6074): [onReceive]
D/CalendarWidgetProvider( 6074): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6074): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6074): [onReceive]
D/CalendarWidgetProvider( 6074): [onReceive]
D/CalendarWidgetProvider( 6074): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6074): [onCreate] mContext.getPackageName() = com.android.calendar
I/AppUp4:CustModeStarterReceiver( 5852): onReceive
I/AppUp4:CustModeStarterReceiver( 5852): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5852): Context : android.app.ReceiverRestrictedContext@15064982
D/AppUp4:CustFacade( 5852): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5852): isSimDevice : true
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  834): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  834): identical MTU - not setting
D/Nat464Xlat(  834): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  834): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  834): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
E/HolidayIntentService( 6074): onHandleIntent:holiday data empty
D/ConnectivityService(  834): Wi-Fi IP changed. Lp difference / No Route difference
,D/DSQN    (  834): enableDataServiceNotify 
D/DSQN    (  834): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1369): CM callback handler got msg 524295
I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:37.815 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/AppUp4:CustModeStarterReceiver( 5852): begin check event
I/AppUp4:CustModeStarterReceiver( 5852): Event For Nothing, skip.
D/DSQN    (  834): dsqn is running restart
I/NotificationManager( 5791): com.google.android.talk: cancel(8) by com.google.android.talk
,I/DSQN    ( 6114): DSQN samuel.seo ver 141203
E/DSQN    ( 6114): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6114): created command queue thread
I/DSQN    ( 6114): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6114): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/ActivityManager(  834): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6117 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6117): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6117): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6117): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 6117): Total System Memory = 906309632
,I/GalleryUtils( 6117): Application Heap = 96 MB
I/AppConfig( 6117): App Tier : NOT_DEF
D/SystemHelper( 6117): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  834): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6136 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 6136): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6136): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  834): onReceive
D/LocSvc_java(  834): got connectivity action
,I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  834): broadcast - no network connections
D/LocSvc_java(  834): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
,D/GpsLocationProvider(  834): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  834): Sending msg: 4 arg1:0 arg2:1
D/GpsLocationProvider(  834): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  834): onReceive
D/LocSvc_java(  834): got connectivity action
D/LocSvc_java(  834): broadcast - no network connections
D/LocSvc_java(  834): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  834): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  834): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  834): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  834): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  834): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  834): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  834): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  834): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  834): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemConfig( 6136): BUILD Country: EU
I/SystemConfig( 6136): BUILD Operator: OPEN
,I/SystemConfig( 6136): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6136): existFile = false
I/SystemConfig( 6136): canReadFile = false
I/SystemConfig( 6136): systemFeature RCS result false
D/SystemConfig( 6136): refreshRcsSupport() :false
,D/LockScreenSettings( 5366): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5366): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5366): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5366): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5366): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  834): Killing 5897:com.android.vending/u0a36 (adj 15): empty #11
I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 37 ms] updated apps [took 37 ms] 
,W/libprocessgroup(  834): failed to open /acct/uid_10036/pid_5897/cgroup.procs: No such file or directory
,I/ActivityManager(  834): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6161 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 328us total 25.106ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 23.649ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.357ms
,D/Finsky  ( 6161): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6161): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6161): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6161): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6161): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3180): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@671941d on behalf of 6161
,D/UEI.SmartControl( 5825): Internal timer expired: 1
,D/Finsky  ( 6161): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6161): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6161): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 6161): Skipping gmscore version check
,I/ActivityManager(  834): Process com.google.android.gm (pid 5992) has died
,D/PackageBroadcastService( 5539): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5539): Null package name or gms related package.  Ignoreing.
I/AudioManager( 5956): getMode name:com.lge.qremote
,I/Icing   ( 5539): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 6161): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  834): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6212 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-29 19:25:39.508 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/WifiInternetCheck(  834): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  834): onReceive
D/LocSvc_java(  834): got connectivity action
D/LocSvc_java(  834): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  834): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  834): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  834): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  834): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1369): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  834): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  834): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ResourcesManager( 6212): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6212): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6212): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6212): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6212): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/NotificationManager( 1937): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/IndexDatabaseHelper( 6212): Using schema version: 115
,I/IndexDatabaseHelper( 6212): Index is fine
I/ActivityManager(  834): Process com.android.gallery3d (pid 6117) has died
V/AlarmManager(  834): RTC_WAKEUP set : Alarm{1fcfbce8 type 0 when 1454091940013 com.android.vending} when 1454091940013
D/Finsky  ( 6161): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/NotificationManager(  834): android: cancelAsUser(2) by android
,D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
D/libc-netbsd( 6161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  834): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6248 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6161): propertyValue:false
D/libc-netbsd( 6161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6114): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6114): restart monitoring
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6114): dsqn report finish
D/DSQN    (  834): DSQM DsqnNotification wlan0  1
D/DSQN    (  834): start to monitor internet connection
,I/PCSuite ( 6248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6248): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
I/PCSuite ( 6248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6248): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
I/PCSuite ( 6248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6248): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
I/PCSuite ( 6248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6248): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd( 6161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
I/AudioManager( 5956): getMode name:com.lge.qremote
,I/AudioManager( 5956): getMode name:com.lge.qremote
,V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,I/Icing   ( 5539): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/WiFiOffLoadBroadcast( 6212): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
,D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  834): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6281 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out(  834): propertyValue:false
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  834): propertyValue:false
,I/art     (  834): Explicit concurrent mark sweep GC freed 45294(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 6.167ms total 193.666ms
,V/WifiInternetCheck(  834): isHttpConnectionAvailable - We got a valid response : 204
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5539): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/NotificationManager(  834): android: cancelAsUser(2) by android
I/ActivityManager(  834): Killing 5721:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  834): failed to open /acct/uid_10038/pid_5721/cgroup.procs: No such file or directory
,W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/qtaguid ( 6161): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6161): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6161): untagSocket(41) failed with errno -22
D/Finsky  ( 6161): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/Gmail   ( 6281): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6281): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  834): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6315 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/ActivityManager(  834): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
I/Gmail   ( 6281): Observing account changes for notifications
W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/NotificationManager(  834): android: cancelAsUser(2) by android
,V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,E/Gmail   ( 6281): Error finding the version of the Email provider.....
E/Gmail   ( 6281): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6281): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6281): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6281): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6281): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6281): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6281): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6281): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6281): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6281): getAccountsCursor
D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 95515799447; DSPS: 3228027; Offset : -3007584368
W/ResourcesManager( 6315): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6315): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
I/PCSuite ( 6248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6212): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6212): MCCMNC not supported: null
I/PCSuite ( 6248): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6248): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/qtaguid ( 6161): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6161): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6161): untagSocket(41) failed with errno -22
I/ActivityManager(  834): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6343 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  834): Killing 5852:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/MultiDex( 6315): VM with version 2.1.0 has multidex support
,I/MultiDex( 6315): install
I/MultiDex( 6315): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup(  834): failed to open /acct/uid_10011/pid_5852/cgroup.procs: No such file or directory
,I/Gmail   ( 6281): notifyAccountChanged
,W/ResourcesManager( 6343): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/Gmail   ( 6281): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6281): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6281): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/JNIHelp ( 6315): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Gmail   ( 6281): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/CalendarProvider2( 6343): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@5533f7
I/Gmail   ( 6281): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/CalendarProvider2( 6343): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6343): Created com.android.providers.calendar.CalendarAlarmManager@3ec70d0(com.android.providers.calendar.CalendarProvider2@5533f7)
D/CalendarProviderBroadcastReceiver( 6343): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6343): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6343): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6343): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 6343): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  834): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6367 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityThread( 6315): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6315): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@4eb1692: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6315): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  834): Process com.android.contacts (pid 6136) has died
,I/NotificationManager( 6315): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6315): com.google.android.gms: cancel(39789) by com.google.android.gms
D/CalendarProvider2( 6343): [IntentService] Release Lock
,D/CalendarProvider2( 6343): CalendarProviderIntentService.onDestroy()
I/art     ( 6161): CheckpointMarkThreadRoots callback created = 0xaae1a2f0
D/ChimeraCfgMgr( 6315): Reading stored module config
,I/art     ( 6161): CheckpointMarkThreadRoots callback created = 0xaae1a2b0
W/art     ( 6161): Suspending all threads took: 10.148ms
,D/ChimeraCfgMgr( 6315): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/Gmail   ( 6281): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 6315): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  834): Process com.google.android.apps.plus (pid 5432) has died
I/MusicStore( 6367): Database version: 120
,D/CAR.SERVICE( 6315): Connecting to CarCallService...
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,I/art     ( 6315): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6315): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/ContextImpl( 6367): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/CAR.SERVICE( 6315): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6315): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6315): Creating a new PhoneAdapter instance
W/ActivityManager(  834): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6315): setListener: com.google.android.gms.car.dn@27cbb689
,W/ActivityManager(  834): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6315): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6315): Starting CarCallService with initial phone null
I/NotificationManager( 6315): com.google.android.gms: cancel(10436) by com.google.android.gms
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6367): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6367): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/CAR.SERVICE( 6315): Package validated; name: com.android.vending
,W/ResourcesManager( 6367): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6367): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/NotificationManager( 6161): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6161): [1] GearheadStateMonitor.access$100: mIsProjecting:false
V/JNIHelp ( 6367): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6367): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6367): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c9b36b5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6367): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6367): GMSCore installation verified
I/ConfigStore( 6367): Config Database version: 1
,D/AlertService( 6074): Beginning updateAlertNotification
D/AlertService( 6074): No fired or scheduled alerts
,I/NotificationManager( 6074): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(9) by com.android.calendar
,I/NotificationManager( 6074): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6074): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6074): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6074): No events found starting within 1 week.
,I/MediaRouter( 6367): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 6367): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6367): type=WIFI subType= reason=null isConnected=true
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  834): android: cancelAsUser(2) by android
I/ActivityManager(  834): Killing 6074:com.android.calendar/u0a13 (adj 15): empty #11
,I/NetworkMonitor( 6367): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  834): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6405 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/libprocessgroup(  834): failed to open /acct/uid_10013/pid_6074/cgroup.procs: No such file or directory
I/qtaguid ( 6161): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6161): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6161): untagSocket(41) failed with errno -22
I/GHttpClientFactory( 6367): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6367): Using platform SSLCertificateSocketFactory
,I/art     (  834): Explicit concurrent mark sweep GC freed 15609(744KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.290ms total 148.495ms
,W/ResourcesManager( 6161): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6161): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  834): Killing 5366:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/ResourcesManager( 6405): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6405): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6405): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  834): failed to open /acct/uid_10069/pid_5366/cgroup.procs: No such file or directory
,W/ResourcesManager( 6161): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/NotificationManager( 6367): com.google.android.music: cancel(1061) by com.google.android.music
D/Finsky  ( 6161): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  834): RTC_WAKEUP set : Alarm{3eeddb03 type 0 when 1454091943492 com.android.vending} when 1454091943492
,I/ActivityManager(  834): Process com.google.android.talk (pid 5791) has died
,D/DeviceConnectionService( 1731): client connected with version: 8296000
D/WearableService( 1731): callingUid 10006, callindPid: 1731
,D/Finsky  ( 6161): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6161): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  834): Killing 6212:com.android.settings/1000 (adj 15): empty #11
I/LGEmail ( 6405): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6405): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_6212/cgroup.procs: No such file or directory
,I/jxcore-log( 5653): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5653): 
,D/eas_req ( 6405): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  834): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6433 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6405): JNI_OnLoad()
I/HubEmail( 6405): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6405): registerNatives()
,I/HubEmail( 6405): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6405): registerNativeMethods()
I/HubEmail( 6405): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6405): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  834): Killing 5825:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5956): android.os.DeadObjectException
,W/System.err( 5956): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5956): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5956): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5956): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5956): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5956): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5956): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5956): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5956): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5956): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5956): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5956): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5956): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5956): android.os.DeadObjectException
W/System.err( 5956): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5956): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5956): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5956): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5956): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5956): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5956): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5956): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5956): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5956): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5956): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5956): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5956): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,W/libprocessgroup(  834): failed to open /acct/uid_10089/pid_5825/cgroup.procs: No such file or directory
W/ActivityManager(  834): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/Settings( 6405): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  834): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6452 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LGDMClient( 6433): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6433): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6433): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6433): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6433): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6433): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6433): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6433): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  834): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6475 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6433): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
E/LGDMClient( 6433): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6433): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6433): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6433): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6433): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  834): Killing 6248:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6452): Quickset Services start...
,I/UEI.SmartControl( 6452): Manufacture = LGE
D/UEI.SmartControl( 6452): File observer start...
E/UEI.SmartControl( 6452): IR Port is disabled: false
D/UEI.SmartControl( 6452): Starting file observer...
D/UEI.SmartControl( 6452): Extracting JNI libs...
D/UEI.SmartControl( 6452): --- this system supports 32-bit or 64-bit only
,W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_6248/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/AlarmManager(  834): RTC_WAKEUP set : Alarm{33001e9d type 0 when 1454091944612 com.google.android.googlequicksearchbox} when 1454091944612
,I/AppUp4:AppBoxCP( 6475): onCreate
,W/AppUp4:DB( 6475):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6475):  setFingerPrint start
I/AppUp4:DB( 6475):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,D/UEI.SmartControl( 6452): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
I/AppUp4:DB( 6475):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6475):  SDK version = 0
I/AppUp4:DB( 6475):  beforefinger == newfinger no write in DB
D/UEI.SmartControl( 6452): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6452): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/AppUp4:AppBoxApplication( 6475): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6475): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6475): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6475): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6475): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6475): onReceive
I/AppUp4:CustModeStarterReceiver( 6475): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6475): Context : android.app.ReceiverRestrictedContext@6eb98c9
D/AppUp4:CustFacade( 6475): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6475): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6475): begin check event
I/AppUp4:CustModeStarterReceiver( 6475): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6475): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6475): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6475): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6475): handleAsyncCustNotification do not startCustService
I/ActivityManager(  834): Killing 5956:com.lge.qremote/u0a106 (adj 15): empty #11
I/UEI.SmartControl( 6452): --- Selecting new region: 2
I/UEI.SmartControl( 6452): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6452): Platform has CIR...
D/UEI.SmartControl( 6452): NO CIR support, need to check package...
I/UEI.SmartControl( 6452): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6452): QS Service created
,W/libprocessgroup(  834): failed to open /acct/uid_10106/pid_5956/cgroup.procs: No such file or directory
V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{acf0f12 type 2 when 99079 com.google.android.gms} when 99079
,I/LgeMiscReceiver( 3229): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3229): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3229): networkInfo.isConnected() = false
,E/UEI.SmartControl( 6452): QS start get config
,I/jxcore-log( 5653): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5653): 
I/ActivityManager(  834): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6508 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 303us total 23.445ms
,D/UEI.SmartControl( 6452): Loading JNI Libs...
D/UEI.SmartControl( 6452):  configuring local db...
I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.796ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 41.840ms
I/jxcore-log( 5653): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5653): 
,I/jxcore-log( 5653): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5653): 
I/jxcore-log( 5653): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5653): 
D/PhoneMonitor( 6508): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6508): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6508): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  834): Killing 6343:com.android.providers.calendar/u0a14 (adj 15): empty #11
,D/UEI.SmartControl( 6452):  ---- Has DB8: true
,D/UEI.SmartControl( 6452): QS start statue = true Error code = 0
D/UEI.SmartControl( 6452): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6452): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6452): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6452): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6452): IrrcClient ++ 
D/irrcClient( 6452): getIrrcService ++ 
D/irrcClient( 6452): getIrrcService -- 
D/irrcClient( 6452): IrrcClient -- 
W/irrc_jni( 6452): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6452): Services init done
,I/UEI.SmartControl( 6452): Device manager: loading config....
W/libprocessgroup(  834): failed to open /acct/uid_10014/pid_6343/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6452): Config is loaded...
D/UEI.SmartControl( 6452): QS Service init finished
,D/UEI.SmartControl( 6452): QS Service version name: 0.1.73
D/UEI.SmartControl( 6452): QS Service version code: 1073
D/UEI.SmartControl( 6452): Service requested: Control
V/DownloadManager( 3180): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
D/UEI.SmartControl( 6452): Service.onUnbind: IControl
D/UEI.SmartControl( 6452): Service.onDestroy
D/UEI.SmartControl( 6452): Shutdown IRRCPlayer... 
I/CheckinService( 5539): Checkin interval check for package: unspecified last checkin: 1454091923659 min interval config: 0 actual interval: 21735
V/DownloadManager( 3180): DownloadService onCreate
W/irrc_jni( 6452): IRRCPlayer_nativeFinalize ++ 
,D/irrcClient( 6452): ~IrrcClient ++ 
D/irrcClient( 6452): ~IrrcClient -- 
W/irrc_jni( 6452): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6452): Blaster closed
D/UEI.SmartControl( 6452): Blaster closed
D/UEI.SmartControl( 6452): Shut down QS...
D/UEI.SmartControl( 6452): Stopped file observer...
I/DownloadManager( 3180): in removeSpuriousFiles
I/UEI.SmartControl( 6452): QS lib stop result = true
D/UEI.SmartControl( 6452): QS shutdown complete
I/NotificationManager( 3180): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3180): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/UEI.SmartControl( 6452): QS Service created
V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@4eb1692 on behalf of 3180
I/UEI.SmartControl( 6452): Notify AllClients services are ready: 11
,I/DownloadManager( 3180): in trimDatabase
V/DownloadManager( 3180): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@3fe54863 on behalf of 3180
E/UEI.SmartControl( 6452): QS start get config
D/PhoneMonitor( 6508): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6508): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6508): [parse] Load xml
,I/ActivityManager(  834): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6542 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/TelephonyAutoProfiling( 6508): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6508): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3180): DownloadService onStartCommand
I/CheckinService( 5539): Checking schedule, now: 1454091945446 next: 1454091953617
I/CheckinService( 5539): active receiver: disabled
D/UEI.SmartControl( 6452):  configuring local db...
,V/DownloadManager( 3180): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@da009de on behalf of 3180
D/PhoneMonitor( 6508): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3180): DownloadService onDestroy
I/ActivityManager(  834): Killing 6281:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  834): failed to open /acct/uid_10053/pid_6281/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2651): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:25:45
D/UpdateThreadPoolManager( 2651): 2 : This is isUpdating : false
D/WeatherAncestor( 2651): connectivity changed - connection : true
D/Weather_cast( 2651): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2651): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:25:45
,D/WeatherService( 2651): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/UEI.SmartControl( 6452):  ---- Has DB8: true
,D/UEI.SmartControl( 6452): QS start statue = true Error code = 0
D/UEI.SmartControl( 6452): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6452): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6452): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6452): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6452): IrrcClient ++ 
D/irrcClient( 6452): getIrrcService ++ 
D/irrcClient( 6452): getIrrcService -- 
D/irrcClient( 6452): IrrcClient -- 
W/irrc_jni( 6452): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6452): Services init done
I/UEI.SmartControl( 6452): Device manager: loading config....
D/UEI.SmartControl( 6452): Config is loaded...
I/ActivityManager(  834): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6562 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  834): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/UEI.SmartControl( 6452): QS Service init finished
D/Weather.Utils( 2651): 2 : Utils getTopActivity com.lge.launcher2 / true
D/UEI.SmartControl( 6452):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6452): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6452): QS Service version name: 0.1.73
D/UEI.SmartControl( 6452): QS Service version code: 1073
D/UEI.SmartControl( 6452): Service requested: Control
D/WeatherService( 2651): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2651): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  834): Killing 6367:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  834): failed to open /acct/uid_10081/pid_6367/cgroup.procs: No such file or directory
,E/ActivityThread( 6452): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@29efc9fc that was originally bound here
E/ActivityThread( 6452): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@29efc9fc that was originally bound here
E/ActivityThread( 6452): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6452): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6452): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6452): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6452): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6452): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6452): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6452): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6452): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6452): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6452): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6452): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6452): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6452): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6452): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6452): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6452): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6452): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6452): Internal service binding...
,W/ResourcesManager( 6562): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6562): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6562): MmsConfig.loadMmsSettings
I/Babel_SMS( 6562): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6562): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6562): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6562): MmsConfig.loadFromResources
E/Babel_SMS( 6562): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6562): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6562): CheckpointMarkThreadRoots callback created = 0xb042d800
,D/SensorManager( 6562): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6562): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6562): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6562): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6562): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6562): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6562): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6562): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6562): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6562): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6562): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6562): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6562): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6562): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6562): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6562): found sensor: Motion Accel, handle=46
,I/art     ( 6562): CheckpointMarkThreadRoots callback created = 0xb042d7f0
W/Settings( 6562): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6562): startup - clean
D/UEI.SmartControl( 6452): Internal timer expired: 2
W/System.err( 6452): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@29efc9fc
W/System.err( 6452): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6452): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6452): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6452): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6452): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 6452): 	at com.uei.control.l.run(Unknown Source)
W/System.err( 6452): 	at java.util.Timer$TimerImpl.run(Timer.java:284)
E/UEI.SmartControl( 6452): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@29efc9fc
I/Babel   ( 6562): deleted: false for 0
,I/ActivityManager(  834): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6598 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/AudioCapabilities( 6562): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6562): Unsupported mime audio/adpcm
W/AudioCapabilities( 6562): Unsupported mime audio/g726
W/AudioCapabilities( 6562): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6562): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6562): Unsupported mime video/mjpg
,W/VideoCapabilities( 6562): Unsupported mime video/theora
W/AudioCapabilities( 6562): Unsupported mime audio/evrc
,W/AudioCapabilities( 6562): Unsupported mime audio/qcelp
W/VideoCapabilities( 6562): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6562): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6562): Unsupported mime audio/qcelp
W/AudioCapabilities( 6562): Unsupported mime audio/evrc
W/VideoCapabilities( 6562): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6562): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6562): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6562): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6562): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6562): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6562): onServiceConnected
,W/Babel   ( 6562): Attempted to change video mute state without an active call.
I/NotificationManager( 6562): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6562): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6562): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6562): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6562): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6562): propertyValue:false
,I/Babel   ( 6562): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  834): Killing 6315:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  834): failed to open /acct/uid_10006/pid_6315/cgroup.procs: No such file or directory
,W/ActivityManager(  834): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6598): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6598): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6598): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6598): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6598): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6598):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6598):   adb logcat -s GAv4
,W/GAv4    ( 6598): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6598): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6598): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6598): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6598): Time to load native libraries: 3 ms (timestamps 1625-1628)
I/LibraryLoader( 6598): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6598): Binding Chromium to main looper Looper (main, tid 1) {2e624842}
I/LibraryLoader( 6598): Expected native library version number "",actual native library version number ""
I/chromium( 6598): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6598): Initializing chromium process, singleProcess=true
W/art     ( 6598): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6598): ApplicationContext is null in ApplicationStatus
,W/chromium( 6598): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6598): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6598): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6598): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6598): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6598): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6598): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6598): Remote Branch: 
I/Adreno-EGL( 6598): Local Patches: 
I/Adreno-EGL( 6598): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb40274c0, uid 10079
,W/AudioManagerAndroid( 6598): Requires BLUETOOTH permission
I/NSApplication( 6598): Starting up...
,I/ActivityManager(  834): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6662 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  834): Killing 6161:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  834): failed to open /acct/uid_10036/pid_6161/cgroup.procs: No such file or directory
,I/ActivityManager(  834): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6681 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  834): Killing 6405:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  834): failed to open /acct/uid_10021/pid_6405/cgroup.procs: No such file or directory
,W/ResourcesManager( 6681): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 5539): SYNC; picasa accounts
,D/NetworkLogImpl( 5539): Loaded NetworkSpeedPredictor
I/iu.Environment( 5539): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  834): Killing 6433:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/iu.UploadsManager( 5539): num queued entries: 0
I/iu.UploadsManager( 5539): num updated entries: 0
I/iu.SyncManager( 5539): NEXT; no task
W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_6433/cgroup.procs: No such file or directory
,I/ActivityManager(  834): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6719 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6719): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6719): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6719): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6719): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6719): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6719): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6719): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6719): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6719): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c9b36b5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6719): Installed default security provider GmsCore_OpenSSL
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
D/AndroidMusic( 6719): GMSCore installation verified
,I/ConfigStore( 6719): Config Database version: 1
,E/UEI.SmartControl( 6452): file observer is disposed!
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MediaRouter( 6719): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6719): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6719): type=WIFI subType= reason=null isConnected=true
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/art     (  834): Explicit concurrent mark sweep GC freed 19928(948KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.144ms total 147.165ms
,I/NetworkMonitor( 6719): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  834): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6756 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6719): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6719): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  834): Killing 6475:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6756): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6756): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6756): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  834): failed to open /acct/uid_10011/pid_6475/cgroup.procs: No such file or directory
,I/NotificationManager( 6719): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6756): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6756): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6756): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  834): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6791 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6756): JNI_OnLoad()
I/HubEmail( 6756): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6756): registerNatives()
I/HubEmail( 6756): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6756): registerNativeMethods()
I/HubEmail( 6756): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6756): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  834): Killing 6508:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/UEI.SmartControl( 6452): Internal timer expired: 3
,W/libprocessgroup(  834): failed to open /acct/uid_10038/pid_6508/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6452): Service.onUnbind: IControl
D/UEI.SmartControl( 6452): Service.onDestroy
W/Settings( 6756): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UEI.SmartControl( 6452): Shutdown IRRCPlayer... 
W/irrc_jni( 6452): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6452): ~IrrcClient ++ 
D/irrcClient( 6452): ~IrrcClient -- 
W/irrc_jni( 6452): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6452): Blaster closed
D/UEI.SmartControl( 6452): Blaster closed
D/UEI.SmartControl( 6452): Shut down QS...
I/UEI.SmartControl( 6452): QS lib stop result = true
D/UEI.SmartControl( 6452): QS shutdown complete
D/LGDMClient( 6791): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6791): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6791): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6791): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6791): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6791): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6791): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6791): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  834): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6826 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/CheckinService( 5539): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  834): Process com.google.android.apps.magazines (pid 6598) has died
,W/ContextImpl( 6791): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6791): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6791): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6791): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6791): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6791): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 6826): onCreate
,W/AppUp4:DB( 6826):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6826):  setFingerPrint start
I/AppUp4:DB( 6826):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6826):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6826):  SDK version = 0
I/AppUp4:DB( 6826):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6826): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6826): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6826): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6826): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6826): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6826): onReceive
I/AppUp4:CustModeStarterReceiver( 6826): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6826): Context : android.app.ReceiverRestrictedContext@6eb98c9
D/AppUp4:CustFacade( 6826): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6826): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6826): begin check event
I/AppUp4:CustModeStarterReceiver( 6826): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6826): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6826): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6826): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6826): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  834): Killing 6452:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  834): failed to open /acct/uid_10089/pid_6452/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3229): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3229): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3229): networkInfo.isConnected() = false
I/ActivityManager(  834): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6852 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6852): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6852): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6852): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  834): Killing 6542:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/PhoneMonitor( 6852): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6852): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6852): [parse] Load xml
V/TelephonyAutoProfiling( 6852): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6852): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6852): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  834): failed to open /acct/uid_10051/pid_6542/cgroup.procs: No such file or directory
,V/DownloadManager( 3180): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3180): DownloadService onCreate
,I/ActivityManager(  834): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6873 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 286us total 24.145ms
I/NotificationManager( 3180): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3180): in removeSpuriousFiles
,I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 443us total 22.605ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 23.790ms
V/DownloadManager( 3180): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 5539): Checkin interval check for package: unspecified last checkin: 1454091923659 min interval config: 0 actual interval: 28242
,V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@2aebae8c on behalf of 3180
I/DownloadManager( 3180): in trimDatabase
V/DownloadManager( 3180): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@21d029d5 on behalf of 3180
V/DownloadManager( 3180): DownloadService onStartCommand
V/DownloadManager( 3180): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@1aeb2778 on behalf of 3180
I/CheckinService( 5539): Checking schedule, now: 1454091951938 next: 1454091953617
I/CheckinService( 5539): active receiver: disabled
,I/ActivityManager(  834): Killing 6562:com.google.android.talk/u0a61 (adj 15): empty #11
,D/WeatherAncestor( 2651): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:25:52
W/libprocessgroup(  834): failed to open /acct/uid_10061/pid_6562/cgroup.procs: No such file or directory
,V/DownloadManager( 3180): DownloadService onDestroy
D/UpdateThreadPoolManager( 2651): 2 : This is isUpdating : false
D/WeatherAncestor( 2651): connectivity changed - connection : true
D/Weather_cast( 2651): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2651): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:25:52
D/WeatherService( 2651): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  834): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6902 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  834): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2651): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2651): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2651): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6902): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6902): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6902): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6902): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6902): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6902): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6902): MmsConfig.loadFromResources
E/Babel_SMS( 6902): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6902): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6902): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6902): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6902): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6902): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6902): found sensor: LGE Gravity Sensor, handle=29
,D/SensorManager( 6902): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6902): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6902): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6902): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6902): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6902): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6902): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6902): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6902): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6902): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6902): found sensor: Motion Accel, handle=46
,W/Settings( 6902): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6902): startup - clean
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     ( 6902): CheckpointMarkThreadRoots callback created = 0xb042d460
,I/Babel   ( 6902): deleted: false for 0
,I/art     ( 6902): CheckpointMarkThreadRoots callback created = 0xb042d430
,I/ActivityManager(  834): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6936 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6902): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6902): Unsupported mime audio/adpcm
W/AudioCapabilities( 6902): Unsupported mime audio/g726
W/AudioCapabilities( 6902): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6902): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6902): Unsupported mime video/mjpg
,W/VideoCapabilities( 6902): Unsupported mime video/theora
W/AudioCapabilities( 6902): Unsupported mime audio/evrc
W/AudioCapabilities( 6902): Unsupported mime audio/qcelp
W/VideoCapabilities( 6902): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6902): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6902): Unsupported mime audio/qcelp
W/AudioCapabilities( 6902): Unsupported mime audio/evrc
W/VideoCapabilities( 6902): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6902): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6902): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6902): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6902): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6902): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6902): onServiceConnected
W/Babel   ( 6902): Attempted to change video mute state without an active call.
I/NotificationManager( 6902): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6902): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6902): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6902): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6902): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6902): propertyValue:false
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6936): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6936): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 6902): connection state changed from UNKNOWN to CONNECTED
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6936): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6936): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/ActivityManager(  834): Killing 6662:com.android.chrome/u0a48 (adj 15): empty #11
I/GAv4    ( 6936): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6936):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6936):   adb logcat -s GAv4
W/libprocessgroup(  834): failed to open /acct/uid_10048/pid_6662/cgroup.procs: No such file or directory
,W/GAv4    ( 6936): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6936): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6936): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6936): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6936): Time to load native libraries: 2 ms (timestamps 7611-7613)
I/LibraryLoader( 6936): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6936): Binding Chromium to main looper Looper (main, tid 1) {2e624842}
I/LibraryLoader( 6936): Expected native library version number "",actual native library version number ""
I/chromium( 6936): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6936): Initializing chromium process, singleProcess=true
W/art     ( 6936): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6936): ApplicationContext is null in ApplicationStatus
,W/chromium( 6936): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6936): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6936): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6936): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6936): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6936): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6936): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6936): Remote Branch: 
I/Adreno-EGL( 6936): Local Patches: 
I/Adreno-EGL( 6936): Reconstruct Branch: 
V/AudioPolicyService(  283): registerClient() client 0xb40274e0, uid 10079
,W/AudioManagerAndroid( 6936): Requires BLUETOOTH permission
I/NSApplication( 6936): Starting up...
I/ActivityManager(  834): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7000 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  834): Killing 6681:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  834): failed to open /acct/uid_10086/pid_6681/cgroup.procs: No such file or directory
,I/ActivityManager(  834): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7019 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  834): Killing 6719:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  834): failed to open /acct/uid_10081/pid_6719/cgroup.procs: No such file or directory
,W/ResourcesManager( 7019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  834): Killing 6756:com.lge.email/u0a21 (adj 15): empty #11
,I/jxcore-log( 5653): Test app app.js loaded
I/jxcore-log( 5653): 
,W/libprocessgroup(  834): failed to open /acct/uid_10021/pid_6756/cgroup.procs: No such file or directory
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5653): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 5653): BLE advertisement is supported
I/jxcore-log( 5653): 
,I/ActivityManager(  834): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7051 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/chromium( 5653): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ResourcesManager( 7051): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  834): Message: 20
D/BluetoothManagerService(  834): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19c59238:true
,D/BluetoothAdapterService(703580668)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@39e81732
D/BluetoothAdapterService(703580668)( 1984): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@39e81732
I/AudioManager( 7051): getMode name:com.lge.qremote
,I/AudioManager( 7051): getMode name:com.lge.qremote
,I/ActivityManager(  834): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7070 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7070): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7070): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7070): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7070): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7070): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7070): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7070): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7070): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7070): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c9b36b5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7070): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7070): GMSCore installation verified
I/ConfigStore( 7070): Config Database version: 1
,I/art     ( 5468): Explicit concurrent mark sweep GC freed 2348(91KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 450us total 46.284ms
,I/art     (  834): Explicit concurrent mark sweep GC freed 19323(971KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.243ms total 137.360ms
,I/MediaRouter( 7070): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7070): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7070): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7070): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  834): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7103 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7070): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7070): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  834): Killing 6791:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 7103): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7103): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7103): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_6791/cgroup.procs: No such file or directory
I/NotificationManager( 7070): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 7103): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7103): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7103): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  834): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7131 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 7103): JNI_OnLoad()
I/HubEmail( 7103): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7103): registerNatives()
I/HubEmail( 7103): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7103): registerNativeMethods()
I/HubEmail( 7103): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7103): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  834): Killing 6826:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  834): failed to open /acct/uid_10011/pid_6826/cgroup.procs: No such file or directory
,W/Settings( 7103): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7131): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7131): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7131): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7131): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7131): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7131): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7131): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7131): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  834): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7158 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7131): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7131): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7131): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7131): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7131): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7131): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  834): Killing 6852:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/AppUp4:AppBoxCP( 7158): onCreate
,W/AppUp4:DB( 7158):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7158):  setFingerPrint start
I/AppUp4:DB( 7158):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7158):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7158):  SDK version = 0
I/AppUp4:DB( 7158):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  834): failed to open /acct/uid_10038/pid_6852/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 7158): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7158): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7158): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7158): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7158): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7158): onReceive
I/AppUp4:CustModeStarterReceiver( 7158): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7158): Context : android.app.ReceiverRestrictedContext@6eb98c9
,D/AppUp4:CustFacade( 7158): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7158): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7158): begin check event
I/AppUp4:CustModeStarterReceiver( 7158): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7158): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7158): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7158): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7158): handleAsyncCustNotification do not startCustService
I/ActivityManager(  834): Killing 6873:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  834): failed to open /acct/uid_10051/pid_6873/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3229): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3229): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3229): networkInfo.isConnected() = true
D/PhoneState( 3229): setPdpRejectCasuse : false
I/ActivityManager(  834): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7177 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7177): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7177): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7177): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  834): Killing 6902:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7177): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7177): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7177): [parse] Load xml
V/TelephonyAutoProfiling( 7177): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7177): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7177): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  834): failed to open /acct/uid_10061/pid_6902/cgroup.procs: No such file or directory
V/DownloadManager( 3180): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3180): DownloadService onCreate
I/NotificationManager( 3180): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3180): in removeSpuriousFiles
V/DownloadManager( 3180): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@3dfd76b6 on behalf of 3180
I/DownloadManager( 3180): in trimDatabase
V/DownloadManager( 3180): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/CheckinService( 5539): Checkin interval check for package: unspecified last checkin: 1454091923659 min interval config: 0 actual interval: 32667
V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@5674324 on behalf of 3180
I/ActivityManager(  834): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7200 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3180): DownloadService onStartCommand
I/CheckinService( 5539): Checking schedule, now: 1454091956349 next: 1454091953617
I/CheckinService( 5539): active receiver: enabled
V/DownloadManager( 3180): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/art     (  305): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 344us total 29.382ms
,V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@2e624842 on behalf of 3180
I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 20.575ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.826ms
I/CheckinService( 5539): Preparing to send checkin request
,V/DownloadManager( 3180): DownloadService onDestroy
I/EventLogService( 5539): Accumulating logs since 1454091916412
,D/WeatherAncestor( 2651): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:25:56
,D/UpdateThreadPoolManager( 2651): 2 : This is isUpdating : false
D/WeatherAncestor( 2651): connectivity changed - connection : true
D/Weather_cast( 2651): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2651): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:25:56
D/WeatherService( 2651): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  834): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7223 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  834): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2651): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2651): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2651): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7223): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5539): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5539): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Babel_SMS( 7223): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7223): MmsConfig.loadMmsSettings
I/Babel_SMS( 7223): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7223): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7223): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7223): MmsConfig.loadFromResources
,E/Babel_SMS( 7223): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7223): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7223): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7223): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7223): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7223): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7223): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7223): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7223): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7223): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7223): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7223): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7223): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7223): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7223): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7223): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7223): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7223): found sensor: Motion Accel, handle=46
,I/art     ( 7223): CheckpointMarkThreadRoots callback created = 0xb042d810
,I/art     ( 7223): CheckpointMarkThreadRoots callback created = 0xb042d7e0
,I/ActivityManager(  834): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7258 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  834): Process com.google.android.apps.magazines (pid 6936) has died
,W/Settings( 7223): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7223): startup - clean
W/ResourcesManager( 7258): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7258): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel   ( 7223): deleted: false for 0
,I/MultiDex( 7258): VM with version 2.1.0 has multidex support
I/MultiDex( 7258): install
I/MultiDex( 7258): VM has multidex support, MultiDex support library is disabled.
,W/AudioCapabilities( 7223): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7223): Unsupported mime audio/adpcm
W/AudioCapabilities( 7223): Unsupported mime audio/g726
W/AudioCapabilities( 7223): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7223): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7223): Unsupported mime video/mjpg
W/VideoCapabilities( 7223): Unsupported mime video/theora
I/ActivityManager(  834): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7281 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7223): Unsupported mime audio/evrc
,W/AudioCapabilities( 7223): Unsupported mime audio/qcelp
W/VideoCapabilities( 7223): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7223): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7223): Unsupported mime audio/qcelp
W/AudioCapabilities( 7223): Unsupported mime audio/evrc
V/JNIHelp ( 7258): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/VideoCapabilities( 7223): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7223): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7223): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7223): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7223): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7223): Unrecognized profile 2130706433 for video/avc
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7281): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7281): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/vclib   ( 7223): onServiceConnected
W/Babel   ( 7223): Attempted to change video mute state without an active call.
W/ActivityThread( 7258): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7258): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@4eb1692: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7258): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7258): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7258): com.google.android.gms: cancel(39789) by com.google.android.gms
I/GAv4    ( 7281): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7281):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7281):   adb logcat -s GAv4
,D/libc-netbsd( 7223): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7223): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager( 7223): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7223): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7223): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7223): propertyValue:false
W/GAv4    ( 7281): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7281): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7281): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7281): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7223): connection state changed from UNKNOWN to CONNECTED
W/GAv4    ( 7281): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/art     ( 7258): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7258): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,V/AlarmManager(  834): RTC_WAKEUP set : Alarm{3264b02a type 0 when 1454091953617 com.google.android.gms} when 1454091953617
,I/ActivityManager(  834): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7317 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  834): RTC_WAKEUP set : Alarm{d07fe1b type 0 when 1454091957677 com.android.vending} when 1454091957677
D/NativeLibraryUtils( 7258): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  283): Instantiating CDM.
,I/WVCdm   (  283): CdmEngine::OpenSession
I/WVCdm   (  283): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  283): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  283): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  283): L1 library not specified. Falling Back to L3
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=254849714
D/Finsky  ( 7317): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/WebViewFactory( 7281): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  834): Process com.google.android.music:main (pid 7070) has died
,I/LibraryLoader( 7281): Time to load native libraries: 4 ms (timestamps 2431-2435)
,I/LibraryLoader( 7281): Expected native library version number "",actual native library version number ""
D/Finsky  ( 7317): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
V/WebViewChromiumFactoryProvider( 7281): Binding Chromium to main looper Looper (main, tid 1) {2e624842}
I/LibraryLoader( 7281): Expected native library version number "",actual native library version number ""
I/chromium( 7281): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/Settings( 7317): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7317): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/BrowserStartupController( 7281): Initializing chromium process, singleProcess=true
I/NotificationManager( 7317): com.android.vending: cancel(-1050172287) by com.android.vending
I/art     ( 7258): CheckpointMarkThreadRoots callback created = 0xb04cbe40
W/art     ( 7281): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7281): ApplicationContext is null in ApplicationStatus
,I/art     ( 7258): CheckpointMarkThreadRoots callback created = 0xb04cbe30
W/chromium( 7281): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7281): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7281): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7281): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7281): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7281): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7281): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7281): Remote Branch: 
I/Adreno-EGL( 7281): Local Patches: 
I/Adreno-EGL( 7281): Reconstruct Branch: 
,D/Ads     ( 7317): Skipping gmscore version check
D/Finsky  ( 7317): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7317): [1] Libraries$2.run: Finished loading 1 libraries.
I/dex2oat ( 7377): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,V/AudioPolicyService(  283): registerClient() client 0xb3825660, uid 10079
,W/AudioManagerAndroid( 7281): Requires BLUETOOTH permission
I/art     (  834): Explicit concurrent mark sweep GC freed 19906(936KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.956ms total 196.418ms
I/NSApplication( 7281): Starting up...
V/DownloadManager( 3180): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@37676d90 on behalf of 7317
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/dex2oat ( 7377): dex2oat took 153.817ms (threads: 4)
,I/Adreno-EGL( 7258): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7258): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7258): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7258): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7258): Remote Branch: 
I/Adreno-EGL( 7258): Local Patches: 
I/Adreno-EGL( 7258): Reconstruct Branch: 
I/AudioManager( 7051): getMode name:com.lge.qremote
,I/AudioManager( 7051): getMode name:com.lge.qremote
D/Finsky  ( 7317): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  834): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7396 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 7317): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Adreno-EGL( 7258): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7258): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7258): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7258): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7258): Remote Branch: 
I/Adreno-EGL( 7258): Local Patches: 
I/Adreno-EGL( 7258): Reconstruct Branch: 
,D/Finsky  ( 7317): [920] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7317): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  834): Killing 7103:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  834): failed to open /acct/uid_10021/pid_7103/cgroup.procs: No such file or directory
,W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 7396): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7396): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7396): Error finding the version of the Email provider.....
E/Gmail   ( 7396): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7396): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7396): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7396): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7396): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7396): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7396): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7396): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  834): Killing 7131:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_7131/cgroup.procs: No such file or directory
,W/ActivityManager(  834): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/WearableService( 1731): callingUid 10006, callindPid: 1731
,I/WVCdm   (  283): CdmEngine::OpenSession
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationInitializer( 5539): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1731): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7396): Observing account changes for notifications
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/GCoreFlp( 1731): No location to return for getLastLocation()
,W/FusedLocationProvider( 1731): location=null
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/Finsky  ( 7317): [925] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/NotificationManager(  834): android: cancelAsUser(2) by android
I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Gmail   ( 7396): notifyAccountChanged
I/Gmail   ( 7396): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7396): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  834): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7452 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 7396): getAccountsCursor
D/libc-netbsd( 7317): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7317): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7317): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7317): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Gmail   ( 7396): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7396): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/LGMDMManager( 7051): Create singleton instance
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7317): propertyValue:false
,D/UEI.SmartControl( 7452): Quickset Services start...
,I/UEI.SmartControl( 7452): Manufacture = LGE
I/AudioManager( 7051): getMode name:com.lge.qremote
D/UEI.SmartControl( 7452): File observer start...
,E/UEI.SmartControl( 7452): IR Port is disabled: false
D/UEI.SmartControl( 7452): Starting file observer...
D/UEI.SmartControl( 7452): Extracting JNI libs...
D/UEI.SmartControl( 7452): --- this system supports 32-bit or 64-bit only
E/MDM     ( 1731): [124] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5539): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,I/CheckinService( 5539): Checkin interval check for package: unspecified last checkin: 1454091923659 min interval config: 0 actual interval: 36141
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
D/UEI.SmartControl( 7452): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7452): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7452): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/Gmail   ( 7396): getAccountsCursor
,W/ContextImpl( 3580): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UEI.SmartControl( 7452): --- Selecting new region: 2
I/UEI.SmartControl( 7452): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7452): Platform has CIR...
D/UEI.SmartControl( 7452): NO CIR support, need to check package...
I/UEI.SmartControl( 7452): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 7452): QS Service created
E/UEI.SmartControl( 7452): QS start get config
,D/UEI.SmartControl( 7452): Loading JNI Libs...
,D/PowerManagerServiceEx(  834): acquireWakeLockInternal: lock=987681739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=834
D/UEI.SmartControl( 7452):  configuring local db...
D/WeatherService( 2651): 2 : TimeTick Intent has been received, Time(hour:min:sec) 19:26:0
,D/WeatherService( 2651): 2 : TimeTick Intent And Screen On
D/WeatherService( 2651): 2 : SDK version : 21
W/ActivityManager(  834): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2651): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2651): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2651): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2651): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2651): 2 : This is isUpdating : false
D/WeatherService( 2651): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2651): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2651): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2651): 2 : Fixed theme : optimus
D/WeatherReflect( 2651): 2 : Map key string is -2
,D/lim     ( 2651): 2 : time = 19:26
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/WeatherReflect( 2651): Model Name : LG-D722
D/WeatherTheme( 2651): 2 : Different view - status_min_formatted : 25 != 26
D/WeatherTheme( 2651): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2651): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/Theme   ( 2651): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2651): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2651): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2651): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2651): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2651): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2651): forecast size is 0
D/Theme   ( 2651): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2651): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2651): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2651): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2651): EnableTheme(home): com.lge.launcher2.theme.optimus
,D/Theme   ( 2651): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2651): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2651): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2651): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2651): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2651): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2651): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2651): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2651): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2651): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2651): url is : null
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/Theme   ( 2651): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2651): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2651): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2651): 2 : update view, appWidgetId: 2
D/WeatherService( 2651): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 19:26:0
D/PowerManagerServiceEx(  834): releaseWakeLockInternal: lock=987681739 [*alarm*], flags=0x0
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  283): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  283): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  283): CdmEngine::GenerateKeyRequest
D/WVCdm   (  283): PrepareKeyRequest: nonce=214900710
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/UEI.SmartControl( 7452):  ---- Has DB8: true
,D/UEI.SmartControl( 7452): QS start statue = true Error code = 0
D/UEI.SmartControl( 7452): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7452): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7452): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7452): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7452): IrrcClient ++ 
D/irrcClient( 7452): getIrrcService ++ 
,D/irrcClient( 7452): getIrrcService -- 
D/irrcClient( 7452): IrrcClient -- 
W/irrc_jni( 7452): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7452): Services init done
D/UEI.SmartControl( 7452): QS Service init finished
D/UEI.SmartControl( 7452): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7452): QS Service version code: 1073
I/UEI.SmartControl( 7452): Device manager: loading config....
D/UEI.SmartControl( 7452): Service requested: Control
D/UEI.SmartControl( 7452): Config is loaded...
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/UEI.SmartControl( 7452):  ----- QS SDK is ready!!!
,D/UEI.SmartControl( 7452): Request IControl service: devices are loaded...
I/UEI.SmartControl( 7452): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7452): Internal service binding...
D/UEI.SmartControl( 7452): -----IControl: 11
D/UEI.SmartControl( 7452): Caller: com.lge.qremote
D/UEI.SmartControl( 7452): ------------ IControl registerCallback...
,I/UEI.SmartControl( 7452): Registering callback...
D/UEI.SmartControl( 7452): -----IControl: 19
D/UEI.SmartControl( 7452): Caller: com.lge.qremote
I/UEI.SmartControl( 7452): Registering Services Ready callback...
I/UEI.SmartControl( 7452): Notify client services are ready...
D/UEI.SmartControl( 7452): -----IControl: 8
D/UEI.SmartControl( 7452): Caller: com.lge.qremote
I/AudioManager( 7051): getMode name:com.lge.qremote
,I/ActivityManager(  834): Killing 7200:com.lge.drmservice/u0a51 (adj 15): empty #11
I/ActivityManager(  834): Killing 7158:com.lge.appbox.client/u0a11 (adj 15): empty #12
,W/libprocessgroup(  834): failed to open /acct/uid_10051/pid_7200/cgroup.procs: No such file or directory
,W/libprocessgroup(  834): failed to open /acct/uid_10011/pid_7158/cgroup.procs: No such file or directory
I/AudioManager( 7051): getMode name:com.lge.qremote
I/AudioManager( 7051): getMode name:com.lge.qremote
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 115516577825; DSPS: 3883413; Offset : -3007599707
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/MusicWidget( 2606): mDelayedStopHandler : unbind
,I/MusicBrowser( 2007): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2007): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2007): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2007): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2007): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2007): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
,I/MusicBrowser( 2007): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2007): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  834):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@197c747ecom.lge.music.MediaPlaybackService$6@1cf02ddf
D/MusicBrowser( 2007): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2007): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2007): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2007): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2007): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1f8bf885
I/MusicBrowser( 2007): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2007): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2007): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2007): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2007): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2007): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2007): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2007): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2007): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2007): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2007): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2007): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2007): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2007): reset
V/MediaPlayer[Native]( 2007): setListener
V/MediaPlayer[Native]( 2007): disconnect
V/MediaPlayer[Native]( 2007): destructor
V/AudioFlinger(  283): releasing 19 from 2007 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/MediaPlayer[Native]( 2007): disconnect
D/MusicBrowser( 2007): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
,I/SmartShareClient( 2007): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2007): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2007): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
,I/MusicBrowser( 2007): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2007): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2007): [SmartShareManagerClient] unregisterListener: 431467052
W/SmartShareClient( 2007): [SmartShareManagerClient] unregisterListener invalid listener: 431467052
I/SmartShareClient( 2007): [SmartShareManagerClient] terminate service: 2007/MediaPlaybackService/983505043
E/HomeCloudIF( 2007): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2007): [SmartShareManagerClient] unbindService context:android.app.Application@33150cf5
V/CloudHub( 2007): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2007): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2007): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2007): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2007): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  834): Killing 7281:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/CloudHub( 2007): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29991
,I/WVCdm   (  283): CdmEngine::CloseSession
,I/WVCdm   (  283): L3 Terminate.
I/Adreno-EGL( 7258): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7258): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7258): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7258): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7258): Remote Branch: 
I/Adreno-EGL( 7258): Local Patches: 
I/Adreno-EGL( 7258): Reconstruct Branch: 
,W/libprocessgroup(  834): failed to open /acct/uid_10079/pid_7281/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 5539): Classify the device as Phone.
,D/libc-netbsd( 5539): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5539): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5539): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5539): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 5539): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd( 5539): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5539): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5539): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5539): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5539): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5539): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5539): Sending checkin request (9800 bytes)
,I/CheckinRequestBuilder( 5539): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5539): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 5468): Explicit concurrent mark sweep GC freed 3231(130KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.517ms total 27.668ms
,I/CheckinRequestBuilder( 5539): Classify the device as Phone.
,I/CheckinTask( 5539): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5539): Checking schedule, now: 1454091963914 next: 1454619212907
I/CheckinService( 5539): active receiver: disabled
,I/CheckinService( 5539): Checking schedule, now: 1454091963957 next: 1454619212907
I/CheckinService( 5539): active receiver: disabled
,D/CheckinService( 5539): Recording last checkin time for package unspecified as 1454091963965
V/SetupWizard( 7177): Connected to Gservices successfully
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/art     (  834): Explicit concurrent mark sweep GC freed 20210(951KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.249ms total 158.060ms
,I/GAV2    ( 7396): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 5539): Google Analytics 8.4.89 is starting up.
I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/ActivityManager(  834): Killing 7019:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/ActivityManager(  834): Killing 7000:com.android.chrome/u0a48 (adj 15): empty #12
,W/libprocessgroup(  834): failed to open /acct/uid_10086/pid_7019/cgroup.procs: No such file or directory
,W/libprocessgroup(  834): failed to open /acct/uid_10048/pid_7000/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7452): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/InputReader(  834): Reconfiguring input devices.  changes=0x00000010
,D/administrator(  834): Handling package changes for user 0
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/ActivityManager(  834): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7543 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationManager( 7223): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7223): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7223): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7543): onCreate
W/AppUp4:DB( 7543):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7543):  setFingerPrint start
,I/AppUp4:DB( 7543):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7543):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7543):  SDK version = 0
I/AppUp4:DB( 7543):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7543): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7543): onReceive
I/AppUp4:CustModeStarterReceiver( 7543): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7543): Context : android.app.ReceiverRestrictedContext@15064982
,D/AppUp4:CustFacade( 7543): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7543): isSimDevice : true
V/JNIHelp ( 7223): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AppUp4:CustModeStarterReceiver( 7543): begin check event
I/AppUp4:CustModeStarterReceiver( 7543): Event For Nothing, skip.
,I/NotificationService(  834): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  834): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  834): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  834): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7565 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/BackupManagerService(  834): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/System  ( 7223): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7223): Installed default security provider GmsCore_OpenSSL
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/BackupManagerService(  834): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  834): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@23ffa57b
,W/ResourcesManager( 7565): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7565): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7565): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager(  834): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
W/ResourceType(  834): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  834): Process com.android.vending (pid 7317) has died
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/AppConfig( 7565): Total System Memory = 906309632
I/GalleryUtils( 7565): Application Heap = 96 MB
I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppConfig( 7565): App Tier : NOT_DEF
,D/SystemHelper( 7565): region [EU], country [EU], operator [OPEN], sub-operator []
,D/LocationProviderProxy(  834): applying state to connected service
I/ActivityManager(  834): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7590 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7590): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7590): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7590): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7590): BUILD Country: EU
I/SystemConfig( 7590): BUILD Operator: OPEN
,I/ActivityManager(  834): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7612 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  834): Killing 7396:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  834): failed to open /acct/uid_10053/pid_7396/cgroup.procs: No such file or directory
,I/SystemConfig( 7590): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7590): existFile = false
I/SystemConfig( 7590): canReadFile = false
I/SystemConfig( 7590): systemFeature RCS result false
D/SystemConfig( 7590): refreshRcsSupport() :false
I/LockScreenSettings( 7612): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7612): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7612): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7612): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7612): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7612): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  834): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7629 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  834): Killing 2007:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  283): 2007 died, releasing its sessions
V/AudioFlinger(  283):  pid 1749 @ 0
V/AudioFlinger(  283):  pid 3229 @ 1
V/AudioFlinger(  283):  pid 3229 @ 2
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 24.739ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 20.789ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.597ms
,W/libprocessgroup(  834): failed to open /acct/uid_10028/pid_2007/cgroup.procs: No such file or directory
,W/ResourcesManager( 7629): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  834): Killing 7177:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 72 ms] updated apps [took 72 ms] 
,I/ActivityManager(  834): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7663 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  834): failed to open /acct/uid_10038/pid_7177/cgroup.procs: No such file or directory
,D/Finsky  ( 7663): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7663): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7663): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7663): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7663): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3180): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3180): created cursor android.database.sqlite.SQLiteCursor@27cbb689 on behalf of 7663
,D/Finsky  ( 7663): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7663): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7663): Skipping gmscore version check
,I/ActivityManager(  834): Killing 7258:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,D/Finsky  ( 7663): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 5539): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
W/libprocessgroup(  834): failed to open /acct/uid_10006/pid_7258/cgroup.procs: No such file or directory
I/PackageBroadcastService( 5539): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7663): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5539): updateResources: need to parse f{com.google.android.gms}
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/Icing   ( 5539): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Icing   ( 5539): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  834): Killing 7452:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7051): android.os.DeadObjectException
,W/System.err( 7051): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7051): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7051): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7051): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7051): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7051): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7051): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7051): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7051): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7051): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7051): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7051): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7051): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7051): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7051): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7051): android.os.DeadObjectException
W/System.err( 7051): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7051): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7051): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7051): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7051): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7051): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7051): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7051): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7051): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7051): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7051): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7051): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7051): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7051): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7051): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  834): failed to open /acct/uid_10089/pid_7452/cgroup.procs: No such file or directory
W/ActivityManager(  834): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  834): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7742 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7742): Quickset Services start...
,I/UEI.SmartControl( 7742): Manufacture = LGE
D/UEI.SmartControl( 7742): File observer start...
E/UEI.SmartControl( 7742): IR Port is disabled: false
D/UEI.SmartControl( 7742): Starting file observer...
D/UEI.SmartControl( 7742): Extracting JNI libs...
D/UEI.SmartControl( 7742): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7742): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7742): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7742): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7742): --- Selecting new region: 2
,I/UEI.SmartControl( 7742): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7742): Platform has CIR...
D/UEI.SmartControl( 7742): NO CIR support, need to check package...
I/UEI.SmartControl( 7742): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7742): QS Service created
E/UEI.SmartControl( 7742): QS start get config
,D/UEI.SmartControl( 7742): Loading JNI Libs...
,D/UEI.SmartControl( 7742):  configuring local db...
D/UEI.SmartControl( 7742):  ---- Has DB8: true
,D/UEI.SmartControl( 7742): QS start statue = true Error code = 0
D/UEI.SmartControl( 7742): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7742): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7742): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7742): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7742): IrrcClient ++ 
D/irrcClient( 7742): getIrrcService ++ 
D/irrcClient( 7742): getIrrcService -- 
D/irrcClient( 7742): IrrcClient -- 
W/irrc_jni( 7742): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7742): Services init done
,I/UEI.SmartControl( 7742): Device manager: loading config....
D/UEI.SmartControl( 7742): QS Service init finished
D/UEI.SmartControl( 7742): QS Service version name: 0.1.73
D/UEI.SmartControl( 7742): QS Service version code: 1073
D/UEI.SmartControl( 7742): Service requested: Control
D/UEI.SmartControl( 7742): Config is loaded...
D/UEI.SmartControl( 7742):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7742): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7742): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7742): -----IControl: 11
D/UEI.SmartControl( 7742): Caller: com.lge.qremote
I/ActivityManager(  834): Killing 7051:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7742): ------------ IControl registerCallback...
I/UEI.SmartControl( 7742): Registering callback...
W/libprocessgroup(  834): failed to open /acct/uid_10106/pid_7051/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7742): Internal service binding...
D/charger_monitor(  489): init target 500000
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
,D/charger_monitor(  489): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 302, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 302
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 302
D/WifiController(  834): battery changed pluggedType: 2
,W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7742): Internal timer expired: 1
,D/UEI.SmartControl( 7742): Service.onUnbind: IControl
D/UEI.SmartControl( 7742): Service.onDestroy
W/System.err( 7742): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@29efc9fc
W/System.err( 7742): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7742): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7742): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7742): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7742): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7742): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7742): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7742): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7742): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7742): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7742): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7742): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7742): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7742): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7742): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7742): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@29efc9fc
D/UEI.SmartControl( 7742): Shutdown IRRCPlayer... 
W/irrc_jni( 7742): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7742): ~IrrcClient ++ 
D/irrcClient( 7742): ~IrrcClient -- 
W/irrc_jni( 7742): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7742): Blaster closed
D/UEI.SmartControl( 7742): Blaster closed
,D/UEI.SmartControl( 7742): Shut down QS...
D/UEI.SmartControl( 7742): Stopped file observer...
I/UEI.SmartControl( 7742): QS lib stop result = true
D/UEI.SmartControl( 7742): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 135517369119; DSPS: 4538799; Offset : -3007601766
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{25922458 type 2 when 145383 com.google.android.gms} when 145383
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1731): Vacuum at: now=1454091991480 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/PowerManagerService(  834): ALS enabled for SRE
D/PowerManagerServiceEx(  834): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29469 ms ago)
,D/qdlights(  834): set_light_backlight: 253
,D/qdlights(  834): set_light_backlight: 250
D/qdlights(  834): set_light_backlight: 246
,D/qdlights(  834): set_light_backlight: 243
,D/qdlights(  834): set_light_backlight: 240
,D/qdlights(  834): set_light_backlight: 236
,D/qdlights(  834): set_light_backlight: 233
,D/qdlights(  834): set_light_backlight: 230
,D/qdlights(  834): set_light_backlight: 226
,D/qdlights(  834): set_light_backlight: 223
,D/qdlights(  834): set_light_backlight: 220
,D/qdlights(  834): set_light_backlight: 216
,D/qdlights(  834): set_light_backlight: 213
,D/qdlights(  834): set_light_backlight: 210
,D/qdlights(  834): set_light_backlight: 206
,D/qdlights(  834): set_light_backlight: 203
,D/qdlights(  834): set_light_backlight: 200
,D/qdlights(  834): set_light_backlight: 196
,D/qdlights(  834): set_light_backlight: 193
,D/qdlights(  834): set_light_backlight: 190
,D/qdlights(  834): set_light_backlight: 186
,D/qdlights(  834): set_light_backlight: 183
,D/qdlights(  834): set_light_backlight: 180
,D/qdlights(  834): set_light_backlight: 176
,D/qdlights(  834): set_light_backlight: 173
,D/qdlights(  834): set_light_backlight: 170
,D/qdlights(  834): set_light_backlight: 166
,D/qdlights(  834): set_light_backlight: 163
,D/qdlights(  834): set_light_backlight: 160
,D/qdlights(  834): set_light_backlight: 156
,D/qdlights(  834): set_light_backlight: 153
,D/qdlights(  834): set_light_backlight: 150
,D/qdlights(  834): set_light_backlight: 146
,D/qdlights(  834): set_light_backlight: 143
,D/qdlights(  834): set_light_backlight: 140
,D/qdlights(  834): set_light_backlight: 136
,D/qdlights(  834): set_light_backlight: 133
,D/qdlights(  834): set_light_backlight: 130
,D/qdlights(  834): set_light_backlight: 126
,D/qdlights(  834): set_light_backlight: 123
,D/qdlights(  834): set_light_backlight: 120
,D/qdlights(  834): set_light_backlight: 116
,D/qdlights(  834): set_light_backlight: 113
,D/qdlights(  834): set_light_backlight: 110
,D/qdlights(  834): set_light_backlight: 106
,D/qdlights(  834): set_light_backlight: 103
,D/qdlights(  834): set_light_backlight: 100
,D/qdlights(  834): set_light_backlight: 96
,D/qdlights(  834): set_light_backlight: 93
,D/qdlights(  834): set_light_backlight: 90
,D/qdlights(  834): set_light_backlight: 86
,D/qdlights(  834): set_light_backlight: 83
,D/qdlights(  834): set_light_backlight: 80
,D/qdlights(  834): set_light_backlight: 76
,D/qdlights(  834): set_light_backlight: 73
,D/qdlights(  834): set_light_backlight: 70
,D/qdlights(  834): set_light_backlight: 66
,D/qdlights(  834): set_light_backlight: 63
,D/qdlights(  834): set_light_backlight: 60
,D/qdlights(  834): set_light_backlight: 56
,D/qdlights(  834): set_light_backlight: 53
,D/qdlights(  834): set_light_backlight: 50
,D/qdlights(  834): set_light_backlight: 46
,D/qdlights(  834): set_light_backlight: 43
,D/qdlights(  834): set_light_backlight: 40
,D/qdlights(  834): set_light_backlight: 36
,D/qdlights(  834): set_light_backlight: 33
,D/qdlights(  834): set_light_backlight: 30
,D/qdlights(  834): set_light_backlight: 26
,D/qdlights(  834): set_light_backlight: 23
,D/qdlights(  834): set_light_backlight: 20
,D/qdlights(  834): set_light_backlight: 16
,D/qdlights(  834): set_light_backlight: 13
,D/qdlights(  834): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 155520598539; DSPS: 5194265; Offset : -3007607080
,I/PowerManagerService(  834): ALS enabled for SRE
D/PowerManagerServiceEx(  834): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36465 ms ago)
I/PowerManagerService(  834): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  834): ALS enabled for SRE
D/PowerManagerServiceEx(  834): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36476 ms ago)
W/ContextImpl(  834): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  834): Sleeping (uid 1000)...
D/LPWGController(  834): [updateScreenState] screen on = false
D/LPWGController(  834): disable proximity sensor
D/LPWGController(  834): enable proximity sensor
,I/SensorManager(  834): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@dd7ade9] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  834): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  834): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  834): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  834): activate: handle is 48, enable
V/sensors_hal_Ctx(  834): activate sensors is 1400000000000
D/sensors_hal_Thresh(  834): enable: handle=48
I/sensors_hal_SAM(  834): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  834): waitForResponse: timeout=1000
V/sensors_hal_SAM(  834): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  834): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  834): enable: Received response: 0
D/PowerManagerServiceEx(  834): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36520 ms ago)
I/Adreno-EGL(  834): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  834): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  834): Build Date: 03/02/15 Mon
I/Adreno-EGL(  834): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  834): Remote Branch: 
I/Adreno-EGL(  834): Local Patches: 
I/Adreno-EGL(  834): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1027 us)
,I/Sensors (  418): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  834): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  834): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  834): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  834): processInd: handle 48, count=1
V/sensors_hal_Thresh(  834): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  834): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  834): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  834): poll: count: 256
I/sensors_hal_Ctx(  834): poll: released wakelock sensor_ind
D/sensors_hal_Util(  834): waitForResponse: timeout=0
D/LPWGController(  834): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  834): current mode = 1  value = 1 1
I/LPWGController(  834): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  834): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  834): set_light_backlight: 0
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/SensorManager(  834): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  834): activate: handle is 46, disable
V/sensors_hal_Ctx(  834): activate sensors is 1000000000000
D/sensors_hal_LP2(  834): enable: handle=46
D/sensors_hal_LP2(  834): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  834): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
,V/sensors_hal_SAM(  834): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  834): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  834): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  834): Display changed displayId=0
,D/DSDPConnection( 1749): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  834): Excessive delay in setPowerMode(): 211ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  834): Got set_interactive hint
,D/KeyguardViewMediator( 1369): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
D/KeyguardViewMediator( 1369): notifyScreenOffLocked
D/KeyguardViewMediator( 1369): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1369): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1369): unregisterProximitySensor
,D/WifiServerServiceExt(  834): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1369): onScreenTurnedOff why = 3
,V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=on, calling pid 834
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=on
V/voice   (  283): voice_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  283): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/WifiServerServiceExt(  834): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,D/GpsLocationProvider(  834): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:true
I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
,D/LNfcService( 1784): action : android.intent.action.SCREEN_ON
D/LEDService( 1802): stopPatternFlashing()
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/NfcServiceNXP( 1784): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1784): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 3
D/NfcService( 1784): Discovery configuration equal, not updating.
D/Cliptray Service( 1802): lockStatus = 0
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): updateLightsLocked : turn off led
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
,D/LEDHandler( 1802): RESTART MSG
D/Ulp_jni (  834): JNI:system_update. Event-0
,D/SplitWindow(  834): check instance of lgWin Window{3efe399c u0 SearchPanel}
,D/InputDispatcher(  834): Window went away: Window{286047a3 u0 SearchPanel}
,I/[SystemUI]Clock( 1369): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1369): time changed, timezoneChanged : false
,I/art     ( 1369): Background sticky concurrent mark sweep GC freed 57388(3MB) AllocSpace objects, 71(2MB) LOS objects, 19% free, 23MB/29MB, paused 1.576ms total 104.609ms
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
I/Sensors (  418): sns_pwr.c(301):releasing wakelock
,D/WeatherService( 2651): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:26:44
,D/WeatherService( 2651): 2 : ACTION screen on
D/WeatherService( 2651): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2651): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2651): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:26:44
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): ACTION_SCREEN_ON
,D/AppCleanupService( 4079): android.intent.action.SCREEN_ON
,V/AudioFlinger(  283): setParameters(): io 0, keyvalue screen_state=off, calling pid 834
D/audio_hw_primary(  283): adev_set_parameters: enter: screen_state=off
V/voice   (  283): voice_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  283): voice_extn_compress_voip_set_parameters: exit
V/voice   (  283): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  283): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  283): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  283): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  283): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  283): adev_set_parameters: exit with code(0)
D/WifiController(  834): CMD_SCREEN_OFF 
,D/WifiController(  834): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  834): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:false
,I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): updateLightsLocked : turn on led
,E/LEDService( 1802): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1802): Can't handle this request of patternId:0
D/LEDHandler( 1802): RESTART MSG
D/VolumeVibrator( 1802): clear
D/LNfcService( 1784): action : android.intent.action.SCREEN_OFF
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1784): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1876): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2651): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:26:44
D/WeatherService( 2651): 2 : ACTION screen off
D/WeatherService( 2651): 2 : TimeTick Receiver Unregister
D/WeatherService( 2651): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:26:44
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): ACTION_SCREEN_OFF
,D/AppCleanupService( 4079): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4079): AppUsageStatsSaveTask
,E/NxpNfcJni( 1784): getReconnectState = 0x0
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: 0
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 1
E/NxpNfcJni( 1784): getReconnectState = 0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{32743fa5 type 2 when 162418 com.android.systemui} when 162418
,D/KeyguardViewMediator( 1369): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
,V/TelecomServiceImpl( 1749): getCallState : 0
D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1369): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1369): doKeyguard: not showing because lockscreen is off
,I/ThermalEngine(  296): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 175521356865; DSPS: 5849649; Offset : -3007581384
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,D/PowerManagerServiceEx(  834): acquireWakeLockInternal: lock=987681739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=834
,V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{5818f7a type 2 when 184229 android} when 184229
D/PowerManagerServiceEx(  834): releaseWakeLockInternal: lock=987681739 [*alarm*], flags=0x0
,D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 298, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{43d732b type 2 when 188409 com.google.android.gms} when 188409
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 44126(2MB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 13MB/22MB, paused 2.729ms total 157.220ms
,I/PhenotypeConfigurator( 1731): Scheduling Phenotype for one-off execution 11688 seconds from now (1454092034807)
,D/GetConfigurationSnapshotOperation( 1731): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1731): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1731): Using platform SSLCertificateSocketFactory
I/art     (  834): Explicit concurrent mark sweep GC freed 52290(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 2.444ms total 253.877ms
,D/LocationManagerService(  834): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  834): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  834): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  834): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/ClearcutLoggerApiImpl( 1731): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 195522044044; DSPS: 6505032; Offset : -3007595952
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 215522869922; DSPS: 7160419; Offset : -3007595924
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 235523624550; DSPS: 7815804; Offset : -3007602569
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 255524305948; DSPS: 8471186; Offset : -3007592323
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 275525066097; DSPS: 9126571; Offset : -3007595192
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 295525818850; DSPS: 9781956; Offset : -3007605483
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 315526495717; DSPS: 10437338; Offset : -3007599716
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
,D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 335527246334; DSPS: 11092722; Offset : -3007582249
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  834): remove 3f23f5a4
,D/LocationManagerService(  834): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  834): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  834): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  834): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  834): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  834): acquireWakeLockInternal: lock=987681739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=834
,D/PowerManagerServiceEx(  834): releaseWakeLockInternal: lock=987681739 [*alarm*], flags=0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 355528183931; DSPS: 11748113; Offset : -3007590853
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 375528859027; DSPS: 12403495; Offset : -3007586468
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 395529593238; DSPS: 13058879; Offset : -3007586527
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 415530628856; DSPS: 13714273; Offset : -3007586737
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 435531458589; DSPS: 14369661; Offset : -3007611339
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 455532122956; DSPS: 15025042; Offset : -3007587815
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 475532853468; DSPS: 15680426; Offset : -3007589986
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 495533606430; DSPS: 16335811; Offset : -3007599962
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 515534267932; DSPS: 16991193; Offset : -3007609431
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 535535001518; DSPS: 17646577; Offset : -3007608058
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 555535761199; DSPS: 18301962; Offset : -3007611812
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 575536372076; DSPS: 18957342; Offset : -3007611885
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 595537117484; DSPS: 19612726; Offset : -3007598222
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 615537800446; DSPS: 20268108; Offset : -3007586412
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 635538526688; DSPS: 20923492; Offset : -3007592982
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 655539244598; DSPS: 21578876; Offset : -3007607364
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 675539923548; DSPS: 22234258; Offset : -3007599568
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 695540687968; DSPS: 22889643; Offset : -3007598529
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 715541430825; DSPS: 23545027; Offset : -3007587938
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 735542111599; DSPS: 24200410; Offset : -3007608756
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 755542848309; DSPS: 24855794; Offset : -3007606576
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 775543608615; DSPS: 25511179; Offset : -3007607335
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 795544345013; DSPS: 26166563; Offset : -3007603411
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 815545089120; DSPS: 26821947; Offset : -3007591935
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 835545825050; DSPS: 27477331; Offset : -3007588295
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 855546585198; DSPS: 28132716; Offset : -3007592676
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 875547300712; DSPS: 28788100; Offset : -3007608282
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 895548059141; DSPS: 29443485; Offset : -3007612297
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 915548818613; DSPS: 30098869; Offset : -3007585221
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 935549551157; DSPS: 30754253; Offset : -3007585151
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  834): acquireWakeLockInternal: lock=987681739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=834
,V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{11a57d1b type 2 when 952330 com.android.bluetooth} when 952330
W/bt-smp  ( 1984): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1984): Plain text(LSB ~ MSB) = ba cf 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1984): Encrypted text(LSB ~ MSB) = 89 0c d2 53 46 2d 12 da 45 5c ac c4 ba 4f 6d 7b 
W/bt-btm  ( 1984): Stopping oneshot timer
I/ActivityManager(  834): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7976 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 7976): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7976): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@15064982
,I/ActivityManager(  834): Killing 7223:com.google.android.talk/u0a61 (adj 15): empty #11
D/PowerManagerServiceEx(  834): releaseWakeLockInternal: lock=987681739 [*alarm*], flags=0x0
,W/libprocessgroup(  834): failed to open /acct/uid_10061/pid_7223/cgroup.procs: No such file or directory
I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 955550586254; DSPS: 31409647; Offset : -3007587574
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 975551351508; DSPS: 32065032; Offset : -3007585598
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 995552001135; DSPS: 32720414; Offset : -3007607253
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  834): acquireWakeLockInternal: lock=987681739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=834
,V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{d76aeb8 type 2 when 1013867 com.google.android.gms} when 1013867
D/PowerManagerServiceEx(  834): releaseWakeLockInternal: lock=987681739 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1015552765190; DSPS: 33375799; Offset : -3007606059
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1035553516745; DSPS: 34031183; Offset : -3007587499
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1055554192779; DSPS: 34686565; Offset : -3007581914
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1075554935687; DSPS: 35341950; Offset : -3007602285
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1095555611618; DSPS: 35997332; Offset : -3007597741
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1115556346870; DSPS: 36652716; Offset : -3007595197
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1135557078112; DSPS: 37308100; Offset : -3007596117
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1155557758938; DSPS: 37963482; Offset : -3007586704
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1175558545805; DSPS: 38618868; Offset : -3007593840
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1195559267048; DSPS: 39274252; Offset : -3007604341
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1984): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1215559950790; DSPS: 39929634; Offset : -3007591882
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  834): User[0] Flushing usage stats to disk
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1235560907970; DSPS: 40585026; Offset : -3007611317
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  834): acquireWakeLockInternal: lock=987681739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=834
,V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{3f14a491 type 2 when 1241135 android} when 1241135
,D/PowerManagerServiceEx(  834): releaseWakeLockInternal: lock=987681739 [*alarm*], flags=0x0
,I/NotificationManager(  834): android: cancelAsUser(-1548111331) by android
I/NotificationManager(  834): android: cancelAsUser(2145784878) by android
,I/NotificationManager( 7629): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1255561581765; DSPS: 41240408; Offset : -3007609298
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerManagerServiceEx(  834): acquireWakeLockInternal: lock=987681739, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=834
,V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{84f35e8 type 2 when 1271961 android} when 1271961
I/DigitalAppWidgetProvider( 7976): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7976): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@15064982
D/PowerManagerServiceEx(  834): releaseWakeLockInternal: lock=987681739 [*alarm*], flags=0x0
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1275562262538; DSPS: 41895790; Offset : -3007599757
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
D/AndroidRuntime( 8081): 
D/AndroidRuntime( 8081): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8081): CheckJNI is OFF
D/sensors_hal_Time(  834): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  834): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  834): tsOffsetIs: Apps: 1295563729614; DSPS: 42551198; Offset : -3007597524
D/AndroidRuntime( 8081): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  834): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  834): Killing 5653:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  834): Skipping PackageSetting{33ed9af3 com.example.hello/10317} due to missing metadata
I/WindowState(  834): WIN DEATH: Window{14935b07 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  834): Focus left window: Window{14935b07 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  834): Window went away: Window{14935b07 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  834):   Force finishing activity ActivityRecord{a309999 u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  834): Display changed displayId=0
D/DSDPConnection( 1749): Display #0 changed.
W/ActivityManager(  834): Spurious death for ProcessRecord{596d401 5653:com.test.thalitest/u0a316}, curProc for 5653: null
I/ActivityManager(  834): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/[LGHome]EVENT( 1876): [Launcher.java:5203:onStart()]onStart
I/[LGHome]EVENT( 1876): [Launcher.java:776:onResume()]onResume
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/art     ( 1937): Explicit concurrent mark sweep GC freed 21826(1361KB) AllocSpace objects, 4(95KB) LOS objects, 40% free, 11MB/19MB, paused 1.212ms total 96.034ms
I/InputReader(  834): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1731): Ignoring removeGeofence because network location is disabled.
W/System.err( 3580): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3580): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3580): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3580): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3580): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3580): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3580): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3580): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3580): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3580): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3580): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3580): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  834): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8114 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1876): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/art     ( 5539): Explicit concurrent mark sweep GC freed 7686(399KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/17MB, paused 832us total 147.571ms
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1876): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1876): [Launcher.java:929:onResume()]onResume end
I/Activity( 1876): Activity.onPostResume() called 
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1876): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1876): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourcesManager( 1369): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1369): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/SystemUI[Framework](  834): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
W/PhoneWindowManagerEx(  834): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  834): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  834): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  834): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@25baff,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  834): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  834): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  834): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  834): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  834): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  834): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@25baff,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  834): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  834): Focus entered window: Window{2e3f6b72 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1369): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/art     (  834): Explicit concurrent mark sweep GC freed 44078(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/34MB, paused 8.489ms total 209.431ms
W/ResourcesManager( 1369): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/art     (  834): WaitForGcToComplete blocked for 131.857ms for cause Explicit
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
W/ResourcesManager( 8114): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8114): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
W/ResourcesManager( 8114): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
I/PhoneWindow( 1876): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  834): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/ResourcesManager( 1369): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1369): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/InputMethodManagerService(  834): Got RemoteException sending setActive(false) notification to pid 5653 uid 10316
W/ResourcesManager( 1369): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
D/KeyguardModel( 1369): handleShortcutListChanged...
D/KeyguardModel( 1369): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1369): createShortcutInfo...
D/administrator(  834): Handling package changes for user 0
D/KeyguardModel( 1369): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1369): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1369): createShortcutInfo...
W/ResourceType( 1369): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1369): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1369): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1369): createShortcutInfo...
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
D/KeyguardModel( 1369): handleShortcutListChanged...
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  834): Timeline: Activity_windows_visible id: ActivityRecord{106e7308 u0 com.lge.launcher2/.Launcher t221} time:1296456
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/LGEmail ( 8114): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 8114): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
I/NotificationService(  834): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  834): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  834): Receieved: android.intent.action.PACKAGE_REMOVED
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
D/PhoneStatusBar( 1369): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
D/TaskPersister(  834): removeObsoleteFile: deleting file=222_task.xml
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/art     (  834): Explicit concurrent mark sweep GC freed 5691(333KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.993ms total 344.244ms
I/PackageChangeReceiver( 8114): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/AndroidRuntime( 8081): Shutting down VM
D/AppUp4:PreloadHelper( 7543): added Exclude : com.test.thalitest
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  834): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8143 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
I/ActivityManager(  834): Killing 7565:com.android.gallery3d/u0a23 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  834): failed to open /acct/uid_10023/pid_7565/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1876): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
E/b       ( 1588): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
W/IInputConnectionWrapper( 1876): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline( 1876): Timeline: Activity_idle id: android.os.BinderProxy@1279cf3e time:1297130
W/ResourcesManager(  834): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     ( 1876): Explicit concurrent mark sweep GC freed 27203(1490KB) AllocSpace objects, 18(2MB) LOS objects, 39% free, 15MB/25MB, paused 1.578ms total 65.305ms
W/ResourcesManager( 8143): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
