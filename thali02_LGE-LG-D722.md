#### Test 58380500055030c_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
--------- beginning of main
W/ContextImpl( 5410): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5410): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5410): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  862): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5458 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  862): Killing 5238:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  862): failed to open /acct/uid_10014/pid_5238/cgroup.procs: No such file or directory
I/art     ( 5410): CheckpointMarkThreadRoots callback created = 0xaaf2a220
W/ResourcesManager( 5458): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 5410): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 5410): CheckpointMarkThreadRoots callback created = 0xb050ea50
W/System  ( 5410): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5410): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  862): Killing 5262:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  862): failed to open /acct/uid_10021/pid_5262/cgroup.procs: No such file or directory
D/AndroidRuntime( 5475): 
D/AndroidRuntime( 5475): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5475): CheckJNI is OFF
I/ActivityManager(  862): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5490 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 157 ms] updated apps [took 157 ms] 
D/AndroidRuntime( 5475): Calling main entry com.android.commands.am.Am
I/ActivityManager(  862): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  862): setTaskToReturnTo : TaskRecord{1164e9d1 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  862): setTaskToReturnTo : TaskRecord{1164e9d1 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  862): AppWindowTokenEx init.. 
D/ContextHelper(  862): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  862): Focus left window: Window{26df2e93 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5475): Shutting down VM
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  862): check instance of lgWin Window{2b588fd3 u0 Starting com.test.thalitest}
I/ActivityManager(  862): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5526 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1941): Closing mic
I/MicrophoneInputStream( 1941): mic_close com.google.android.apps.gsa.speech.audio.u@c1448c8
V/AudioRecord( 1941): stop()
D/AudioRecord( 1941): AudioRecord->stop()
V/AudioFlinger(  276): RecordHandle::stop()
V/AudioFlinger(  276): RecordThread::stop
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
D/Finsky  ( 5490): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/WindowStateAnimator(  862): Starting window displayed
I/SystemUI[Framework](  862): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
V/AudioFlinger(  276): Record stopped OK
V/AudioPolicyManager(  276): stopInput() input 17
V/AudioPolicyService(  276): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  276): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing release audio patch
W/PhoneWindowManagerEx(  862): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  862): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  862): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  862): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@ffc345c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  862): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioFlinger::PatchPanel(  276): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  276): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  276): ThreadBase::setParameters() routing=0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb42a4000
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/audio_hw_primary(  276): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
D/BarTransitions( 1374): draw background and invalidate : color = b000000
D/BarTransitions( 1374): draw background and invalidate : color = e0d0d0d
V/audio_hw_primary(  276): stop_input_stream: enter: usecase(7: audio-record)
,V/audio_hw_primary(  276): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  276): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  276): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  276): disable_audio_route: exit
E/audio_hw_primary(  276): disable_snd_device: enter 144
D/hardware_info(  276): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  276): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  276): stop_input_stream: exit: status(0)
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioFlinger(  276): RecordThread: loop stopping
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioPolicyManager(  276): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  276): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  276): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  276): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioPolicyService(  276): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  276): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  276): setParameters(): io 17, keyvalue hotword_active=0, calling pid 276
V/AudioFlinger(  276): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  276): RecordThread: loop starting
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  276): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  276): in_set_parameters: exit: status(0)
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb42a4000
V/AudioFlinger(  276): RecordThread: loop stopping
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioFlinger(  276): releasing 16 from 1941 for -1
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
V/AudioFlinger(  276): RecordHandle::stop()
V/AudioFlinger(  276): RecordThread::stop
V/AudioPolicyManager(  276): releaseInput() 17
V/AudioPolicyManager(  276): closeInput(17)
V/AudioFlinger(  276): closeInput() 17
V/AudioSystem(  276): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): ThreadBase::exit
V/AudioSystem( 1753): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2063): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): RecordThread: loop starting
V/AudioSystem(  862): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3226): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2764): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1941): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): RecordThread 0xb42a4000 exiting
D/audio_hw_primary(  276): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  276): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioPolicyService(  276): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  276): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  276): releaseInput() exit
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioFlinger(  276): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  276): AudioCommandThread() processing update audio port list
V/AudioFlinger(  276): removeClient_l() pid 1941, calling pid 276
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1941): Stopping hotword detection.
I/HotwordRecognitionRnr( 1941): Hotword detection finished
D/ContextHelper( 5526): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5526): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5526): Time to load native libraries: 2 ms (timestamps 1888-1890)
I/LibraryLoader( 5526): Expected native library version number "",actual native library version number ""
D/Finsky  ( 5490): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
V/WebViewChromiumFactoryProvider( 5526): Binding Chromium to main looper Looper (main, tid 1) {30183a30}
I/LibraryLoader( 5526): Expected native library version number "",actual native library version number ""
I/chromium( 5526): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5526): Initializing chromium process, singleProcess=true
W/art     ( 5526): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5526): ApplicationContext is null in ApplicationStatus
W/Settings( 5490): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5490): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5490): com.android.vending: cancel(-1050172287) by com.android.vending
W/chromium( 5526): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5526): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5526): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5526): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5526): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5526): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5526): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5526): Remote Branch: 
I/Adreno-EGL( 5526): Local Patches: 
I/Adreno-EGL( 5526): Reconstruct Branch: 
I/NotificationManager( 5490): com.android.vending: cancel(1003285959) by com.android.vending
V/DownloadManager( 3208): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@49674c1 on behalf of 5490
D/Finsky  ( 5490): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5490): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 5490): Skipping gmscore version check
V/AudioPolicyService(  276): registerClient() client 0xb4143060, uid 10316
D/BluetoothManagerService(  862): Message: 20
D/BluetoothManagerService(  862): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@24555828:true
D/BluetoothAdapterService(167692636)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@32340192
I/ActivityManager(  862): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5584 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/Finsky  ( 5490): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 5490): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5490): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  481): init target 500000
,W/ResourcesManager( 5584): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5584): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/MainApplication( 5154): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  862): battery changed pluggedType: 2
D/charger_monitor(  481): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
W/MainApplication( 5154): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  862): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/MultiDex( 5584): VM with version 2.1.0 has multidex support
I/MultiDex( 5584): install
I/MultiDex( 5584): VM has multidex support, MultiDex support library is disabled.
,W/art     ( 5526): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5526): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5526): CordovaWebView is running on device made by: LGE
,W/art     ( 5526): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5526): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5526): Activity.onPostResume() called 
,D/OpenGLRenderer( 5526): Render dirty regions requested: true
I/OpenGLRenderer( 5526): Initialized EGL, version 1.4
D/OpenGLRenderer( 5526): Enabling debug mode 0
,D/Atlas   ( 5526): Validating map...
,D/SplitWindow(  862): check instance of lgWin Window{2caea62b u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5526): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/JNIHelp ( 5584): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/InputDispatcher(  862): Focus entered window: Window{2caea62b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  862): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  862): Displayed com.test.thalitest/.MainActivity: +1s209ms
I/Timeline(  862): Timeline: Activity_windows_visible id: ActivityRecord{fdb6c36 u0 com.test.thalitest/.MainActivity t222} time:82682
,I/Timeline( 5526): Timeline: Activity_idle id: android.os.BinderProxy@275206bf time:82694
,W/ActivityThread( 5584): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5584): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21675408: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5584): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5584): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5584): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5584): Reading stored module config
,D/PackageBroadcastService( 5584): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/ChimeraCfgMgr( 5584): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5584): Loading module APK com.google.android.play.games
W/BindingManager( 5526): Cannot call determinedVisibility() - never saw a connection for the pid: 5526
W/art     ( 5584): Suspending all threads took: 6.256ms
,D/JsMessageQueue( 5526): Set native->JS mode to OnlineEventsBridgeMode
,D/NativeLibraryUtils( 5584): Install completed successfully. count=14 extracted=0
,I/art     ( 5584): CheckpointMarkThreadRoots callback created = 0xaaf4cd30
,I/art     ( 5584): CheckpointMarkThreadRoots callback created = 0xaaf4cd10
,D/ChimeraCfgMgr( 5584): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5584): Module APK com.google.android.play.games already loaded
I/art     ( 3961): Explicit concurrent mark sweep GC freed 8107(407KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 1.049ms total 64.749ms
I/PeopleDatabaseHelper( 5584): cleanUpNonGplusAccounts done.
,D/ChimeraCfgMgr( 5584): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/AsyncTaskServiceImpl( 5584): Submit a task: k
I/ActivityManager(  862): Killing 5292:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  862): failed to open /acct/uid_10009/pid_5292/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 5584): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5584): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 5584): Processing package: com.test.thalitest
,D/jxcore_app_log( 5526): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622977024
W/BaseAppContext( 5584): Using Auth Proxy for data requests.
,D/GassUtils( 5584): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5584): Found info for package com.test.thalitest in db.
,I/chromium( 5526): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Icing   ( 5584): Storage manager: low false usage 1.74MB avail 2.38GB capacity 4.06GB
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WearableService( 1734): callingUid 10006, callindPid: 1734
,E/MDM     ( 1734): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,E/BaseAppContext( 5584): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
D/LocationInitializer( 5584): Restart initialization of location
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/BaseAppContext( 5584): Using Auth Proxy for data requests.
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 5526): CheckpointMarkThreadRoots callback created = 0x9c1a4460
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
I/art     ( 5584): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5584): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5526): CheckpointMarkThreadRoots callback created = 0x9c1a4430
W/art     ( 5526): Suspending all threads took: 6.943ms
,I/art     ( 5526): Background partial concurrent mark sweep GC freed 8603(681KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 8.856ms total 65.108ms
I/ActivityManager(  862): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5669 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  862): Process com.android.contacts (pid 5348) has died
,W/BaseAppContext( 5584): Using Auth Proxy for data requests.
,W/BaseAppContext( 5584): Using Auth Proxy for data requests.
,W/BaseAppContext( 5584): Using Auth Proxy for data requests.
W/BaseAppContext( 5584): Using Auth Proxy for data requests.
W/BaseAppContext( 5584): Using Auth Proxy for data requests.
,W/IcingInternalCorpora( 5584): getNumBytesRead when not calculated.
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
,I/ActivityManager(  862): Process com.android.gallery3d (pid 5329) has died
,W/ActivityManager(  862): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     (  862): Explicit concurrent mark sweep GC freed 27781(1375KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.454ms total 192.418ms
,D/InitAlarmsService( 3797): Clearing and rescheduling alarms.
,I/ActivityManager(  862): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5698 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 5669): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5698): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/GAV2    ( 5669): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/CalendarProvider2( 5698): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3f0958d7
,W/ActivityManager(  862): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5669): Error finding the version of the Email provider.....
E/Gmail   ( 5669): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5669): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5669): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5669): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5669): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5669): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5669): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5669): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5669): We do not support migrating this version of the Email provider.
D/CalendarProvider2( 5698): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5698): Created com.android.providers.calendar.CalendarAlarmManager@30183a30(com.android.providers.calendar.CalendarProvider2@3f0958d7)
I/Gmail   ( 5669): getAccountsCursor
D/CalendarProvider2( 5698): Scheduling check of next Alarm
D/CalendarProvider2( 5698): SCHEDULE_ALARM_REMOVE
,I/Icing   ( 5584): updateResources: need to parse f{com.google.android.gms}
W/ActivityManager(  862): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  862): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5669): Observing account changes for notifications
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 5584): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5584): Module APK com.google.android.play.games already loaded
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
V/DownloadManager( 3208): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@19e8b466 on behalf of 5584
I/ActivityManager(  862): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5745 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/InstanceID/Rpc( 5584): Found 10006
,W/InstanceID/Rpc( 5584): Found 10006
,V/DownloadManager( 3208): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@1bf013a7 on behalf of 5584
V/DownloadManager( 3208): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@255f7054 on behalf of 5584
I/Gmail   ( 5669): notifyAccountChanged
,I/Gmail   ( 5669): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5669): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/PhoneMonitor( 5745): Register our PhoneStateListener
,I/Gmail   ( 5669): getAccountsCursor
,I/Gmail   ( 5669): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5669): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PhoneMonitor( 5745): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5745): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 5745): [parse] Load xml
,I/Icing   ( 5584): Internal init done: storage state 0
V/TelephonyAutoProfiling( 5745): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5745): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5745): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/art     ( 5584): Background sticky concurrent mark sweep GC freed 10424(732KB) AllocSpace objects, 5(80KB) LOS objects, 5% free, 13MB/14MB, paused 21.528ms total 85.399ms
,I/NotificationManager( 5584): com.google.android.gms: cancel(10436) by com.google.android.gms
I/art     ( 1734): Explicit concurrent mark sweep GC freed 26828(1742KB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 13MB/22MB, paused 2.548ms total 121.246ms
,I/art     ( 3961): Explicit concurrent mark sweep GC freed 3087(121KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.393ms total 57.202ms
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinService( 5584): Checkin interval check for package: unspecified last checkin: 1454970739734 min interval config: 0 actual interval: 7697
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5584): Post-init done
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 5584): Disabling old GoogleServicesFramework version
,I/ActivityManager(  862): Killing 3797:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  862): failed to open /acct/uid_10013/pid_3797/cgroup.procs: No such file or directory
,I/CheckinService( 5584): Checking schedule, now: 1454970747582 next: 1454970769683
I/CheckinService( 5584): active receiver: disabled
,W/art     ( 5526): Suspending all threads took: 17.683ms
,W/jxcore-log( 5526): Initializing JXcore engine
I/art     ( 5526): Background sticky concurrent mark sweep GC freed 5862(519KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 18.774ms total 42.905ms
W/jxcore-log( 5526): JXcore engine is ready
I/ActivityManager(  862): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5775 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 22.639ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 22.453ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 22.141ms
,W/ResourcesManager( 5775): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Gmail   ( 5669): getAccountsCursor
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CalendarProvider2( 5698): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5698): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  862): Killing 5312:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  862): failed to open /acct/uid_10011/pid_5312/cgroup.procs: No such file or directory
,W/Thread-656( 5652): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7569]" dev="sockfs" ino=7569 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-656( 5652): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-656( 5652): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8540]" dev="sockfs" ino=8540 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-656( 5652): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-656( 5652): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-656( 5652): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26255]" dev="sockfs" ino=26255 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5526): Starting JXcore engine
,I/ActivityManager(  862): Process com.google.android.apps.docs (pid 5410) has died
,W/jxcore-log( 5526): Platform android
W/jxcore-log( 5526): 
,W/jxcore-log( 5526): Process ARCH arm
W/jxcore-log( 5526): 
,I/Babel_SMS( 5775): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5775): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5775): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5775): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5775): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 5775): MmsConfig.loadFromResources
E/Babel_SMS( 5775): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5775): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5775): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5775): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5775): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5775): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5775): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5775): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5775): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5775): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5775): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5775): found sensor: LGE Significant Motion Detector Sensor, handle=47
,D/SensorManager( 5775): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5775): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5775): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5775): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5775): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5775): found sensor: Motion Accel, handle=46
W/Settings( 5775): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5775): startup - clean
I/art     ( 5775): CheckpointMarkThreadRoots callback created = 0xaaf39890
,I/art     ( 5775): CheckpointMarkThreadRoots callback created = 0xaaf39870
,I/Babel   ( 5775): deleted: false for 0
,V/AlarmManager(  862): RTC_WAKEUP set : Alarm{3a739dc0 type 0 when 1454970748457 com.google.android.googlequicksearchbox} when 1454970748457
,W/AudioCapabilities( 5775): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5775): Unsupported mime audio/adpcm
W/AudioCapabilities( 5775): Unsupported mime audio/g726
W/AudioCapabilities( 5775): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5775): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5775): Unsupported mime video/mjpg
W/VideoCapabilities( 5775): Unsupported mime video/theora
,I/jxcore-log( 5526): JXcore Cordova bridge is ready!
I/jxcore-log( 5526): 
W/jxcore-log( 5526): JXcore engine is started
W/AudioCapabilities( 5775): Unsupported mime audio/evrc
W/AudioCapabilities( 5775): Unsupported mime audio/qcelp
W/VideoCapabilities( 5775): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5775): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5775): Unsupported mime audio/qcelp
W/AudioCapabilities( 5775): Unsupported mime audio/evrc
W/VideoCapabilities( 5775): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5775): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5775): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5775): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5775): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5775): Unrecognized profile 2130706433 for video/avc
I/Icing   ( 5584): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/vclib   ( 5775): onServiceConnected
W/Babel   ( 5775): Attempted to change video mute state without an active call.
I/NotificationManager( 5775): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5775): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5775): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/jxcore-log( 5526): Toggling radios to true
I/jxcore-log( 5526): 
,D/BluetoothAdapter( 5526): enable(): BT is already enabled..!
V/JNIHelp ( 5775): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  862): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5814 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/WifiServiceImplEx(  862): setWifiEnabled: true pid=5526, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,I/AudioManager( 5076): getMode name:com.lge.qremote
D/WifiService(  862): setWifiEnabled: true pid=5526, uid=10316
D/WifiServiceImplEx(  862): disconnect pid=5526, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  862): reconnect pid=5526, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5526): Radios toggled
I/jxcore-log( 5526): 
I/jxcore-log( 5526): My device name is: LGE-LG-D722
I/jxcore-log( 5526): 
I/AudioManager( 5076): getMode name:com.lge.qremote
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2770): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
E/WifiStateMachine(  862): WifiStateMachine: Leaving Connected state
,E/WifiConfigStore(  862): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/wpa_supplicant( 2770): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1806): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/AudioManager( 5076): getMode name:com.lge.qremote
,D/LGWifiP2pService(  862): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  862): P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  862): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/Icing   ( 5584): Loaded CLD2 Version V2.0 - 20141016
D/CommandListener(  272): Clearing all IP addresses on wlan0
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 7
I/art     ( 5584): Background sticky concurrent mark sweep GC freed 6223(362KB) AllocSpace objects, 0(0B) LOS objects, 3% free, 13MB/14MB, paused 4.174ms total 104.510ms
,I/art     ( 5584): WaitForGcToComplete blocked for 31.829ms for cause HeapTrim
V/NativeCrypto( 1734): Read error: ssl=0xaaee1600: I/O error during system call, Connection timed out
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 7
,W/System  ( 5775): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5775): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  862): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/WifiHS20(  862): hidePasspointNotification off =false
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Icing   ( 5584): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
D/ConnectivityService(  862): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  862): Start Disconnecting Watchdog 1
I/wpa_supplicant( 2770): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiHS20(  862): hidePasspointNotification off =false
V/NativeCrypto( 1734): SSL shutdown failed: ssl=0xaaee1600: I/O error during system call, Broken pipe
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  862): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  862): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:29.091 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:29.1 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  862): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,I/AudioManager( 5076): getMode name:com.lge.qremote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): ValidatedState{ when=-19ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): DefaultState{ when=-24ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): Forcing reevaluation
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/AudioManager( 5076): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5814): Quickset Services start...
I/UEI.SmartControl( 5814): Manufacture = LGE
D/UEI.SmartControl( 5814): File observer start...
E/UEI.SmartControl( 5814): IR Port is disabled: false
D/UEI.SmartControl( 5814): Starting file observer...
D/UEI.SmartControl( 5814): Extracting JNI libs...
D/UEI.SmartControl( 5814): --- this system supports 32-bit or 64-bit only
,D/CommandListener(  272): Clearing all IP addresses on wlan0
D/ConnectivityService(  862): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  862): disableDataServiceNotify
D/WifiHS20(  862): hidePasspointNotification off =false
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:29.207 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiNetworkAgent(  862): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/DSQN    (  862): stop dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/art     (  862): Explicit concurrent mark sweep GC freed 21014(985KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.992ms total 271.480ms
,D/WifiHS20(  862): hidePasspointNotification off =false
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:29.233 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,E/MDM     ( 1734): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:29.244 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/DhcpStateMachine(  862): StoppedState
D/DhcpStateMachine(  862): StoppedState{ when=-148ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  862): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/WifiServerServiceExt(  862): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  862): setSupplicantStateDISCONNECTED
D/ConnectivityService(  862):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  862):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiServerServiceExt(  862): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  862): setSupplicantStateSCANNING
D/ConnectivityService(  862): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524292
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): Disconnected - quitting
D/Nat464Xlat(  862): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/LocationInitializer( 5584): Restart initialization of location
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/CSLegacyTypeTracker(  862): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  862): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  862): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  862): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/Tethering(  862): MasterInitialState.processMessage what=3
D/ConnectivityService(  862): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1842): |CORE| No family connected
V/NetworkPolicy(  862): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  862): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  862): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  862): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  862): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  862):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1753): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/Tethering(  862): MasterInitialState.processMessage what=3
D/NetworkManagementService(  862): Removing idletimer
W/QCNEJ   ( 1842): |CORE| No family connected
I/QCNEJ   ( 1842): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
V/NetworkPolicy(  862): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings(  862): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  862): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/QCNEJ   ( 1842): |CORE| sendDefaultNwMsg: default = -1
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
I/AudioManager( 5076): getMode name:com.lge.qremote
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/AudioManager( 5076): getMode name:com.lge.qremote
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NotificationManager( 5775): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  862): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5844 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/UEI.SmartControl( 5814): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5814): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5814): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5814): --- Selecting new region: 2
I/UEI.SmartControl( 5814): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5814): Platform has CIR...
D/UEI.SmartControl( 5814): NO CIR support, need to check package...
I/UEI.SmartControl( 5814): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5814): QS Service created
,E/UEI.SmartControl( 5814): QS start get config
I/AppUp4:AppBoxCP( 5844): onCreate
,W/AppUp4:DB( 5844):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5844):  setFingerPrint start
I/AppUp4:DB( 5844):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5844):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5844):  SDK version = 0
I/AppUp4:DB( 5844):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5844): AppBoxApplication onCreate()
D/UEI.SmartControl( 5814): Loading JNI Libs...
D/UEI.SmartControl( 5814):  configuring local db...
I/AppUp4:CustModeStarterReceiver( 5844): onReceive
I/AppUp4:CustModeStarterReceiver( 5844): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5844): Context : android.app.ReceiverRestrictedContext@36d8dbe2
D/AppUp4:CustFacade( 5844): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5844): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5844): begin check event
I/AppUp4:CustModeStarterReceiver( 5844): Event For Nothing, skip.
I/ActivityManager(  862): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5863 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5863): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5863): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5863): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  862): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/administrator(  862): Handling package changes for user 0
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/UEI.SmartControl( 5814):  ---- Has DB8: true
,D/UEI.SmartControl( 5814): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5814): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5814): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5814): IRRCDataComm has AudioManager!!!!.
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/irrc_jni( 5814): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5814): IrrcClient ++ 
,D/irrcClient( 5814): getIrrcService ++ 
D/irrcClient( 5814): getIrrcService -- 
D/irrcClient( 5814): IrrcClient -- 
W/irrc_jni( 5814): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5814): Services init done
,I/UEI.SmartControl( 5814): Device manager: loading config....
D/UEI.SmartControl( 5814): Config is loaded...
,D/UEI.SmartControl( 5814):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5814): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5814): QS Service init finished
D/UEI.SmartControl( 5814): QS Service version name: 0.1.73
D/UEI.SmartControl( 5814): QS Service version code: 1073
D/UEI.SmartControl( 5814): Service requested: Control
D/UEI.SmartControl( 5814): Internal service binding...
D/UEI.SmartControl( 5814): -----IControl: 11
,D/UEI.SmartControl( 5814): Caller: com.lge.qremote
D/UEI.SmartControl( 5814): ------------ IControl registerCallback...
I/UEI.SmartControl( 5814): Registering callback...
D/UEI.SmartControl( 5814): -----IControl: 19
D/UEI.SmartControl( 5814): Caller: com.lge.qremote
I/UEI.SmartControl( 5814): Registering Services Ready callback...
I/UEI.SmartControl( 5814): Notify client services are ready...
D/UEI.SmartControl( 5814): -----IControl: 8
,D/UEI.SmartControl( 5814): Caller: com.lge.qremote
I/NotificationService(  862): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  862): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  862): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  862): Process com.lge.bnr (pid 5154) has died
W/ResourcesManager(  862): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/BackupManagerService(  862): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/wpa_supplicant( 2770): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/ActivityManager(  862): Killing 5372:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/AppConfig( 5863): Total System Memory = 906309632
I/GalleryUtils( 5863): Application Heap = 96 MB
,I/AppConfig( 5863): App Tier : NOT_DEF
D/SystemHelper( 5863): region [EU], country [EU], operator [OPEN], sub-operator []
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2770): wlan0: Associated with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2770): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2770): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 4
W/ResourceType(  862): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  862): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5885 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  862): Killing 5390:com.lge.eula/1000 (adj 15): empty #11
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
,W/libprocessgroup(  862): failed to open /acct/uid_1000/pid_5390/cgroup.procs: No such file or directory
W/libprocessgroup(  862): failed to open /acct/uid_10069/pid_5372/cgroup.procs: No such file or directory
,D/LocSvc_java(  862): onReceive
,W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:30.467 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:30.469 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/ResourcesManager( 5885): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/ResourcesManager( 5885): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
W/ResourcesManager( 5885): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:30.477 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/ResourcesManager( 5885): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5885): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/WifiServiceExtension(  862): setVHTCapabilityType  : false
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:30.493 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
V/BackupManagerService(  862): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
V/BackupManagerService(  862): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@73d00d1
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/WifiServerServiceExt(  862): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  862): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  862): setSecurityType  : 2
I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:30.552 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:30.556 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/LocationProviderProxy(  862): applying state to connected service
D/ConnectivityService(  862): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{Interfac,eName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  862): Got NetworkAgent Messenger
D/ConnectivityService(  862): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  862): NetworkAgent connected
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
E/WifiConfigStore(  862): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  862): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  272): Setting iface cfg
E/WifiStateMachine(  862): Start Dhcp Watchdog 2
D/DhcpStateMachine(  862): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  862): WaitBeforeStartState
D/WifiServerServiceExt(  862): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  862): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  862): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  862): setSupplicantStateASSOCIATED
D/WifiServerServiceExt(  862): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  862): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  862): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  862): setSupplicantStateGROUP_HANDSHAKE
,D/ConnectivityService(  862): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  862): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  862): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  862): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@76d2083 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  862): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@76d2083 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  862): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  862): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  862): DHCP Start wake lock is acquired.
D/CommandListener(  272): Setting iface cfg
I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  272): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  862): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  862): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  862): setSupplicantStateCOMPLETED
,D/ConnectivityService(  862): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/SystemConfig( 5885): BUILD Country: EU
I/SystemConfig( 5885): BUILD Operator: OPEN
D/LGWifiP2pService(  862): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  862): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  862): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  862): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  862): ignoring duplicate network state non-change
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:30.726 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  862): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  862): Adding iface wlan0 to network 101
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:30.749 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/ConnectivityService(  862): Unexpected mtu value: 0, wlan0
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  862): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  862): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  272): netlink response contains error (File exists)
D/ConnectivityService(  862): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/ConnectivityService(  862): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  862): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  862): Setting Dns servers for network 101 to [/192.168.1.1]
D/WifiHS20(  862): [PASSPOINT] passpointNotification: hs20AP list is checked
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/Nat464Xlat(  862): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  862): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  862): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  862): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  862):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  862):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  862):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  862):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  862):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  862): currentScore = 0, newScore = 20
D/ConnectivityService(  862):    accepting network in place of null
D/ConnectivityService(  862): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.S,ettings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:30.763 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
E/ConnectivityService(  862): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  862): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  862): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1753): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiHS20(  862): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): [LWD] Start DNSResolver start to wait
E/WifiStateMachine(  862): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:30.777 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  862): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  862): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  862): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  862): validation of new default Network = false
D/ConnectivityService(  862): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  862): enableDataServiceNotify 
D/DSQN    (  862): start dsqn bin
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Tethering(  862): MasterInitialState.processMessage what=3
D/WIFI    (  862): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  862):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): [LWD] wait 500ms before dns check
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=0 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/QCNEJ   ( 1842): |CORE| No family connected
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1842): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1842): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
V/NetworkPolicy(  862): [LG_RESTRICTED] checkMobilePolicy_type()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  862): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  862):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  862):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  862): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/CheckinService( 5584): Checkin interval check for package: unspecified last checkin: 1454970739734 min interval config: 0 actual interval: 11080
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/DSQN    ( 5907): DSQN samuel.seo ver 141203
E/DSQN    ( 5907): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5907): created command queue thread
I/DSQN    ( 5907): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5907): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/CheckinService( 5584): Checking schedule, now: 1454970750825 next: 1454970769683
I/CheckinService( 5584): active receiver: disabled
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/DhcpStateMachine(  862): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  862): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  862): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/ActivityManager(  862): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5914 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  862): Killing 5458:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/dhcpcd  ( 5913): version 5.5.6 starting
E/dhcpcd  ( 5913): get_duid: Read-only file system
I/dhcpcd  ( 5913): wlan0: rebinding lease of 192.168.1.134
,W/libprocessgroup(  862): failed to open /acct/uid_10086/pid_5458/cgroup.procs: No such file or directory
I/SystemConfig( 5885): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5885): existFile = false
I/SystemConfig( 5885): canReadFile = false
I/SystemConfig( 5885): systemFeature RCS result false
D/SystemConfig( 5885): refreshRcsSupport() :false
I/LockScreenSettings( 5914): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5914): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 5914): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5914): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5914): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5914): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/dhcpcd  ( 5913): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/ActivityManager(  862): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5937 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  862): Killing 5490:com.android.vending/u0a36 (adj 15): empty #11
I/dhcpcd  ( 5913): wlan0: leased 192.168.1.134 for 86400 seconds
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): [LWD] DNSResolver start dns
,D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
W/libprocessgroup(  862): failed to open /acct/uid_10036/pid_5490/cgroup.procs: No such file or directory
,W/ResourcesManager( 5937): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out(  862): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5907): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5907): restart monitoring
,D/LGDataListener(  272): argv[0]=dsqncommand
D/LGDataListener(  272): argv[1]=wlan0
D/LGDataListener(  272): argv[2]=1
D/LGDataListener(  272): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5907): dsqn report finish
D/DSQN    (  862): DSQM DsqnNotification wlan0  1
D/DSQN    (  862): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 08 Feb 2016 22:32:31 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454970751403], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454970751380]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  862): Validated
D/ConnectivityService(  862): Validated NetworkAgentInfo [WIFI () - 101]
D/WifiDataContinuityService(  862): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  862): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  862):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  862):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  862):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  862): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  862): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  862):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  862):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  862): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  862): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  862): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/WifiServerServiceExt(  862): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  862): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  862):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1753): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1753):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  862): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  862): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  862): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  862): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  862): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  862): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  862): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  862): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  862): RunningState
I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  862): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5993 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GAV2    ( 5669): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  862): Killing 5669:com.google.android.gm/u0a53 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  862): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 139 ms] updated apps [took 139 ms] 
V/AlarmManager(  862): ELAPSED_WAKEUP set : Alarm{58afe9 type 2 when 89988 com.android.providers.calendar} when 89988
W/libprocessgroup(  862): failed to open /acct/uid_10053/pid_5669/cgroup.procs: No such file or directory
,I/GAv4-SVC( 5584): Google Analytics 8.4.89 is starting up.
,V/AlarmManager(  862): ELAPSED_WAKEUP set : Alarm{2292146e type 2 when 90187 com.google.android.gms} when 90187
,I/ActivityManager(  862): Process com.android.providers.calendar (pid 5698) has died
,D/ConnectivityService(  862): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  862): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  862): onReceive
D/LocSvc_java(  862): got connectivity action
D/LocSvc_java(  862): broadcast - no network connections
D/LocSvc_java(  862): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  862): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  862): onReceive
D/LocSvc_java(  862): got connectivity action
D/LocSvc_java(  862): broadcast - no network connections
D/LocSvc_java(  862): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  862): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  862): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  862): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  862): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  862): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  862): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  862): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  862): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  862): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  862): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  862): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 5993): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Netd    (  272): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  862): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  862): identical MTU - not setting
D/Nat464Xlat(  862): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  862): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  862):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  862):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/ActivityManager(  862): Process com.google.android.setupwizard (pid 5745) has died
D/ConnectivityService(  862): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  862): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  862): enableDataServiceNotify 
D/DSQN    (  862): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524295
I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:32.54 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  862): dsqn is running restart
,I/DSQN    ( 6034): DSQN samuel.seo ver 141203
E/DSQN    ( 6034): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6034): created command queue thread
I/DSQN    ( 6034): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6034): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/Finsky  ( 5993): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 5993): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5993): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5993): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 5993): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5993): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5993): Skipping gmscore version check
V/DownloadManager( 3208): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@32d49bfd on behalf of 5993
D/PackageBroadcastService( 5584): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5584): Null package name or gms related package.  Ignoreing.
I/AudioManager( 5076): getMode name:com.lge.qremote
D/Finsky  ( 5993): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/Icing   ( 5584): updateResources: need to parse f{com.google.android.gms}
D/Finsky  ( 5993): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  862): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6054 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  862): Process com.android.gallery3d (pid 5863) has died
,I/ActivityManager(  862): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6080 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,E/UpdateRequestReceiver( 6080): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6080): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6080): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6080): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/GservicesUpdateTask( 1941): Updating Gservices keys
I/art     (  862): Explicit concurrent mark sweep GC freed 80415(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.808ms total 210.758ms
,I/CheckinService( 5584): Checkin interval check for package: unspecified last checkin: 1454970739734 min interval config: 0 actual interval: 13749
I/CheckinService( 5584): Checking schedule, now: 1454970753522 next: 1454970769683
I/CheckinService( 5584): active receiver: disabled
,I/SystemUpdateService( 5584): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 5584): onCreate
,D/SystemUpdateService( 5584): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 5584): cancelUpdate (empty URL)
,I/SystemUpdateService( 5584): active receiver: disabled
I/NotificationManager( 5584): com.google.android.gms: cancel(2130838165) by com.google.android.gms
I/NotificationManager( 5584): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-08 23:32:33.624 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     ( 3961): Explicit concurrent mark sweep GC freed 3980(171KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.030ms total 33.678ms
,V/WifiInternetCheck(  862): Single check msg out of sync, ignoring.
,D/ConnectivityService(  862): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  862): onReceive
D/LocSvc_java(  862): got connectivity action
D/LocSvc_java(  862): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  862): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  862): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  862): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  862): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  862): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  862): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 3961): Explicit concurrent mark sweep GC freed 2777(108KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.240ms total 27.524ms
,I/Icing   ( 5584): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/art     ( 5584): Explicit concurrent mark sweep GC freed 14075(858KB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 13MB/22MB, paused 10.190ms total 86.383ms
,D/SystemUpdateService( 5584): onDestroy
,I/Icing   ( 5584): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,E/DynamiteModule( 5584): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 5584): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 5584): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 5584): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 5584): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 5584): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 5584): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 5584): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 5584): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 5584): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 5584): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 5584): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 5584): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 5584): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 5584): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 5584): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 5584): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 5584): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 5584): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 5584): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 5584): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 5584): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 5584): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 5584): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 5584): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 5584): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 5584): 		... 17 more
E/DynamiteModule( 5584): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 5584): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 5584): Selected local version of com.google.android.gms.flags
,D/SystemEventReceiver( 5584): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 5584): Updating ocr activity enabled=false
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  862): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 5584): Updating downloaded model state (gservices changed)
,I/ActivityManager(  862): Killing 5775:com.google.android.talk/u0a61 (adj 15): empty #11
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 17686(1289KB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 13MB/22MB, paused 1.338ms total 77.791ms
,W/libprocessgroup(  862): failed to open /acct/uid_10061/pid_5775/cgroup.procs: No such file or directory
,I/art     ( 3961): Explicit concurrent mark sweep GC freed 2517(99KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 720us total 32.025ms
,I/NotificationManager(  862): android: cancelAsUser(-591465577) by android
D/GCM     ( 1734): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  862): Killing 5844:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
,W/libprocessgroup(  862): failed to open /acct/uid_10011/pid_5844/cgroup.procs: No such file or directory
,I/DSQN    ( 6034): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6034): restart monitoring
I/DSQN    ( 6034): dsqn report finish
D/LGDataListener(  272): argv[0]=dsqncommand
D/LGDataListener(  272): argv[1]=wlan0
D/LGDataListener(  272): argv[2]=1
D/LGDataListener(  272): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  862): DSQM DsqnNotification wlan0  1
D/DSQN    (  862): start to monitor internet connection
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out(  862): propertyValue:false
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  862): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  862): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  272): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out(  862): propertyValue:false
V/WifiInternetCheck(  862): isHttpConnectionAvailable - We got a valid response : 204
,D/UEI.SmartControl( 5814): Internal timer expired: 1
I/GCoreUlr( 1734): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1734): DispatchingService.onCreate()
I/ActivityManager(  862): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6153 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/AlarmManager(  862): RTC_WAKEUP set : Alarm{22fb3acf type 0 when 1454970755130 com.android.vending} when 1454970755130
,D/Finsky  ( 5993): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  862): android: cancelAsUser(2) by android
,I/GCoreUlr( 1734): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
E/ctxmgr  ( 1734): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,D/PhoneMonitor( 6153): Register our PhoneStateListener
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,V/SetupWizard( 6153): Connected to Gservices successfully
,D/PhoneMonitor( 6153): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6153): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6153): [parse] Load xml
,V/TelephonyAutoProfiling( 6153): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6153): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
W/ctxmgr  ( 1734): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
E/ctxmgr  ( 1734): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
I/GCoreUlr( 1734): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1734): Unbound from all location providers
I/GCoreUlr( 1734): Place inference reporting - stopped
,D/PhoneMonitor( 6153): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/libc-netbsd( 5993): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5993): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5993): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5993): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  272): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
I/GCoreUlr( 1734): DispatchingService.onDestroy()
I/GCoreUlr( 1734): Stopping handler for UlrDispSvcFast
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/GCoreUlr( 1734): Unbound from all location providers
I/GCoreUlr( 1734): Place inference reporting - stopped
D/WearableService( 1734): callingUid 10006, callindPid: 1734
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
E/MDM     ( 1734): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/System.out( 5993): propertyValue:false
D/libc-netbsd( 5993): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5993): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5584): Restart initialization of location
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  862): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6189 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 346us total 24.904ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.754ms
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 18988(1148KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 13MB/23MB, paused 1.894ms total 88.297ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 20.866ms
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
,D/libc-netbsd( 5993): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5993): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ActivityManager(  862): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  862): android: cancelAsUser(2) by android
I/Gmail   ( 6189): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 5993): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5993): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5993): untagSocket(41) failed with errno -22
W/GAV2    ( 6189): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/Finsky  ( 5993): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/ActivityManager(  862): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6189): Error finding the version of the Email provider.....
E/Gmail   ( 6189): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6189): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6189): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6189): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6189): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6189): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6189): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6189): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6189): getAccountsCursor
I/ActivityManager(  862): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6231 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ActivityManager(  862): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  862): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/NotificationManager(  862): android: cancelAsUser(2) by android
,I/Gmail   ( 6189): Observing account changes for notifications
I/art     (  862): Explicit concurrent mark sweep GC freed 32965(1681KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.348ms total 153.224ms
,W/ResourcesManager( 6231): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6231): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MultiDex( 6231): VM with version 2.1.0 has multidex support
I/MultiDex( 6231): install
I/MultiDex( 6231): VM has multidex support, MultiDex support library is disabled.
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/JNIHelp ( 6231): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 5993): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5993): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5993): untagSocket(41) failed with errno -22
I/ActivityManager(  862): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6257 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 6189): notifyAccountChanged
,I/Gmail   ( 6189): getAccountsCursor
I/Gmail   ( 6189): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 3961): Explicit concurrent mark sweep GC freed 3022(120KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 416us total 28.943ms
,W/ActivityThread( 6231): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6231): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ebbb0f2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6231): Installed default security provider GmsCore_OpenSSL
I/Gmail   ( 6189): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/NotificationManager( 6231): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6231): com.google.android.gms: cancel(39789) by com.google.android.gms
I/Gmail   ( 6189): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6189): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/ChimeraCfgMgr( 6231): Reading stored module config
W/ResourcesManager( 6257): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 6231): Loading module com.google.android.gms.car from APK com.google.android.gms
D/CalendarApplication( 6257): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6257): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6257): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3430dcad, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@36d8dbe2, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2020ab73, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@30183a30, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@d2b96a9, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@132cd42e, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1c508bcf, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@9fec95c, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3bfdf465, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@16b6053a, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@25f415eb, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@265d1f48, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2ede71e1, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@306f3b06, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2ffc25c7, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@c8e7f4, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@26ef4b1d, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@32340192, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@18b5763, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@16868f60, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1b3a7c19, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3e0ca4de, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@275206bf, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@32b5418c, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@f6dc0d5, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3c3a30ea, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1eaa4fdb, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@113aea78, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1a569551, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@260271b6, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@16740eb7, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@4703624, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@181e358d, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@313bf342, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@21b0df53, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@98c9090, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@4459d89, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@289a018e, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@37e01daf, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@37d225bc, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@37618945, lg_preferences_rece,nt_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3cb8a89
,D/GeneralPreferenceUtils( 6257): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6257): [init]
,I/Config  ( 6257): LGCalendar ver.4.40.17
I/Config  ( 6257): start check model
I/Config  ( 6257): start check native_ca
D/CAR.SERVICE( 6231): Connecting to CarCallService...
I/Config  ( 6257): Config Operator=OPEN, Country=EU
D/Config  ( 6257): [setDefaultValuesToPref]
D/Config  ( 6257): [parseProfiles]
I/Gmail   ( 6189): getAccountsCursor
,D/ProfilesParser( 6257): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6257): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6257): [updateProfiletoCountryInfo]
D/GeneralPreference( 6257): [checkAndMigrateOldPreference]
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AlertReceiver( 6257): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/sensors_hal_Time(  862): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  862): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  862): tsOffsetIs: Apps: 95187606792; DSPS: 3217092; Offset : -2994730251
,I/InitNotificationRingtoneService( 6257): Start InitializeAlertRingtoneService.onHandleIntent
I/art     ( 6231): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6231): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/AlertUtils( 6257): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
D/NativeLibraryUtils( 6231): Install completed successfully. count=14 extracted=0
I/AlertUtils( 6257): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/art     ( 5993): WaitForGcToComplete blocked for 111.786ms for cause HomogeneousSpaceCompact
I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
D/CAR.SERVICE( 6231): com.google.android.projection.gearhead isn't installed.
I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,D/CAR.TEL.Service( 6231): Creating a new CarCallService.
I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
D/CAR.TEL.PhoneAdapter( 6231): Creating a new PhoneAdapter instance
I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
W/ActivityManager(  862): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6231): setListener: com.google.android.gms.car.dn@2d2c9469
I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
W/ActivityManager(  862): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6231): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6231): Starting CarCallService with initial phone null
I/AlertUtils( 6257): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6257): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6257): set default noti to content://media/internal/audio/media/38
I/NotificationManager( 6231): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/InitNotificationRingtoneService( 6257): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6257): onHandleIntent
D/HolidayDataLoader( 6257): readJsonAsset : holiday.json
,D/AlertService( 6257): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6257): [updateWidgets] 
,D/MonthWidgetProvider( 6257): [onReceive]
D/CalendarWidgetProvider( 6257): [onReceive]
D/CalendarWidgetProvider( 6257): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CAR.SERVICE( 6231): Package validated; name: com.android.vending
D/CalendarTypeController( 6257): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6257): [onReceive]
D/CalendarWidgetProvider( 6257): [onReceive]
,D/CalendarWidgetProvider( 6257): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6257): [onCreate] mContext.getPackageName() = com.android.calendar
,I/NotificationManager( 5993): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5993): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,E/HolidayIntentService( 6257): onHandleIntent:holiday data empty
I/ActivityManager(  862): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6295 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     ( 5993): CheckpointMarkThreadRoots callback created = 0xb05833a0
,I/art     ( 5993): CheckpointMarkThreadRoots callback created = 0xb0583390
,W/ResourcesManager( 6295): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6295): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,W/ResourcesManager( 6295): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6295): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6295): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/IndexDatabaseHelper( 6295): Using schema version: 115
,I/IndexDatabaseHelper( 6295): Index is fine
I/ActivityManager(  862): Process com.lge.qremote (pid 5076) has died
,D/UEI.SmartControl( 5814): Service.onUnbind: IControl
D/UEI.SmartControl( 5814): Service.onDestroy
D/UEI.SmartControl( 5814): Shutdown IRRCPlayer... 
,W/irrc_jni( 5814): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5814): ~IrrcClient ++ 
D/irrcClient( 5814): ~IrrcClient -- 
W/irrc_jni( 5814): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5814): Blaster closed
D/UEI.SmartControl( 5814): Blaster closed
D/UEI.SmartControl( 5814): Shut down QS...
D/UEI.SmartControl( 5814): Stopped file observer...
,I/UEI.SmartControl( 5814): QS lib stop result = true
D/UEI.SmartControl( 5814): QS shutdown complete
I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5526): 
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
,I/ActivityManager(  862): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6324 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  862): android: cancelAsUser(2) by android
,I/PCSuite ( 6324): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6324): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6324): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/qtaguid ( 5993): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5993): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5993): untagSocket(41) failed with errno -22
,I/ActivityManager(  862): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6345 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager(  862): Killing 5885:com.android.contacts/u0a18 (adj 15): empty #11
,I/ActivityManager(  862): Process com.google.android.apps.plus (pid 5937) has died
W/libprocessgroup(  862): failed to open /acct/uid_10018/pid_5885/cgroup.procs: No such file or directory
,W/ResourcesManager( 6345): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/BluetoothManagerService(  862): Message: 20
D/BluetoothManagerService(  862): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@328a6a03:true
,D/BluetoothAdapterService(167692636)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@32340192
D/BluetoothAdapterService(167692636)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@32340192
,W/ResourcesManager( 5993): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5993): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
I/PCSuite ( 6324): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6324): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6324): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ResourcesManager( 5993): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  862): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6373 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6373): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Finsky  ( 5993): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  862): RTC_WAKEUP set : Alarm{1f5f6e0a type 0 when 1454970759076 com.android.vending} when 1454970759076
,D/DeviceConnectionService( 1734): client connected with version: 8296000
,D/Finsky  ( 5993): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5993): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  862): Killing 5914:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  862): failed to open /acct/uid_10069/pid_5914/cgroup.procs: No such file or directory
,V/AlarmManager(  862): RTC_WAKEUP set : Alarm{a49f57 type 0 when 1454970759160 com.google.android.googlequicksearchbox} when 1454970759160
I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5526): 
,E/lowmemorykiller(  241): Error writing /proc/6189/oom_score_adj; errno=22
,I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5526): 
I/ActivityManager(  862): Process com.google.android.gm (pid 6189) has died
,I/art     ( 6373): CheckpointMarkThreadRoots callback created = 0xb042d430
I/Babel_SMS( 6373): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6373): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6373): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6373): MmsConfig.loadFromDatabase
I/art     ( 6373): CheckpointMarkThreadRoots callback created = 0xb042d410
,I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5526): 
,E/Babel_SMS( 6373): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6373): MmsConfig.loadFromResources
E/Babel_SMS( 6373): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6373): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5526): 
,D/SensorManager( 6373): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6373): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6373): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6373): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6373): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6373): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6373): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6373): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6373): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6373): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6373): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6373): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6373): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6373): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6373): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6373): found sensor: Motion Accel, handle=46
,W/Settings( 6373): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6373): startup - clean
I/Babel   ( 6373): deleted: false for 0
,V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
I/PCSuite ( 6324): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6324): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6324): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6373): Unsupported mime audio/x-lg-flac
D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
,W/AudioCapabilities( 6373): Unsupported mime audio/adpcm
I/PCSuite ( 6324): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6324): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6324): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/AudioCapabilities( 6373): Unsupported mime audio/g726
V/WiFiOffLoadBroadcast( 6295): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/AudioCapabilities( 6373): Unsupported mime audio/x-ms-wma
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/AudioCapabilities( 6373): Unsupported mime audio/wma-voice
,D/WiFiOffLoadBroadcast( 6295): MCCMNC not supported: null
W/VideoCapabilities( 6373): Unsupported mime video/mjpg
W/VideoCapabilities( 6373): Unsupported mime video/theora
,W/AudioCapabilities( 6373): Unsupported mime audio/evrc
,W/AudioCapabilities( 6373): Unsupported mime audio/qcelp
W/VideoCapabilities( 6373): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6373): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6373): Unsupported mime audio/qcelp
W/AudioCapabilities( 6373): Unsupported mime audio/evrc
W/VideoCapabilities( 6373): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6373): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6373): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6373): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6373): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6373): Unrecognized profile 2130706433 for video/avc
,I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5526): 
,I/vclib   ( 6373): onServiceConnected
W/Babel   ( 6373): Attempted to change video mute state without an active call.
I/jxcore-log( 5526): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5526): 
I/ActivityManager(  862): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6408 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  862): Process com.uei.lg.quicksetsdk.lite (pid 5814) has died
,I/NotificationManager( 6373): com.google.android.talk: cancel(8) by com.google.android.talk
,I/NotificationManager( 6373): com.google.android.talk: cancel(10436) by com.google.android.talk
W/ResourcesManager( 6373): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6373): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 6408): onCreate
,W/AppUp4:DB( 6408):  [AppBoxDatabaseHelper] construct
V/JNIHelp ( 6373): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:DB( 6408):  setFingerPrint start
I/AppUp4:DB( 6408):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6408):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6408):  SDK version = 0
I/AppUp4:DB( 6408):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6408): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6408): onReceive
I/AppUp4:CustModeStarterReceiver( 6408): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6408): Context : android.app.ReceiverRestrictedContext@36d8dbe2
D/AppUp4:CustFacade( 6408): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6408): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6408): begin check event
I/AppUp4:CustModeStarterReceiver( 6408): Event For Nothing, skip.
,W/System  ( 6373): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6373): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  862): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6430 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,W/ResourcesManager( 6430): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6430): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6430): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/ActivityManager(  862): Process com.google.android.setupwizard (pid 6153) has died
,I/AppConfig( 6430): Total System Memory = 906309632
I/GalleryUtils( 6430): Application Heap = 96 MB
I/AppConfig( 6430): App Tier : NOT_DEF
D/SystemHelper( 6430): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  862): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6452 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ResourcesManager( 6452): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6452): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6452): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6452): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6452): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6452): BUILD Country: EU
,I/SystemConfig( 6452): BUILD Operator: OPEN
I/ActivityManager(  862): Process com.android.vending (pid 5993) has died
,D/CAR.SERVICE( 6231): mConnectedToCar = false, abort
E/ActivityThread( 6231): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3d051031 that was originally bound here
E/ActivityThread( 6231): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3d051031 that was originally bound here
E/ActivityThread( 6231): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6231): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6231): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6231): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6231): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6231): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6231): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6231): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6231): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6231): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6231): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6231): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6231): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6231): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6231): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6231): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6231): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6231): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6231): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/ActivityManager(  862): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6471 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,E/ActivityThread( 6231): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@192b96f0 that was originally bound here
E/ActivityThread( 6231): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@192b96f0 that was originally bound here
E/ActivityThread( 6231): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6231): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6231): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6231): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6231): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6231): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6231): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6231): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6231): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6231): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6231): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6231): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6231): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6231): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6231): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6231): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6231): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6231): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6231): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6231): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6231): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6231): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  862): Unbind failed: could not find connection for android.os.BinderProxy@1727760c
I/SystemConfig( 6452): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6452): existFile = false
I/SystemConfig( 6452): canReadFile = false
I/SystemConfig( 6452): systemFeature RCS result false
D/SystemConfig( 6452): refreshRcsSupport() :false
,I/art     (  862): Explicit concurrent mark sweep GC freed 17383(809KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.556ms total 147.699ms
,I/LockScreenSettings( 6471): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6471): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6471): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6471): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6471): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6471): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  862): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6488 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  862): Killing 6054:com.google.android.partnersetup/u0a9 (adj 15): empty #11
I/art     (  305): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 428us total 23.085ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 8(256B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.630ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 25.607ms
,W/libprocessgroup(  862): failed to open /acct/uid_10009/pid_6054/cgroup.procs: No such file or directory
,W/ResourcesManager( 6488): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 53 ms] updated apps [took 52 ms] 
,I/ActivityManager(  862): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6520 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  862): Killing 6080:com.google.android.configupdater/u0a3 (adj 15): empty #11
,D/AlertService( 6257): Beginning updateAlertNotification
,W/libprocessgroup(  862): failed to open /acct/uid_10003/pid_6080/cgroup.procs: No such file or directory
I/ActivityManager(  862): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6537 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6537): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6537): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3f0958d7
,D/CalendarProvider2( 6537): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6537): Created com.android.providers.calendar.CalendarAlarmManager@30183a30(com.android.providers.calendar.CalendarProvider2@3f0958d7)
,D/Finsky  ( 6520): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/AlertService( 6257): No fired or scheduled alerts
,I/NotificationManager( 6257): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(15) by com.android.calendar
,I/NotificationManager( 6257): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6257): com.android.calendar: cancel(20) by com.android.calendar
,D/AlertService( 6257): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6257): No events found starting within 1 week.
,I/ActivityManager(  862): Killing 6257:com.android.calendar/u0a13 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  862): failed to open /acct/uid_10013/pid_6257/cgroup.procs: No such file or directory
,D/Finsky  ( 6520): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6520): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6520): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6520): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 6520): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6520): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6520): Skipping gmscore version check
I/ActivityManager(  862): Killing 6231:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  862): failed to open /acct/uid_10006/pid_6231/cgroup.procs: No such file or directory
,I/ActivityManager(  862): Killing 6295:com.android.settings/1000 (adj 15): empty #11
V/DownloadManager( 3208): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@ebbb0f2 on behalf of 6520
W/PackageSettings(  862): Skipping PackageSetting{2b295bc2 com.example.hello/10317} due to missing metadata
,W/libprocessgroup(  862): failed to open /acct/uid_1000/pid_6295/cgroup.procs: No such file or directory
D/PackageBroadcastService( 5584): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5584): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 6520): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/Icing   ( 5584): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 6520): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  862): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6602 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6345): Create singleton instance
,I/AudioManager( 6345): getMode name:com.lge.qremote
,I/ActivityManager(  862): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6621 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/UEI.SmartControl( 6602): Quickset Services start...
I/UEI.SmartControl( 6602): Manufacture = LGE
D/UEI.SmartControl( 6602): File observer start...
W/ResourcesManager( 6621): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6621): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6621): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/UEI.SmartControl( 6602): IR Port is disabled: false
D/UEI.SmartControl( 6602): Starting file observer...
D/UEI.SmartControl( 6602): Extracting JNI libs...
W/ResourcesManager( 6621): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6621): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6602): --- this system supports 32-bit or 64-bit only
,I/IndexDatabaseHelper( 6621): Using schema version: 115
I/IndexDatabaseHelper( 6621): Index is fine
,V/WiFiOffLoadBroadcast( 6621): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/UEI.SmartControl( 6602): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6602): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6602): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,D/WiFiOffLoadBroadcast( 6621): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6621): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6621): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6621): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6621): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6621): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/UEI.SmartControl( 6602): --- Selecting new region: 2
I/UEI.SmartControl( 6602): -- Running on KitKat(19) and above! JNI will be used.
D/WiFiOffLoadBroadcast( 6621): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6621): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/UEI.SmartControl( 6602): Platform has CIR...
D/UEI.SmartControl( 6602): NO CIR support, need to check package...
I/UEI.SmartControl( 6602): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6602): QS Service created
,D/WiFiOffLoadBroadcast( 6621): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6621): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6621): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6621): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6621): MCCMNC not supported: null
E/UEI.SmartControl( 6602): QS start get config
V/WiFiOffLoadBroadcast( 6621): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6621): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6621): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6621): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6621): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6621): MCCMNC not supported: null
I/PCSuite ( 6324): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6324): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/UEI.SmartControl( 6602): Loading JNI Libs...
D/UEI.SmartControl( 6602):  configuring local db...
V/WiFiOffLoadBroadcast( 6621): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6621): MCCMNC not supported: null
I/PCSuite ( 6324): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6324): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  862): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6649 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6649): Register our PhoneStateListener
,I/ActivityManager(  862): Killing 6408:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/PhoneMonitor( 6649): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6649): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6649): [parse] Load xml
V/TelephonyAutoProfiling( 6649): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6649): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6649): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/UEI.SmartControl( 6602):  ---- Has DB8: true
,D/UEI.SmartControl( 6602): QS start statue = true Error code = 0
D/UEI.SmartControl( 6602): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6602): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6602): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6602): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6602): IrrcClient ++ 
D/irrcClient( 6602): getIrrcService ++ 
D/irrcClient( 6602): getIrrcService -- 
D/irrcClient( 6602): IrrcClient -- 
W/irrc_jni( 6602): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6602): Services init done
I/UEI.SmartControl( 6602): Device manager: loading config....
D/UEI.SmartControl( 6602): Config is loaded...
,I/rmt_storage(  269): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  269): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  269): wakelock acquired: 1, error no: 42
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
D/UEI.SmartControl( 6602):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6602): Notify AllClients services are ready: 0
,W/libprocessgroup(  862): failed to open /acct/uid_10011/pid_6408/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6602): QS Service init finished
,D/UEI.SmartControl( 6602): QS Service version name: 0.1.73
D/UEI.SmartControl( 6602): QS Service version code: 1073
D/UEI.SmartControl( 6602): Service requested: Control
D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/CalendarProviderBroadcastReceiver( 6537): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
I/CheckinService( 5584): Checkin interval check for package: unspecified last checkin: 1454970739734 min interval config: 0 actual interval: 24718
D/UEI.SmartControl( 6602): Internal service binding...
I/CheckinService( 5584): Checking schedule, now: 1454970764458 next: 1454970769683
I/CheckinService( 5584): active receiver: disabled
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,D/CalendarProviderBroadcastReceiver( 6537): [IntentService] WakeLock acquire, start IntentSerivce
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  269): 
D/UEI.SmartControl( 6602): -----IControl: 11
I/rmt_storage(  269): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/UEI.SmartControl( 6602): Caller: com.lge.qremote
D/UEI.SmartControl( 6602): ------------ IControl registerCallback...
I/UEI.SmartControl( 6602): Registering callback...
D/UEI.SmartControl( 6602): -----IControl: 19
D/UEI.SmartControl( 6602): Caller: com.lge.qremote
I/UEI.SmartControl( 6602): Registering Services Ready callback...
I/UEI.SmartControl( 6602): Notify client services are ready...
,D/CalendarProvider2( 6537): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6537): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/UEI.SmartControl( 6602): -----IControl: 8
D/CalendarProvider2( 6537): [getOrCreateCalendarAlarmManager]
D/UEI.SmartControl( 6602): Caller: com.lge.qremote
I/ActivityManager(  862): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6676 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  862): Killing 6430:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/Icing   ( 5584): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,W/libprocessgroup(  862): failed to open /acct/uid_10023/pid_6430/cgroup.procs: No such file or directory
D/CalendarProvider2( 6537): [IntentService] Release Lock
D/CalendarProvider2( 6537): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  862): Killing 6452:com.android.contacts/u0a18 (adj 15): empty #11
,D/Icing   ( 5584): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5584): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/libprocessgroup(  862): failed to open /acct/uid_10018/pid_6452/cgroup.procs: No such file or directory
,I/ActivityManager(  862): Killing 6471:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/MusicStore( 6676): Database version: 120
,W/libprocessgroup(  862): failed to open /acct/uid_10069/pid_6471/cgroup.procs: No such file or directory
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6676): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6676): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6676): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6676): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6676): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6676): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6676): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6676): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1abaca95: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6676): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6676): GMSCore installation verified
I/ConfigStore( 6676): Config Database version: 1
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/MediaRouter( 6676): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6676): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6676): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  862): Killing 6373:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  862): failed to open /acct/uid_10061/pid_6373/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6676): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  862): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6715 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6676): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6676): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6715): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6715): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6715): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  862): Killing 6488:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  862): failed to open /acct/uid_10086/pid_6488/cgroup.procs: No such file or directory
,I/NotificationManager( 6676): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6715): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6715): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6715): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  862): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6746 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/LGDMClient( 6746): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6746): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6746): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6746): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  862): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6767 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  862): Explicit concurrent mark sweep GC freed 25508(1461KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 3.333ms total 198.425ms
,D/LGDMClient( 6746): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6746): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6746): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6746): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/HubEmail( 6715): JNI_OnLoad()
I/HubEmail( 6715): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6715): registerNatives()
I/HubEmail( 6715): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6715): registerNativeMethods()
I/HubEmail( 6715): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6715): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/ContextImpl( 6746): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6746): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6746): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6746): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
W/Settings( 6715): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6746): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/ActivityManager(  862): Killing 6520:com.android.vending/u0a36 (adj 15): empty #11
D/LGDMClient( 6746): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/AppUp4:AppBoxCP( 6767): onCreate
W/AppUp4:DB( 6767):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6767):  setFingerPrint start
I/AppUp4:DB( 6767):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6767):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6767):  SDK version = 0
I/AppUp4:DB( 6767):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  862): failed to open /acct/uid_10036/pid_6520/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6767): AppBoxApplication onCreate()
I/ActivityManager(  862): Killing 6621:com.android.settings/1000 (adj 15): empty #11
I/NetworkStateForAutoUpdateMonitor( 6767): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6767): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6767): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6767): [onReceive] request level :IDLE....
W/libprocessgroup(  862): failed to open /acct/uid_1000/pid_6621/cgroup.procs: No such file or directory
,I/AppUp4:CustModeStarterReceiver( 6767): onReceive
I/AppUp4:CustModeStarterReceiver( 6767): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6767): Context : android.app.ReceiverRestrictedContext@d2b96a9
D/AppUp4:CustFacade( 6767): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6767): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6767): begin check event
I/AppUp4:CustModeStarterReceiver( 6767): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 6767): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6767): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6767): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6767): handleAsyncCustNotification do not startCustService
I/ActivityManager(  862): Killing 6602:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6345): android.os.DeadObjectException
,W/System.err( 6345): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6345): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 6345): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,W/System.err( 6345): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6345): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6345): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6345): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6345): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6345): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6345): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6345): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6345): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6345): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6345): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6345): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6345): android.os.DeadObjectException
W/System.err( 6345): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6345): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6345): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6345): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6345): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6345): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6345): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6345): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6345): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6345): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6345): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6345): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6345): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6345): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/UEI.SmartControl( 6345): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
E/libprocessgroup(  862): failed to kill 1 processes for processgroup 6602
,I/LgeMiscReceiver( 3226): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3226): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3226): networkInfo.isConnected() = false
,W/ActivityManager(  862): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/MobileConnectivityChangeReceiver( 6649): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6649): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  862): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6806 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DownloadManager( 3208): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3208): DownloadService onCreate
I/art     (  305): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 307us total 22.912ms
,I/ActivityManager(  862): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6825 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/DownloadManager( 3208): in removeSpuriousFiles
V/DownloadManager( 3208): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@3004343 on behalf of 3208
I/DownloadManager( 3208): in trimDatabase
V/DownloadManager( 3208): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@246d3dc0 on behalf of 3208
I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 30.946ms
,I/NotificationManager( 3208): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.364ms
D/UEI.SmartControl( 6806): Quickset Services start...
I/UEI.SmartControl( 6806): Manufacture = LGE
D/UEI.SmartControl( 6806): File observer start...
E/UEI.SmartControl( 6806): IR Port is disabled: false
D/UEI.SmartControl( 6806): Starting file observer...
D/UEI.SmartControl( 6806): Extracting JNI libs...
D/UEI.SmartControl( 6806): --- this system supports 32-bit or 64-bit only
,V/DownloadManager( 3208): DownloadService onStartCommand
V/DownloadManager( 3208): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@859d09f on behalf of 3208
D/UEI.SmartControl( 6806): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6806): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 6806): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/DownloadManager( 3208): DownloadService onDestroy
,I/ActivityManager(  862): Killing 6324:com.lge.sync/1000 (adj 15): empty #11
,I/UEI.SmartControl( 6806): --- Selecting new region: 2
I/UEI.SmartControl( 6806): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6806): Platform has CIR...
D/UEI.SmartControl( 6806): NO CIR support, need to check package...
I/UEI.SmartControl( 6806): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6806): QS Service created
W/libprocessgroup(  862): failed to open /acct/uid_1000/pid_6324/cgroup.procs: No such file or directory
,I/CheckinService( 5584): Done disabling old GoogleServicesFramework version
D/WeatherAncestor( 2747): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:32:47
,E/UEI.SmartControl( 6806): QS start get config
D/UpdateThreadPoolManager( 2747): 2 : This is isUpdating : false
D/WeatherAncestor( 2747): connectivity changed - connection : true
D/Weather_cast( 2747): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2747): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:32:47
D/WeatherService( 2747): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  862): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6855 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  862): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2747): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/UEI.SmartControl( 6806): Loading JNI Libs...
D/UEI.SmartControl( 6806):  configuring local db...
D/WeatherService( 2747): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2747): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6855): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6806):  ---- Has DB8: true
,D/UEI.SmartControl( 6806): QS start statue = true Error code = 0
D/UEI.SmartControl( 6806): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6806): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6806): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6806): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6806): IrrcClient ++ 
D/irrcClient( 6806): getIrrcService ++ 
D/irrcClient( 6806): getIrrcService -- 
D/irrcClient( 6806): IrrcClient -- 
W/irrc_jni( 6806): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6806): Services init done
,D/UEI.SmartControl( 6806): QS Service init finished
D/UEI.SmartControl( 6806): QS Service version name: 0.1.73
D/UEI.SmartControl( 6806): QS Service version code: 1073
D/UEI.SmartControl( 6806): Service requested: Control
I/UEI.SmartControl( 6806): Device manager: loading config....
,D/UEI.SmartControl( 6806): Config is loaded...
D/UEI.SmartControl( 6806): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6806):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6806): Notify AllClients services are ready: 0
I/ActivityManager(  862): Killing 6345:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6806): -----IControl: 11
D/UEI.SmartControl( 6806): Caller: com.lge.qremote
D/UEI.SmartControl( 6806): ------------ IControl registerCallback...
I/UEI.SmartControl( 6806): Registering callback...
W/libprocessgroup(  862): failed to open /acct/uid_10106/pid_6345/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6806): Internal service binding...
I/art     ( 6855): CheckpointMarkThreadRoots callback created = 0xb042d550
,I/Babel_SMS( 6855): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6855): MmsConfig.loadMmsSettings
I/Babel_SMS( 6855): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6855): MmsConfig.loadFromDatabase
,I/art     ( 6855): CheckpointMarkThreadRoots callback created = 0xb042d530
,E/Babel_SMS( 6855): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6855): MmsConfig.loadFromResources
E/Babel_SMS( 6855): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6855): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6855): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6855): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6855): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6855): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6855): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6855): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6855): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6855): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6855): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6855): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6855): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6855): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6855): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6855): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6855): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6855): found sensor: Motion Accel, handle=46
W/Settings( 6855): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6855): startup - clean
,I/Babel   ( 6855): deleted: false for 0
I/ActivityManager(  862): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6893 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6855): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6855): Unsupported mime audio/adpcm
W/AudioCapabilities( 6855): Unsupported mime audio/g726
W/AudioCapabilities( 6855): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6855): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6855): Unsupported mime video/mjpg
,W/VideoCapabilities( 6855): Unsupported mime video/theora
W/AudioCapabilities( 6855): Unsupported mime audio/evrc
,W/AudioCapabilities( 6855): Unsupported mime audio/qcelp
W/VideoCapabilities( 6855): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6855): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6855): Unsupported mime audio/qcelp
W/AudioCapabilities( 6855): Unsupported mime audio/evrc
W/VideoCapabilities( 6855): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6855): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6855): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6855): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6855): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6855): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6855): onServiceConnected
,W/Babel   ( 6855): Attempted to change video mute state without an active call.
I/NotificationManager( 6855): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6855): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6855): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  272): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 6855): propertyValue:false
W/art     ( 6855): Suspending all threads took: 5.635ms
,I/Babel   ( 6855): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  862): Killing 6537:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  862): failed to open /acct/uid_10014/pid_6537/cgroup.procs: No such file or directory
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6893): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6893): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6893): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6893): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 6893): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6893):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6893):   adb logcat -s GAv4
W/GAv4    ( 6893): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6893): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6893): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6893): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6893): Time to load native libraries: 2 ms (timestamps 7534-7536)
,I/LibraryLoader( 6893): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6893): Binding Chromium to main looper Looper (main, tid 1) {2e3e3aa2}
I/LibraryLoader( 6893): Expected native library version number "",actual native library version number ""
I/chromium( 6893): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6893): Initializing chromium process, singleProcess=true
W/art     ( 6893): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6893): ApplicationContext is null in ApplicationStatus
W/chromium( 6893): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/jxcore-log( 5526): Test app app.js loaded
I/jxcore-log( 5526): 
E/libEGL  ( 6893): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6893): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6893): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6893): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6893): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6893): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6893): Remote Branch: 
I/Adreno-EGL( 6893): Local Patches: 
I/Adreno-EGL( 6893): Reconstruct Branch: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5526): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@117e097c added. We now have 1 listener(s)
,D/BluetoothAdapterService(167692636)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@32340192
I/jxcore-log( 5526): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5526): 
I/jxcore-log( 5526): TAP version 13
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): # setup
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 5526): 
,I/chromium( 5526): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 5526): ok 1 should be equal
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # teardown
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # setup
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 5526): 
,V/AudioPolicyService(  276): registerClient() client 0xb383db60, uid 10079
W/AudioManagerAndroid( 6893): Requires BLUETOOTH permission
I/NSApplication( 6893): Starting up...
,I/ActivityManager(  862): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6964 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  862): Killing 6676:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/jxcore-log( 5526): ok 2 should be equal
I/jxcore-log( 5526): 
I/jxcore-log( 5526): ok 3 should be equal
I/jxcore-log( 5526): 
I/jxcore-log( 5526): ok 4 should be equal
I/jxcore-log( 5526): 
I/jxcore-log( 5526): ok 5 should be equal
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # teardown
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # setup
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): ok 6 should throw
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): # teardown
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # setup
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 5526): 
I/jxcore-log( 5526): ok 7 should throw
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): # teardown
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # setup
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # #parseBeacons no beacons returns null
I/jxcore-log( 5526): 
W/libprocessgroup(  862): failed to open /acct/uid_10081/pid_6676/cgroup.procs: No such file or directory
,I/jxcore-log( 5526): ok 8 should be equal
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # teardown
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # setup
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): ok 9 should throw
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # teardown
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # setup
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 5526): 
,I/ActivityManager(  862): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6986 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  862): Killing 6715:com.lge.email/u0a21 (adj 15): empty #11
I/jxcore-log( 5526): ok 10 should be equal
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): # teardown
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # setup
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # #parseBeacons addressBookCallback returns null for all
I/jxcore-log( 5526): 
W/libprocessgroup(  862): failed to open /acct/uid_10021/pid_6715/cgroup.procs: No such file or directory
,W/ResourcesManager( 6986): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 5526): ok 11 (unnamed assert)
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): ok 12 should be equal
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): # teardown
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # setup
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 5526): 
I/jxcore-log( 5526): ok 13 (unnamed assert)
I/jxcore-log( 5526): 
,I/jxcore-log( 5526): ok 14 (unnamed assert)
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # teardown
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # setup
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 5526): 
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/jxcore-log( 5526): ok 15 (unnamed assert)
I/jxcore-log( 5526): 
I/jxcore-log( 5526): # teardown
I/jxcore-log( 5526): 
,I/iu.SyncManager( 5584): SYNC; picasa accounts
,D/NetworkLogImpl( 5584): Loaded NetworkSpeedPredictor
I/iu.Environment( 5584): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  862): Killing 6746:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/iu.UploadsManager( 5584): num queued entries: 0
,I/iu.UploadsManager( 5584): num updated entries: 0
I/iu.SyncManager( 5584): NEXT; no task
W/libprocessgroup(  862): failed to open /acct/uid_1000/pid_6746/cgroup.procs: No such file or directory
,I/ActivityManager(  862): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7021 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7021): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7021): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7021): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7021): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7021): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7021): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7021): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7021): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7021): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1abaca95: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7021): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 7021): GMSCore installation verified
I/ConfigStore( 7021): Config Database version: 1
,I/MediaRouter( 7021): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7021): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7021): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7021): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  862): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7052 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7021): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7021): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 7052): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7052): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7052): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  862): Killing 6767:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  862): failed to open /acct/uid_10011/pid_6767/cgroup.procs: No such file or directory
,I/NotificationManager( 7021): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7052): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/LGEmail ( 7052): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7052): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  862): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7075 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7052): JNI_OnLoad()
I/HubEmail( 7052): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7052): registerNatives()
I/HubEmail( 7052): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7052): registerNativeMethods()
I/HubEmail( 7052): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7052): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7052): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  862): Killing 6649:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  862): failed to open /acct/uid_10038/pid_6649/cgroup.procs: No such file or directory
,D/LGDMClient( 7075): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7075): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7075): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7075): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 7075): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7075): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 7075): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7075): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  862): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7099 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7075): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7075): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7075): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7075): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7075): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7075): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  862): Killing 6806:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  862): failed to open /acct/uid_10089/pid_6806/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7099): onCreate
,W/AppUp4:DB( 7099):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7099):  setFingerPrint start
I/AppUp4:DB( 7099):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7099):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7099):  SDK version = 0
I/AppUp4:DB( 7099):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7099): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7099): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7099): onReceive
I/AppUp4:CustModeStarterReceiver( 7099): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7099): Context : android.app.ReceiverRestrictedContext@d2b96a9
D/AppUp4:CustFacade( 7099): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7099): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7099): begin check event
I/AppUp4:CustModeStarterReceiver( 7099): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7099): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7099): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7099): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7099): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  862): Killing 6825:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  862): failed to open /acct/uid_10051/pid_6825/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3226): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3226): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3226): networkInfo.isConnected() = false
,I/ActivityManager(  862): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7126 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     (  862): Explicit concurrent mark sweep GC freed 19680(982KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 6.055ms total 155.439ms
,D/PhoneMonitor( 7126): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7126): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7126): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  862): Killing 6855:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7126): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7126): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7126): [parse] Load xml
V/TelephonyAutoProfiling( 7126): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7126): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7126): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  862): failed to open /acct/uid_10061/pid_6855/cgroup.procs: No such file or directory
V/DownloadManager( 3208): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/AlarmManager(  862): RTC_WAKEUP set : Alarm{30894ec8 type 0 when 1454970769683 com.google.android.gms} when 1454970769683
,I/ActivityManager(  862): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7149 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  862): RTC_WAKEUP set : Alarm{3727ab61 type 0 when 1454970772935 com.android.vending} when 1454970772935
,V/DownloadManager( 3208): DownloadService onCreate
,I/DownloadManager( 3208): in removeSpuriousFiles
V/DownloadManager( 3208): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@ad04db5 on behalf of 3208
I/NotificationManager( 3208): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3208): in trimDatabase
V/DownloadManager( 3208): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@215c6c4a on behalf of 3208
,I/ActivityManager(  862): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7170 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3208): DownloadService onStartCommand
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.386ms
,I/CheckinService( 5584): Checkin interval check for package: unspecified last checkin: 1454970739734 min interval config: 0 actual interval: 33362
,V/DownloadManager( 3208): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@3d051031 on behalf of 3208
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 22.701ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.921ms
,I/CheckinService( 5584): Checking schedule, now: 1454970773140 next: 1454970769683
I/CheckinService( 5584): active receiver: enabled
,V/DownloadManager( 3208): DownloadService onDestroy
,I/CheckinService( 5584): Preparing to send checkin request
,I/EventLogService( 5584): Accumulating logs since 1454970731333
D/WeatherAncestor( 2747): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:32:53
,D/UpdateThreadPoolManager( 2747): 2 : This is isUpdating : false
D/WeatherAncestor( 2747): connectivity changed - connection : true
D/Weather_cast( 2747): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2747): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:32:53
D/WeatherService( 2747): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  862): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7193 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  862): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2747): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2747): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2747): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7193): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Finsky  ( 7149): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/CheckinRequestBuilder( 5584): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5584): Failed to find provider info for com.google.android.wearable.settings
,D/Finsky  ( 7149): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7149): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7149): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7149): com.android.vending: cancel(-1050172287) by com.android.vending
I/Babel_SMS( 7193): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7193): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7193): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7193): MmsConfig.loadFromDatabase
D/Ads     ( 7149): Skipping gmscore version check
,E/Babel_SMS( 7193): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7193): MmsConfig.loadFromResources
,E/Babel_SMS( 7193): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7193): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
V/DownloadManager( 3208): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/Finsky  ( 7149): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7149): [1] Libraries$2.run: Finished loading 1 libraries.
,V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@7af3497 on behalf of 7149
D/Finsky  ( 7149): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7149): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/SensorManager( 7193): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7193): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7193): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7193): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7193): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7193): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7193): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7193): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7193): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7193): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7193): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7193): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7193): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7193): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7193): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7193): found sensor: Motion Accel, handle=46
I/art     ( 7193): CheckpointMarkThreadRoots callback created = 0xb042d550
,W/Settings( 7193): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7193): startup - clean
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Babel   ( 7193): deleted: false for 0
,I/art     ( 7193): CheckpointMarkThreadRoots callback created = 0xb042d520
W/AudioCapabilities( 7193): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7193): Unsupported mime audio/adpcm
W/AudioCapabilities( 7193): Unsupported mime audio/g726
W/AudioCapabilities( 7193): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7193): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7193): Unsupported mime video/mjpg
W/VideoCapabilities( 7193): Unsupported mime video/theora
,I/ActivityManager(  862): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7250 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/AudioCapabilities( 7193): Unsupported mime audio/evrc
,W/AudioCapabilities( 7193): Unsupported mime audio/qcelp
W/VideoCapabilities( 7193): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7193): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7193): Unsupported mime audio/qcelp
W/AudioCapabilities( 7193): Unsupported mime audio/evrc
W/VideoCapabilities( 7193): Unsupported mime video/mp4v-esdp
,I/ActivityManager(  862): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7267 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 7250): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/VideoCapabilities( 7193): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7193): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 7267): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7267): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 7193): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7193): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7193): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7193): onServiceConnected
W/Babel   ( 7193): Attempted to change video mute state without an active call.
,I/NotificationManager( 7193): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7193): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7193): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7193): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7193): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  272): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 7193): propertyValue:false
I/Babel   ( 7193): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  862): Killing 7021:com.google.android.music:main/u0a81 (adj 15): empty #11
D/BluetoothManagerService(  862): Message: 20
D/BluetoothManagerService(  862): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b3b0f35:true
D/Finsky  ( 7149): [895] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,I/MultiDex( 7267): VM with version 2.1.0 has multidex support
D/Finsky  ( 7149): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/MultiDex( 7267): install
I/MultiDex( 7267): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  862): Killing 7052:com.lge.email/u0a21 (adj 15): empty #11
,D/BluetoothAdapterService(167692636)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@32340192
,W/libprocessgroup(  862): failed to open /acct/uid_10081/pid_7021/cgroup.procs: No such file or directory
,W/libprocessgroup(  862): failed to open /acct/uid_10021/pid_7052/cgroup.procs: No such file or directory
D/BluetoothAdapterService(167692636)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@32340192
I/AudioManager( 7250): getMode name:com.lge.qremote
,V/JNIHelp ( 7267): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AudioManager( 7250): getMode name:com.lge.qremote
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ActivityThread( 7267): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  862): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7291 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/System  ( 7267): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ebbb0f2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7267): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7267): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7267): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/art     ( 7267): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7267): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/MusicStore( 7291): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7291): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,D/NativeLibraryUtils( 7267): Install completed successfully. count=14 extracted=0
,I/art     ( 3961): Explicit concurrent mark sweep GC freed 2240(87KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 377us total 33.999ms
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7291): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,D/WVCdm   (  276): Instantiating CDM.
I/WVCdm   (  276): CdmEngine::OpenSession
I/WVCdm   (  276): Level3 Library Dec 11 2014 16:13:16
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7291): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7291): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7291): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/WVCdm   (  276): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  276): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  276): L1 library not specified. Falling Back to L3
V/JNIHelp ( 7291): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  276): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  276): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
D/WVCdm   (  276): PrepareKeyRequest: nonce=2254559127
W/ActivityThread( 7291): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7291): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1abaca95: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7291): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7291): GMSCore installation verified
,I/ActivityManager(  862): Process com.lge.appbox.client (pid 7099) has died
,I/ConfigStore( 7291): Config Database version: 1
,I/MediaRouter( 7291): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 7291): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7291): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7291): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  862): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7324 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7291): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7291): Using platform SSLCertificateSocketFactory
,I/art     ( 7267): CheckpointMarkThreadRoots callback created = 0xb042d470
,I/art     ( 7267): CheckpointMarkThreadRoots callback created = 0xb042d460
,I/dex2oat ( 7343): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/art     (  862): Explicit concurrent mark sweep GC freed 21421(983KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.723ms total 198.062ms
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
I/NotificationManager( 7291): com.google.android.music: cancel(1061) by com.google.android.music
W/ResourcesManager( 7324): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7324): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7324): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/dex2oat ( 7343): dex2oat took 115.859ms (threads: 4)
I/Adreno-EGL( 7267): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7267): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7267): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7267): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7267): Remote Branch: 
I/Adreno-EGL( 7267): Local Patches: 
I/Adreno-EGL( 7267): Reconstruct Branch: 
,I/LGEmail ( 7324): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7324): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/Adreno-EGL( 7267): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7267): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7267): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7267): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7267): Remote Branch: 
I/Adreno-EGL( 7267): Local Patches: 
I/Adreno-EGL( 7267): Reconstruct Branch: 
,I/ActivityManager(  862): Process com.google.android.talk (pid 7193) has died
,D/eas_req ( 7324): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 7075): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7075): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7075): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7075): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7075): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7075): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/HubEmail( 7324): JNI_OnLoad()
,I/HubEmail( 7324): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7324): registerNatives()
I/HubEmail( 7324): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7324): registerNativeMethods()
I/HubEmail( 7324): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7324): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/LGDMClient( 7075): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7075): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  862): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7357 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/Settings( 7324): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 7075): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7075): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7075): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 7075): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7075): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7075): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/Adreno-EGL( 7267): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7267): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7267): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7267): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7267): Remote Branch: 
I/Adreno-EGL( 7267): Local Patches: 
I/Adreno-EGL( 7267): Reconstruct Branch: 
,I/AppUp4:AppBoxCP( 7357): onCreate
W/AppUp4:DB( 7357):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7357):  setFingerPrint start
I/AppUp4:DB( 7357):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7357):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7357):  SDK version = 0
I/AppUp4:DB( 7357):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7357): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7357): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7357): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7357): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7357): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7357): onReceive
I/AppUp4:CustModeStarterReceiver( 7357): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7357): Context : android.app.ReceiverRestrictedContext@d2b96a9
D/AppUp4:CustFacade( 7357): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7357): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7357): begin check event
I/AppUp4:CustModeStarterReceiver( 7357): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7357): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 7357): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7357): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7357): handleAsyncCustNotification do not startCustService
I/ActivityManager(  862): Killing 7170:com.lge.drmservice/u0a51 (adj 15): empty #11
I/WVCdm   (  276): CdmEngine::OpenSession
,W/libprocessgroup(  862): failed to open /acct/uid_10051/pid_7170/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3226): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3226): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3226): networkInfo.isConnected() = true
D/PhoneState( 3226): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 7126): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7126): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3208): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3208): DownloadService onCreate
I/DownloadManager( 3208): in removeSpuriousFiles
I/NotificationManager( 3208): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3208): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@15e97e6d on behalf of 3208
I/DownloadManager( 3208): in trimDatabase
V/DownloadManager( 3208): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@2e3e3aa2 on behalf of 3208
I/ActivityManager(  862): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7381 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3208): DownloadService onStartCommand
V/DownloadManager( 3208): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@192b96f0 on behalf of 3208
,V/DownloadManager( 3208): DownloadService onDestroy
I/ActivityManager(  862): Killing 7149:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  862): failed to open /acct/uid_10036/pid_7149/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2747): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:32:56
D/UpdateThreadPoolManager( 2747): 2 : This is isUpdating : false
D/WeatherAncestor( 2747): connectivity changed - connection : true
D/Weather_cast( 2747): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2747): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:32:56
D/WeatherService( 2747): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  862): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7401 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  862): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2747): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2747): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2747): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7401): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7401): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7401): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7401): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7401): MmsConfig.loadFromDatabase
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/Babel_SMS( 7401): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7401): MmsConfig.loadFromResources
E/Babel_SMS( 7401): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7401): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7401): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7401): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7401): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7401): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7401): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7401): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7401): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7401): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7401): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7401): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7401): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7401): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7401): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7401): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7401): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7401): found sensor: Motion Accel, handle=46
W/Settings( 7401): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7401): startup - clean
I/Babel   ( 7401): deleted: false for 0
,I/art     ( 7401): CheckpointMarkThreadRoots callback created = 0xb042d910
,W/AudioCapabilities( 7401): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7401): Unsupported mime audio/adpcm
W/AudioCapabilities( 7401): Unsupported mime audio/g726
W/AudioCapabilities( 7401): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7401): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7401): Unsupported mime video/mjpg
,W/VideoCapabilities( 7401): Unsupported mime video/theora
I/WVCdm   (  276): CdmEngine::CloseSession
,D/sensors_hal_Time(  862): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  862): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  862): tsOffsetIs: Apps: 115188514597; DSPS: 3872481; Offset : -2994706545
W/AudioCapabilities( 7401): Unsupported mime audio/evrc
I/art     ( 7401): CheckpointMarkThreadRoots callback created = 0xb042d8f0
W/AudioCapabilities( 7401): Unsupported mime audio/qcelp
W/VideoCapabilities( 7401): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7401): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7401): Unsupported mime audio/qcelp
W/AudioCapabilities( 7401): Unsupported mime audio/evrc
I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  276): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  276): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
D/WVCdm   (  276): PrepareKeyRequest: nonce=3799458609
W/VideoCapabilities( 7401): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7401): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7401): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7401): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7401): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7401): Unrecognized profile 2130706433 for video/avc
D/libc-netbsd( 7401): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7401): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7401): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7401): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  272): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  272): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 7401): propertyValue:false
I/Babel   ( 7401): connection state changed from UNKNOWN to CONNECTED
,I/vclib   ( 7401): onServiceConnected
W/Babel   ( 7401): Attempted to change video mute state without an active call.
,I/NotificationManager( 7401): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  862): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7439 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  862): Killing 7291:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/art     ( 7401): Suspending all threads took: 18.768ms
,I/MusicWidget( 2643): mDelayedStopHandler : unbind
,W/libprocessgroup(  862): failed to open /acct/uid_10081/pid_7291/cgroup.procs: No such file or directory
,I/MusicBrowser( 2764): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2764): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2764): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2764): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
,D/MusicBrowser( 2764): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2764): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2764): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2764): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  862):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@275206bfcom.lge.music.MediaPlaybackService$6@32b5418c
D/MusicBrowser( 2764): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3bfdf465
,I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2764): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2764): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2764): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2764): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2764): reset
V/MediaPlayer[Native]( 2764): setListener
V/MediaPlayer[Native]( 2764): disconnect
V/MediaPlayer[Native]( 2764): destructor
,V/AudioFlinger(  276): releasing 19 from 2764 for -1
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
V/MediaPlayer[Native]( 2764): disconnect
D/MusicBrowser( 2764): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2764): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2764): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2764): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2764): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2764): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2764): [SmartShareManagerClient] unregisterListener: 258851029
W/SmartShareClient( 2764): [SmartShareManagerClient] unregisterListener invalid listener: 258851029
I/SmartShareClient( 2764): [SmartShareManagerClient] terminate service: 2764/MediaPlaybackService/539011955
E/HomeCloudIF( 2764): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2764): [SmartShareManagerClient] unbindService context:android.app.Application@3c3a30ea
V/CloudHub( 2764): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2764): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2764): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2764): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2764): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  862): Killing 7324:com.lge.email/u0a21 (adj 15): empty #11
I/CloudHub( 2764): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
W/libprocessgroup(  862): failed to open /acct/uid_10021/pid_7324/cgroup.procs: No such file or directory
,W/ActivityManager(  862): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Gmail   ( 7439): getAccountsCursor
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7439): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  862): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  862): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 7439): Observing account changes for notifications
W/ActivityManager(  862): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7439): Error finding the version of the Email provider.....
E/Gmail   ( 7439): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7439): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7439): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7439): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7439): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7439): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7439): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7439): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7439): We do not support migrating this version of the Email provider.
I/Gmail   ( 7439): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WearableService( 1734): callingUid 10006, callindPid: 1734
,I/ActivityManager(  862): Killing 7075:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  862): failed to open /acct/uid_1000/pid_7075/cgroup.procs: No such file or directory
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 5584): Restart initialization of location
E/MDM     ( 1734): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
I/ActivityManager(  862): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7485 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7250): Create singleton instance
,I/Gmail   ( 7439): notifyAccountChanged
,I/AudioManager( 7250): getMode name:com.lge.qremote
I/Gmail   ( 7439): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7439): getAccountsCursor
I/Gmail   ( 7439): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7439): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7439): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  862): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7504 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.147ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.343ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.153ms
,D/UEI.SmartControl( 7485): Quickset Services start...
I/UEI.SmartControl( 7485): Manufacture = LGE
D/UEI.SmartControl( 7485): File observer start...
E/UEI.SmartControl( 7485): IR Port is disabled: false
D/UEI.SmartControl( 7485): Starting file observer...
D/UEI.SmartControl( 7485): Extracting JNI libs...
D/UEI.SmartControl( 7485): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 7485): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7485): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7485): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/Gmail   ( 7439): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UEI.SmartControl( 7485): --- Selecting new region: 2
I/UEI.SmartControl( 7485): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7485): Platform has CIR...
,D/UEI.SmartControl( 7485): NO CIR support, need to check package...
I/UEI.SmartControl( 7485): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7485): QS Service created
E/UEI.SmartControl( 7485): QS start get config
,D/Finsky  ( 7504): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 7485): Loading JNI Libs...
,D/UEI.SmartControl( 7485):  configuring local db...
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/Finsky  ( 7504): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7504): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7504): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7504): com.android.vending: cancel(-1050172287) by com.android.vending
,D/UEI.SmartControl( 7485):  ---- Has DB8: true
D/UEI.SmartControl( 7485): QS start statue = true Error code = 0
D/UEI.SmartControl( 7485): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 7485): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7485): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7485): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 7485): IrrcClient ++ 
D/irrcClient( 7485): getIrrcService ++ 
D/irrcClient( 7485): getIrrcService -- 
D/irrcClient( 7485): IrrcClient -- 
W/irrc_jni( 7485): IRRCPlayer_nativeInit -- 
D/Ads     ( 7504): Skipping gmscore version check
D/Finsky  ( 7504): [958] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AudioManager( 7250): getMode name:com.lge.qremote
D/UEI.SmartControl( 7485): Services init done
I/UEI.SmartControl( 7485): Device manager: loading config....
,D/UEI.SmartControl( 7485): QS Service init finished
D/UEI.SmartControl( 7485): Config is loaded...
D/UEI.SmartControl( 7485): QS Service version name: 0.1.73
D/UEI.SmartControl( 7485): QS Service version code: 1073
D/UEI.SmartControl( 7485): Service requested: Control
,D/UEI.SmartControl( 7485): Internal service binding...
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinService( 5584): Checkin interval check for package: unspecified last checkin: 1454970739734 min interval config: 0 actual interval: 39248
V/DownloadManager( 3208): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/UEI.SmartControl( 7485): -----IControl: 11
D/Finsky  ( 7504): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7504): [1] Libraries$2.run: Finished loading 1 libraries.
,D/UEI.SmartControl( 7485): Caller: com.lge.qremote
D/UEI.SmartControl( 7485): ------------ IControl registerCallback...
I/UEI.SmartControl( 7485): Registering callback...
D/UEI.SmartControl( 7485): -----IControl: 19
D/UEI.SmartControl( 7485): Caller: com.lge.qremote
,I/UEI.SmartControl( 7485): Registering Services Ready callback...
I/UEI.SmartControl( 7485): Notify client services are ready...
D/UEI.SmartControl( 7485):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 7485): -----IControl: 8
I/UEI.SmartControl( 7485): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7485): Caller: com.lge.qremote
W/ContextImpl( 3605): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/art     (  862): Explicit concurrent mark sweep GC freed 24069(1100KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.484ms total 174.691ms
,V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@3695eee on behalf of 7504
I/WVCdm   (  276): CdmEngine::CloseSession
I/WVCdm   (  276): L3 Terminate.
I/AudioManager( 7250): getMode name:com.lge.qremote
,I/NotificationManager(  862): android: cancelAsUser(2) by android
I/ActivityManager(  862): Killing 7357:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/Finsky  ( 7504): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/libprocessgroup(  862): failed to open /acct/uid_10011/pid_7357/cgroup.procs: No such file or directory
,E/MDM     ( 1734): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5584): Restart initialization of location
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,D/Finsky  ( 7504): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
D/libc-netbsd( 7504): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7504): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/AudioManager( 7250): getMode name:com.lge.qremote
D/libc-netbsd( 7504): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7504): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
I/AudioManager( 7250): getMode name:com.lge.qremote
I/AudioManager( 7250): getMode name:com.lge.qremote
I/AudioManager( 7250): getMode name:com.lge.qremote
,I/AudioManager( 7250): getMode name:com.lge.qremote
I/ActivityManager(  862): Killing 7381:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  862): failed to open /acct/uid_10051/pid_7381/cgroup.procs: No such file or directory
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out( 7504): propertyValue:false
I/ActivityManager(  862): Killing 6893:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  862): failed to open /acct/uid_10079/pid_6893/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PowerManagerServiceEx(  862): acquireWakeLockInternal: lock=452067486, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=862
,D/WeatherService( 2747): 2 : TimeTick Intent has been received, Time(hour:min:sec) 23:33:0
,D/WeatherService( 2747): 2 : TimeTick Intent And Screen On
D/WeatherService( 2747): 2 : SDK version : 21
W/ActivityManager(  862): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2747): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2747): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2747): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2747): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2747): 2 : This is isUpdating : false
D/WeatherService( 2747): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2747): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2747): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2747): 2 : Fixed theme : optimus
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
D/WeatherReflect( 2747): 2 : Map key string is -2
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
,I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/lim     ( 2747): 2 : time = 23:33
I/WeatherReflect( 2747): Model Name : LG-D722
D/WeatherTheme( 2747): 2 : Different view - status_min_formatted : 32 != 33
D/WeatherTheme( 2747): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2747): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2747): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2747): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2747): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2747): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]DateView( 1374): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/Weather4x2_optimus( 2747): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2747): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2747): forecast size is 0
,D/Theme   ( 2747): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2747): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2747): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2747): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2747): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2747): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2747): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2747): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2747): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2747): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2747): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2747): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2747): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2747): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2747): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2747): url is : null
D/Theme   ( 2747): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2747): EnableTheme(home): com.lge.launcher2.theme.optimus
,D/Theme   ( 2747): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2747): 2 : update view, appWidgetId: 2
D/WeatherService( 2747): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 23:33:0
D/PowerManagerServiceEx(  862): releaseWakeLockInternal: lock=452067486 [*alarm*], flags=0x0
,I/art     ( 6986): CheckpointMarkThreadRoots callback created = 0xb042d3d0
,I/art     ( 6986): CheckpointMarkThreadRoots callback created = 0xb042d3c0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/CheckinRequestBuilder( 5584): Classify the device as Phone.
,D/libc-netbsd( 5584): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5584): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5584): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5584): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 5584): propertyValue:false
D/libc-netbsd( 5584): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5584): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5584): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5584): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5584): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5584): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5584): Sending checkin request (9794 bytes)
,I/CheckinRequestBuilder( 5584): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5584): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5584): Classify the device as Phone.
,I/CheckinTask( 5584): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5584): Checking schedule, now: 1454970781480 next: 1455498030476
I/CheckinService( 5584): active receiver: disabled
,I/CheckinService( 5584): Checking schedule, now: 1454970781509 next: 1455498030476
I/CheckinService( 5584): active receiver: disabled
,D/CheckinService( 5584): Recording last checkin time for package unspecified as 1454970781519
V/SetupWizard( 7126): Connected to Gservices successfully
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/GAV2    ( 7439): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/InputReader(  862): Reconfiguring input devices.  changes=0x00000010
D/administrator(  862): Handling package changes for user 0
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  862): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7644 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 7401): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7401): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7401): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7644): onCreate
,W/AppUp4:DB( 7644):  [AppBoxDatabaseHelper] construct
V/JNIHelp ( 7401): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:DB( 7644):  setFingerPrint start
I/AppUp4:DB( 7644):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7644):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7644):  SDK version = 0
I/AppUp4:DB( 7644):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7644): AppBoxApplication onCreate()
I/NotificationService(  862): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  862): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  862): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  862): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/AppUp4:CustModeStarterReceiver( 7644): onReceive
I/AppUp4:CustModeStarterReceiver( 7644): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7644): Context : android.app.ReceiverRestrictedContext@36d8dbe2
D/AppUp4:CustFacade( 7644): isCustomizationCompleted : false
,W/System  ( 7401): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7401): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  862): Process com.google.android.apps.plus (pid 6986) has died
D/AppUp4:CustFacade( 7644): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7644): begin check event
I/AppUp4:CustModeStarterReceiver( 7644): Event For Nothing, skip.
,V/BackupManagerService(  862): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  862): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@20d8780e
,I/ActivityManager(  862): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7667 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
,W/ResourcesManager(  862): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7667): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7667): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7667): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ActivityManager(  862): Process com.android.vending (pid 7504) has died
,W/ResourceType(  862): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/AppConfig( 7667): Total System Memory = 906309632
,I/GalleryUtils( 7667): Application Heap = 96 MB
I/AppConfig( 7667): App Tier : NOT_DEF
I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/SystemHelper( 7667): region [EU], country [EU], operator [OPEN], sub-operator []
D/LocationProviderProxy(  862): applying state to connected service
,D/UEI.SmartControl( 7485): Internal timer expired: 1
,I/ActivityManager(  862): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7691 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7691): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7691): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7691): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7691): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7691): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7691): BUILD Country: EU
I/SystemConfig( 7691): BUILD Operator: OPEN
,I/ActivityManager(  862): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7713 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  862): Killing 2764:com.lge.music/u0a28 (adj 15): empty #11
,I/SystemConfig( 7691): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7691): existFile = false
I/SystemConfig( 7691): canReadFile = false
I/SystemConfig( 7691): systemFeature RCS result false
,D/SystemConfig( 7691): refreshRcsSupport() :false
V/AudioFlinger(  276): 2764 died, releasing its sessions
V/AudioFlinger(  276):  pid 1753 @ 0
V/AudioFlinger(  276):  pid 3226 @ 1
V/AudioFlinger(  276):  pid 3226 @ 2
I/ActivityManager(  862): Killing 6964:com.android.chrome/u0a48 (adj 15): empty #12
,W/libprocessgroup(  862): failed to open /acct/uid_10028/pid_2764/cgroup.procs: No such file or directory
,W/libprocessgroup(  862): failed to open /acct/uid_10048/pid_6964/cgroup.procs: No such file or directory
,I/LockScreenSettings( 7713): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7713): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7713): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7713): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7713): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7713): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  862): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7734 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  862): Killing 7485:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7250): android.os.DeadObjectException
,W/System.err( 7250): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7250): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7250): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7250): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7250): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7250): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7250): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7250): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7250): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7250): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
,W/System.err( 7250): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7250): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7250): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7250): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7250): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7250): android.os.DeadObjectException
W/System.err( 7250): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7250): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7250): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7250): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7250): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7250): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7250): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7250): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7250): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7250): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7250): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7250): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7250): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7250): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7250): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  862): failed to open /acct/uid_10089/pid_7485/cgroup.procs: No such file or directory
W/ActivityManager(  862): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,W/ResourcesManager( 7734): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  862): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7753 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7753): Quickset Services start...
,I/UEI.SmartControl( 7753): Manufacture = LGE
D/UEI.SmartControl( 7753): File observer start...
E/UEI.SmartControl( 7753): IR Port is disabled: false
D/UEI.SmartControl( 7753): Starting file observer...
D/UEI.SmartControl( 7753): Extracting JNI libs...
D/UEI.SmartControl( 7753): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7753): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7753): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7753): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7753): --- Selecting new region: 2
I/UEI.SmartControl( 7753): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7753): Platform has CIR...
,D/UEI.SmartControl( 7753): NO CIR support, need to check package...
I/UEI.SmartControl( 7753): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7753): QS Service created
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/UEI.SmartControl( 7753): QS start get config
,D/UEI.SmartControl( 7753): Loading JNI Libs...
D/UEI.SmartControl( 7753):  configuring local db...
,I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 46 ms] updated apps [took 46 ms] 
,I/ActivityManager(  862): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7780 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  862): Killing 7439:com.google.android.gm/u0a53 (adj 15): empty #11
,D/UEI.SmartControl( 7753):  ---- Has DB8: true
,D/UEI.SmartControl( 7753): QS start statue = true Error code = 0
D/UEI.SmartControl( 7753): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7753): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7753): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7753): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7753): IrrcClient ++ 
D/irrcClient( 7753): getIrrcService ++ 
D/irrcClient( 7753): getIrrcService -- 
D/irrcClient( 7753): IrrcClient -- 
W/irrc_jni( 7753): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7753): Services init done
,I/UEI.SmartControl( 7753): Device manager: loading config....
,W/libprocessgroup(  862): failed to open /acct/uid_10053/pid_7439/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7753): QS Service init finished
D/UEI.SmartControl( 7753): Config is loaded...
,D/UEI.SmartControl( 7753): QS Service version name: 0.1.73
D/UEI.SmartControl( 7753): QS Service version code: 1073
D/UEI.SmartControl( 7753): Service requested: Control
I/ActivityManager(  862): Killing 7250:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7753): -----IControl: 11
D/UEI.SmartControl( 7753): Caller: com.lge.qremote
D/UEI.SmartControl( 7753): ------------ IControl registerCallback...
I/UEI.SmartControl( 7753): Registering callback...
D/UEI.SmartControl( 7753):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7753): Notify AllClients services are ready: 0
W/libprocessgroup(  862): failed to open /acct/uid_10106/pid_7250/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7753): Internal service binding...
D/Finsky  ( 7780): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/Finsky  ( 7780): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7780): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7780): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7780): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3208): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3208): created cursor android.database.sqlite.SQLiteCursor@28de1f8f on behalf of 7780
,I/art     (  862): Explicit concurrent mark sweep GC freed 29723(1508KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.553ms total 149.248ms
,D/Finsky  ( 7780): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 7780): Skipping gmscore version check
D/Finsky  ( 7780): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7780): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5584): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 7780): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  862): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7828 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/PackageBroadcastService( 5584): Null package name or gms related package.  Ignoreing.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ResourcesManager( 7828): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/Icing   ( 5584): updateResources: need to parse f{com.google.android.gms}
,D/BluetoothManagerService(  862): Message: 20
D/BluetoothManagerService(  862): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@21793bc9:true
,D/BluetoothAdapterService(167692636)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@32340192
D/BluetoothAdapterService(167692636)( 2063): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@32340192
V/LGMDMManager( 7828): Create singleton instance
,I/AudioManager( 7828): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7753): -----IControl: 11
,D/UEI.SmartControl( 7753): Caller: com.lge.qremote
D/UEI.SmartControl( 7753): ------------ IControl registerCallback...
I/UEI.SmartControl( 7753): Registering callback...
D/UEI.SmartControl( 7753): -----IControl: 19
D/UEI.SmartControl( 7753): Caller: com.lge.qremote
I/UEI.SmartControl( 7753): Registering Services Ready callback...
I/UEI.SmartControl( 7753): Notify client services are ready...
D/UEI.SmartControl( 7753): -----IControl: 8
D/UEI.SmartControl( 7753): Caller: com.lge.qremote
,I/AudioManager( 7828): getMode name:com.lge.qremote
I/ActivityManager(  862): Killing 7126:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  862): failed to open /acct/uid_10038/pid_7126/cgroup.procs: No such file or directory
,I/AudioManager( 7828): getMode name:com.lge.qremote
I/AudioManager( 7828): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Icing   ( 5584): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5584): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  862): Killing 7267:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  862): failed to open /acct/uid_10006/pid_7267/cgroup.procs: No such file or directory
,I/ActivityManager(  862): Killing 7401:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  862): failed to open /acct/uid_10061/pid_7401/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/charger_monitor(  481): init target 500000
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,D/charger_monitor(  481): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
,D/WifiController(  862): battery changed pluggedType: 2
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,D/UEI.SmartControl( 7753): Internal timer expired: 1
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  862): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  862): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  862): tsOffsetIs: Apps: 135189444537; DSPS: 4527872; Offset : -2994723431
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  862): ELAPSED_WAKEUP set : Alarm{36467b94 type 2 when 145681 com.google.android.gms} when 145681
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1734): Vacuum at: now=1454970807728 tag=VacuumService
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  862): ALS enabled for SRE
D/PowerManagerServiceEx(  862): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28718 ms ago)
,D/qdlights(  862): set_light_backlight: 253
,D/qdlights(  862): set_light_backlight: 249
,D/qdlights(  862): set_light_backlight: 246
,D/qdlights(  862): set_light_backlight: 243
,D/qdlights(  862): set_light_backlight: 239
,D/qdlights(  862): set_light_backlight: 236
,D/qdlights(  862): set_light_backlight: 233
,D/qdlights(  862): set_light_backlight: 229
,D/qdlights(  862): set_light_backlight: 226
,D/qdlights(  862): set_light_backlight: 223
,D/qdlights(  862): set_light_backlight: 219
,D/qdlights(  862): set_light_backlight: 216
,D/qdlights(  862): set_light_backlight: 213
,D/qdlights(  862): set_light_backlight: 209
,D/qdlights(  862): set_light_backlight: 206
,D/qdlights(  862): set_light_backlight: 203
,D/qdlights(  862): set_light_backlight: 199
,D/qdlights(  862): set_light_backlight: 196
,D/qdlights(  862): set_light_backlight: 193
,D/qdlights(  862): set_light_backlight: 189
,D/qdlights(  862): set_light_backlight: 186
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  862): set_light_backlight: 183
,D/qdlights(  862): set_light_backlight: 179
,D/qdlights(  862): set_light_backlight: 176
,D/qdlights(  862): set_light_backlight: 173
,D/qdlights(  862): set_light_backlight: 169
,D/qdlights(  862): set_light_backlight: 166
,D/qdlights(  862): set_light_backlight: 163
,D/qdlights(  862): set_light_backlight: 159
,D/qdlights(  862): set_light_backlight: 156
,D/qdlights(  862): set_light_backlight: 153
,D/qdlights(  862): set_light_backlight: 149
,D/qdlights(  862): set_light_backlight: 146
,D/qdlights(  862): set_light_backlight: 143
,D/qdlights(  862): set_light_backlight: 139
,D/qdlights(  862): set_light_backlight: 136
,D/qdlights(  862): set_light_backlight: 133
,D/qdlights(  862): set_light_backlight: 129
,D/qdlights(  862): set_light_backlight: 126
,D/qdlights(  862): set_light_backlight: 123
,D/qdlights(  862): set_light_backlight: 119
,D/qdlights(  862): set_light_backlight: 116
,D/qdlights(  862): set_light_backlight: 113
,D/qdlights(  862): set_light_backlight: 109
,D/qdlights(  862): set_light_backlight: 106
,D/qdlights(  862): set_light_backlight: 103
,D/qdlights(  862): set_light_backlight: 99
,D/qdlights(  862): set_light_backlight: 96
,D/qdlights(  862): set_light_backlight: 93
,D/qdlights(  862): set_light_backlight: 89
,D/qdlights(  862): set_light_backlight: 86
,D/qdlights(  862): set_light_backlight: 83
,D/qdlights(  862): set_light_backlight: 79
,D/qdlights(  862): set_light_backlight: 76
,D/qdlights(  862): set_light_backlight: 73
,D/qdlights(  862): set_light_backlight: 69
,D/qdlights(  862): set_light_backlight: 66
,D/qdlights(  862): set_light_backlight: 63
,D/qdlights(  862): set_light_backlight: 59
,D/qdlights(  862): set_light_backlight: 56
,D/qdlights(  862): set_light_backlight: 53
,D/qdlights(  862): set_light_backlight: 49
,D/qdlights(  862): set_light_backlight: 46
,D/qdlights(  862): set_light_backlight: 43
,D/qdlights(  862): set_light_backlight: 39
,D/qdlights(  862): set_light_backlight: 36
,D/qdlights(  862): set_light_backlight: 33
,D/qdlights(  862): set_light_backlight: 29
,D/qdlights(  862): set_light_backlight: 26
,D/qdlights(  862): set_light_backlight: 23
,D/qdlights(  862): set_light_backlight: 19
,D/qdlights(  862): set_light_backlight: 16
,D/qdlights(  862): set_light_backlight: 13
,D/qdlights(  862): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/sensors_hal_Time(  862): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  862): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  862): tsOffsetIs: Apps: 155191373384; DSPS: 5183295; Offset : -2994715342
,I/PowerManagerService(  862): ALS enabled for SRE
D/PowerManagerServiceEx(  862): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35711 ms ago)
I/PowerManagerService(  862): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  862): ALS enabled for SRE
D/PowerManagerServiceEx(  862): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35721 ms ago)
W/ContextImpl(  862): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  862): Sleeping (uid 1000)...
D/LPWGController(  862): [updateScreenState] screen on = false
D/LPWGController(  862): disable proximity sensor
D/LPWGController(  862): enable proximity sensor
,I/SensorManager(  862): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2cb49ff5] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  862): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  862): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  862): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  862): activate: handle is 48, enable
V/sensors_hal_Ctx(  862): activate sensors is 1400000000000
D/sensors_hal_Thresh(  862): enable: handle=48
I/sensors_hal_SAM(  862): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  862): waitForResponse: timeout=1000
V/sensors_hal_SAM(  862): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  862): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  862): enable: Received response: 0
D/PowerManagerServiceEx(  862): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35763 ms ago)
I/Adreno-EGL(  862): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  862): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  862): Build Date: 03/02/15 Mon
I/Adreno-EGL(  862): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  862): Remote Branch: 
I/Adreno-EGL(  862): Local Patches: 
I/Adreno-EGL(  862): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (531 us)
,I/Sensors (  422): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  862): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  862): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  862): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  862): processInd: handle 48, count=1
V/sensors_hal_Thresh(  862): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  862): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  862): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  862): poll: count: 256
I/sensors_hal_Ctx(  862): poll: released wakelock sensor_ind
D/sensors_hal_Util(  862): waitForResponse: timeout=0
D/LPWGController(  862): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  862): current mode = 1  value = 1 1
I/LPWGController(  862): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=0 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/LPWGController(  862): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  862): set_light_backlight: 0
,I/SensorManager(  862): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  862): activate: handle is 46, disable
V/sensors_hal_Ctx(  862): activate sensors is 1000000000000
D/sensors_hal_LP2(  862): enable: handle=46
D/sensors_hal_LP2(  862): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  862): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
I/DisplayManagerService(  862): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  862): Display changed displayId=0
,V/sensors_hal_SAM(  862): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  862): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1753): Display #0 changed.
D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
D/SurfaceControl(  862): Excessive delay in setPowerMode(): 211ms
,I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  862): Got set_interactive hint
D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1374): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1374): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
,D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
D/WifiServerServiceExt(  862): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 862
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
,V/voice   (  276): voice_set_parameters: enter: screen_state=on
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: exit
V/voice   (  276): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  276): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  276): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  276): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  276): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
I/WifiServerServiceExt(  862): set CMD_KT_SCAN_INTERVAL
,D/GpsLocationProvider(  862): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1842): |CORE| sendScreenState: state:true
I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): updateLightsLocked : turn off led
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1806): RESTART MSG
D/SplitWindow(  862): check instance of lgWin Window{2d22c18 u0 SearchPanel}
,I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1806): lockStatus = 0
D/InputDispatcher(  862): Window went away: Window{b56cbf5 u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
,D/LNfcService( 1789): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1789): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1789): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1789): isRequireNfcCRouting() return true
D/LNfcService( 1789): isHCERoutingtoHost() return : true
D/NfcService( 1789): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): newParams.techmask= mTechMask: default
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): screenState= 3
D/NfcService( 1789): Discovery configuration equal, not updating.
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,I/Sensors (  422): sns_pwr.c(301):releasing wakelock
D/Ulp_jni (  862): JNI:system_update. Event-0
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2747): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:33:39
,D/WeatherService( 2747): 2 : ACTION screen on
D/WeatherService( 2747): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2747): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2747): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:33:39
,W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): ACTION_SCREEN_ON
D/AppCleanupService( 4067): android.intent.action.SCREEN_ON
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 862
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: exit
V/voice   (  276): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  276): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  276): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  276): adev_set_parameters: exit with code(0)
D/WifiController(  862): CMD_SCREEN_OFF 
D/WifiController(  862): shouldWifiStayAwake TRUE
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
D/GpsLocationProvider(  862): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:false
,I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1806): clear
I/LEDService( 1806): updateLightsLocked : turn on led
E/LEDService( 1806): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1806): Can't handle this request of patternId:0
D/LEDHandler( 1806): RESTART MSG
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1789): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1789): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1880): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2747): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:33:39
D/WeatherService( 2747): 2 : ACTION screen off
D/WeatherService( 2747): 2 : TimeTick Receiver Unregister
D/WeatherService( 2747): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:33:39
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  862): ACTION_SCREEN_OFF
D/AppCleanupService( 4067): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4067): AppUsageStatsSaveTask
,E/NxpNfcJni( 1789): getReconnectState = 0x0
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
D/LNfcService( 1789): isRequireNfcCRouting() return true
D/LNfcService( 1789): isHCERoutingtoHost() return : true
D/NfcService( 1789): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): newParams.techmask= mTechMask: 0
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): screenState= 1
E/NxpNfcJni( 1789): getReconnectState = 0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  862): ELAPSED_WAKEUP set : Alarm{2f7c4671 type 2 when 161595 com.android.systemui} when 161595
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1753): getCallState : 0
D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
,D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  862): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  862): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  862): tsOffsetIs: Apps: 175192048637; DSPS: 5838677; Offset : -2994711997
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  862): acquireWakeLockInternal: lock=452067486, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=862
,V/AlarmManager(  862): ELAPSED_WAKEUP set : Alarm{1c69c56 type 2 when 183273 android} when 183273
D/PowerManagerServiceEx(  862): releaseWakeLockInternal: lock=452067486 [*alarm*], flags=0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
,D/charger_monitor(  481): init target 500000
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  862): battery changed pluggedType: 2
V/AlarmManager(  862): ELAPSED_WAKEUP set : Alarm{5b6f4d7 type 2 when 187695 com.google.android.gms} when 187695
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 46696(2MB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 14MB/23MB, paused 12.697ms total 170.874ms
,I/PhenotypeConfigurator( 1734): Scheduling Phenotype for one-off execution 12277 seconds from now (1454970850050)
D/GetConfigurationSnapshotOperation( 1734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  862): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/LocationManagerService(  862): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  862): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  862): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  862): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  862): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  862): tsOffsetIs: Apps: 195192814411; DSPS: 6494062; Offset : -2994709057
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  862): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  862): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  862): tsOffsetIs: Apps: 215193566956; DSPS: 7149447; Offset : -2994719635
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  862): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  862): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  862): tsOffsetIs: Apps: 235194237416; DSPS: 7804829; Offset : -2994720536
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  481): init target 500000
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  862): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  862): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  862): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  862): tsOffsetIs: Apps: 255194916992; DSPS: 8460211; Offset : -2994711877
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  862): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  862): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  862): tsOffsetIs: Apps: 275195691151; DSPS: 9115596; Offset : -2994701074
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  862): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  862): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  862): tsOffsetIs: Apps: 295196389945; DSPS: 9770979; Offset : -2994704107
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  862): battery changed pluggedType: 2
D/HeadsetStateMachine( 2063): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  862): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  862): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  862): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5526): --= Surplus to requirements =--
I/jxcore-log( 5526): 
I/jxcore-log( 5526): ****TEST TOOK:  ms ****
I/jxcore-log( 5526): 
I/jxcore-log( 5526): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5526): 
,D/AndroidRuntime( 8038): 
D/AndroidRuntime( 8038): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8038): CheckJNI is OFF
,D/AndroidRuntime( 8038): Calling main entry com.android.commands.pm.Pm
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ActivityManager(  862): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  862): Killing 5526:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,W/PackageSettings(  862): Skipping PackageSetting{2b295bc2 com.example.hello/10317} due to missing metadata
,I/WindowState(  862): WIN DEATH: Window{2caea62b u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  862): Focus left window: Window{2caea62b u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  862): Window went away: Window{2caea62b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  862):   Force finishing activity ActivityRecord{fdb6c36 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  862): Display changed displayId=0
D/DSDPConnection( 1753): Display #0 changed.
,W/ActivityManager(  862): Spurious death for ProcessRecord{3b48c1c7 5526:com.test.thalitest/u0a316}, curProc for 5526: null
,I/ActivityManager(  862): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,I/[LGHome]EVENT( 1880): [Launcher.java:5203:onStart()]onStart
,I/[LGHome]EVENT( 1880): [Launcher.java:776:onResume()]onResume
,D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  862): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3605): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
W/System.err( 3605): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3605): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3605): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3605): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3605): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3605): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3605): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3605): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3605): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3605): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3605): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/art     ( 1941): Explicit concurrent mark sweep GC freed 22601(1338KB) AllocSpace objects, 5(119KB) LOS objects, 39% free, 12MB/21MB, paused 7.706ms total 162.428ms
,I/ActivityManager(  862): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8071 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     ( 5584): Explicit concurrent mark sweep GC freed 6325(318KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 13MB/18MB, paused 863us total 159.578ms
I/[LGHome]EVENT( 1880): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
,W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]LGActivityUtil( 1880): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
I/art     (  862): Explicit concurrent mark sweep GC freed 49065(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 3.824ms total 220.724ms
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1880): [Launcher.java:929:onResume()]onResume end
I/art     (  862): WaitForGcToComplete blocked for 21.069ms for cause Explicit
I/Activity( 1880): Activity.onPostResume() called 
,W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
,W/[LGHome]LGWallpaperInfo( 1880): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1880): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1374): handleShortcutListChanged...
,I/SystemUI[Framework](  862): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourcesManager( 8071): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8071): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8071): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/PhoneWindowManagerEx(  862): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  862): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  862): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  862): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@ffc345c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  862): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  862): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
D/InputDispatcher(  862): Focus entered window: Window{26df2e93 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  862): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  862): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  862): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  862): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@ffc345c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  862): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/administrator(  862): Handling package changes for user 0
,D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1374): handleShortcutListChanged...
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
,I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1880): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  862): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  862): Got RemoteException sending setActive(false) notification to pid 5526 uid 10316
,I/LGEmail ( 8071): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8071): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  862): Timeline: Activity_windows_visible id: ActivityRecord{fdc2944 u0 com.lge.launcher2/.Launcher t221} time:305758
,I/art     (  862): Explicit concurrent mark sweep GC freed 8838(517KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 5.846ms total 338.532ms
W/IInputConnectionWrapper( 1880): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1616): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/NotificationService(  862): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  862): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  862): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1880): getTextAfterCursor on inactive InputConnection
D/TaskPersister(  862): removeObsoleteFile: deleting file=222_task.xml
,D/PhoneStatusBar( 1374): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
D/AndroidRuntime( 8038): Shutting down VM
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/PackageChangeReceiver( 8071): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/AppUp4:PreloadHelper( 7644): added Exclude : com.test.thalitest
,W/ResourcesManager(  862): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  862): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8097 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  862): Killing 7667:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/ResourceType(  862): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/libprocessgroup(  862): failed to open /acct/uid_10023/pid_7667/cgroup.procs: No such file or directory
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 8097): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8097): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8097): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8097): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 8097): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/SQLiteDatabase( 8097): Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
E/SQLiteDatabase( 8097): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8097): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8097): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8097): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8097): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8097): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8097): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8097): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8097): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8097): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8097): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 8097): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8097): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8097): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8097): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/SQLiteDatabase( 8097): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 8097): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 8097): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 8097): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 8097): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 8097): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 8097): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8097): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8097): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8097): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8097): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8097): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8097): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8097): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/AndroidRuntime( 8097): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 8097): FATAL EXCEPTION: main
E/AndroidRuntime( 8097): Process: com.android.settings, PID: 8097
E/AndroidRuntime( 8097): java.lang.RuntimeException: Unable to get provider com.android.settings.vibratecreation.VibrateUserPatternProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8097): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 8097): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 8097): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/,AndroidRuntime( 8097): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 8097): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 8097): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8097): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8097): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 8097): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8097): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8097): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 8097): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 8097): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8097): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8097): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 8097): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 8097): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 8097): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 8097): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8097): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 8097): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 8097): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 8097): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 8097): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 8097): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8097): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8097): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/AndroidRuntime( 8097): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 8097): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 8097): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 8097): 	... 11 more
,I/Process ( 8097): Sending signal. PID: 8097 SIG: 9
,E/DropBoxManagerService(  862): Can't write: system_app_crash
E/DropBoxManagerService(  862): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  862): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  862): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  862): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  862): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  862): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  862): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
E/DropBoxManagerService(  862): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  862): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  862): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  862): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  862): 	... 5 more
E/SharedPreferencesImpl( 1880): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak

```
