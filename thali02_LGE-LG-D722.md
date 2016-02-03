#### Test 58135655c662d33_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 82 ms] updated apps [took 82 ms] 
,D/Finsky  ( 5547): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/Finsky  ( 5547): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 5547): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5547): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5547): com.android.vending: cancel(-1050172287) by com.android.vending
D/AndroidRuntime( 5574): 
D/AndroidRuntime( 5574): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5574): CheckJNI is OFF
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@34373616 on behalf of 5547
I/art     ( 3969): Explicit concurrent mark sweep GC freed 9376(460KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 418us total 36.760ms
I/NotificationManager( 5547): com.android.vending: cancel(1003285959) by com.android.vending
D/Ads     ( 5547): Skipping gmscore version check
D/Finsky  ( 5547): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5547): [1] Libraries$2.run: Finished loading 1 libraries.
--------- beginning of system
I/ActivityManager(  838): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5614 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1367): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1367): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1367): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/Finsky  ( 5547): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1367): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1367): onReceive = android.intent.action.BATTERY_CHANGED
W/MainApplication( 5203): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/Finsky  ( 5547): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1367): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1367): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
W/MainApplication( 5203): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/Finsky  ( 5547): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  838): Killing 5353:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/ResourcesManager( 5614): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5614): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  838): failed to open /acct/uid_10011/pid_5353/cgroup.procs: No such file or directory
I/MultiDex( 5614): VM with version 2.1.0 has multidex support
I/MultiDex( 5614): install
I/MultiDex( 5614): VM has multidex support, MultiDex support library is disabled.
D/AndroidRuntime( 5574): Calling main entry com.android.commands.am.Am
I/ActivityManager(  838): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ActivityManager(  838): setTaskToReturnTo : TaskRecord{21c97096 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  838): setTaskToReturnTo : TaskRecord{21c97096 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  838): AppWindowTokenEx init.. 
D/ContextHelper(  838): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  838): Focus left window: Window{399b8aa4 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5574): Shutting down VM
I/[LGHome]EVENT( 1873): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  838): check instance of lgWin Window{30aa2f0f u0 Starting com.test.thalitest}
I/ActivityManager(  838): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5642 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1873): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1873): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1935): Closing mic
I/WindowStateAnimator(  838): Starting window displayed
I/MicrophoneInputStream( 1935): mic_close com.google.android.apps.gsa.speech.audio.u@3f608a36
V/AudioRecord( 1935): stop()
D/AudioRecord( 1935): AudioRecord->stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
I/SystemUI[Framework](  838): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1367): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  838): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  838): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  838): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@e6fa2b1,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  838): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioFlinger(  278): Record stopped OK
I/[SystemUI]NavigationThemeResource( 1367): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1367):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1367): , Keyguard show=false, IME shown=false, Panel expanded=false
V/AudioPolicyManager(  278): stopInput() input 16
V/AudioPolicyService(  278): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  278): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  278): releaseAudioPatch handle 17
D/BarTransitions( 1367): draw background and invalidate : color = b000000
,D/audio_hw_primary(  278): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/AudioFlinger::PatchPanel(  278): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  278): ThreadBase::setParameters() routing=0
D/BarTransitions( 1367): draw background and invalidate : color = b0b0b0b
V/audio_hw_primary(  278): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  278): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  278): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  278): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  278): disable_audio_route: exit
E/audio_hw_primary(  278): disable_snd_device: enter 144
D/hardware_info(  278): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  278): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  278): stop_input_stream: exit: status(0)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb381d000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioPolicyManager(  278): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  278): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  278): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  278): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioPolicyService(  278): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  278): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  278): setParameters(): io 16, keyvalue hotword_active=0, calling pid 278
V/AudioFlinger(  278): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  278): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  278): in_set_parameters: exit: status(0)
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb381d000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioRecord( 1935): stop()
V/AudioRecord( 1935): stop()
V/AudioRecord( 1935): stop()
V/AudioFlinger(  278): releasing 15 from 1935 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioPolicyManager(  278): releaseInput() 16
V/AudioPolicyManager(  278): closeInput(16)
V/AudioFlinger(  278): closeInput() 16
V/AudioSystem(  278): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1367): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  838): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1748): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1935): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1987): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  278): ThreadBase::exit
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioSystem( 2703): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  278): RecordThread 0xb381d000 exiting
D/audio_hw_primary(  278): adev_close_input_stream: enter:stream_handle(0xb546e240)
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioSystem( 3260): ioConfigChanged() event 4, ioHandle 16
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioPolicyManager(  278): releaseInput() exit
V/AudioFlinger(  278): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  278): removeClient_l() pid 1935, calling pid 278
I/HotwordRecognitionRnr( 1935): Stopping hotword detection.
I/HotwordRecognitionRnr( 1935): Hotword detection finished
V/JNIHelp ( 5614): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ContextHelper( 5642): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
W/ActivityThread( 5614): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5614): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@228d1a11: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5614): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5614): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5614): com.google.android.gms: cancel(39789) by com.google.android.gms
I/WebViewFactory( 5642): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/ChimeraCfgMgr( 5614): Reading stored module config
D/PackageBroadcastService( 5614): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/LibraryLoader( 5642): Time to load native libraries: 2 ms (timestamps 3067-3069)
I/LibraryLoader( 5642): Expected native library version number "",actual native library version number ""
D/ChimeraCfgMgr( 5614): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5614): Loading module APK com.google.android.play.games
V/WebViewChromiumFactoryProvider( 5642): Binding Chromium to main looper Looper (main, tid 1) {3b0d3b19}
I/LibraryLoader( 5642): Expected native library version number "",actual native library version number ""
I/chromium( 5642): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5642): Initializing chromium process, singleProcess=true
W/art     ( 5642): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5642): ApplicationContext is null in ApplicationStatus
W/chromium( 5642): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5642): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5642): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5642): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5642): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5642): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5642): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5642): Remote Branch: 
I/Adreno-EGL( 5642): Local Patches: 
I/Adreno-EGL( 5642): Reconstruct Branch: 
D/NativeLibraryUtils( 5614): Install completed successfully. count=14 extracted=0
,V/AudioPolicyService(  278): registerClient() client 0xb39acca0, uid 10316
,D/BluetoothManagerService(  838): Message: 20
,D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c55ee91:true
D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/art     ( 5614): CheckpointMarkThreadRoots callback created = 0xb042d4a0
I/art     ( 5614): CheckpointMarkThreadRoots callback created = 0xb042d490
,W/art     ( 5642): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5642): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5642): CordovaWebView is running on device made by: LGE
,W/art     ( 5642): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5642): Attempt to remove local handle scope entry from IRT, ignoring
,D/ChimeraCfgMgr( 5614): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5614): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 5614): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/Activity( 5642): Activity.onPostResume() called 
,D/OpenGLRenderer( 5642): Render dirty regions requested: true
I/OpenGLRenderer( 5642): Initialized EGL, version 1.4
D/OpenGLRenderer( 5642): Enabling debug mode 0
,D/AsyncTaskServiceImpl( 5614): Submit a task: k
,D/Atlas   ( 5642): Validating map...
D/ChimeraCfgMgr( 5614): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/SplitWindow(  838): check instance of lgWin Window{3db97ee7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5642): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/PeopleDatabaseHelper( 5614): cleanUpNonGplusAccounts done.
D/ChimeraCfgMgr( 5614): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/Icing   ( 5614): Storage manager: low false usage 1.68MB avail 2.37GB capacity 4.06GB
,D/InputDispatcher(  838): Focus entered window: Window{3db97ee7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/k       ( 5614): Processing package: com.test.thalitest
,D/GassUtils( 5614): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5614): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 5614): Using Auth Proxy for data requests.
,W/InputMethodManagerService(  838): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  838): Displayed com.test.thalitest/.MainActivity: +1s294ms
,I/Timeline(  838): Timeline: Activity_windows_visible id: ActivityRecord{2d16d417 u0 com.test.thalitest/.MainActivity t222} time:83907
I/art     ( 5614): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5614): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/BaseAppContext( 5614): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/Timeline( 5642): Timeline: Activity_idle id: android.os.BinderProxy@1beff0bc time:83946
W/BaseAppContext( 5614): Using Auth Proxy for data requests.
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5614): Restart initialization of location
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/BindingManager( 5642): Cannot call determinedVisibility() - never saw a connection for the pid: 5642
W/BaseAppContext( 5614): Using Auth Proxy for data requests.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,W/BaseAppContext( 5614): Using Auth Proxy for data requests.
,W/BaseAppContext( 5614): Using Auth Proxy for data requests.
,W/BaseAppContext( 5614): Using Auth Proxy for data requests.
I/ActivityManager(  838): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5741 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 22.632ms
,W/BaseAppContext( 5614): Using Auth Proxy for data requests.
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 21.207ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.400ms
,D/JsMessageQueue( 5642): Set native->JS mode to OnlineEventsBridgeMode
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
W/IcingInternalCorpora( 5614): getNumBytesRead when not calculated.
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Icing   ( 5614): updateResources: need to parse f{com.google.android.gms}
,I/Gmail   ( 5741): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5741): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/jxcore_app_log( 5642): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426127360
,W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5741): Error finding the version of the Email provider.....
E/Gmail   ( 5741): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5741): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5741): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5741): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5741): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5741): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5741): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5741): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5741): We do not support migrating this version of the Email provider.
,I/chromium( 5642): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Gmail   ( 5741): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  838): Killing 5370:com.android.gallery3d/u0a23 (adj 15): empty #11
I/art     ( 5642): CheckpointMarkThreadRoots callback created = 0x9fa8b500
,D/ChimeraCfgMgr( 5614): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5614): Module APK com.google.android.play.games already loaded
W/libprocessgroup(  838): failed to open /acct/uid_10023/pid_5370/cgroup.procs: No such file or directory
W/ActivityManager(  838): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/art     ( 5642): CheckpointMarkThreadRoots callback created = 0x9fa8b4e0
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,I/Gmail   ( 5741): Observing account changes for notifications
,W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@3900eb97 on behalf of 5614
,W/InstanceID/Rpc( 5614): Found 10006
,I/art     ( 3969): Explicit concurrent mark sweep GC freed 3195(125KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.191ms total 48.196ms
,I/ActivityManager(  838): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5792 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
D/InitAlarmsService( 3811): Clearing and rescheduling alarms.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@1af68184 on behalf of 5614
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@6838d6d on behalf of 5614
I/Gmail   ( 5741): notifyAccountChanged
,D/CalendarProvider2( 5481): Scheduling check of next Alarm
,D/CalendarProvider2( 5481): SCHEDULE_ALARM_REMOVE
I/Gmail   ( 5741): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5741): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Icing   ( 5614): Internal init done: storage state 0
,I/NotificationManager( 5614): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 30588(1843KB) AllocSpace objects, 16(256KB) LOS objects, 40% free, 13MB/22MB, paused 1.277ms total 116.726ms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5741): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     (  838): Explicit concurrent mark sweep GC freed 33888(1641KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 12.925ms total 232.771ms
I/Icing   ( 5614): Post-init done
,I/Gmail   ( 5741): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5741): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PhoneMonitor( 5792): Register our PhoneStateListener
,I/ActivityManager(  838): Killing 3811:com.android.calendar/u0a13 (adj 15): empty #11
,D/PhoneMonitor( 5792): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5792): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5792): [parse] Load xml
,V/TelephonyAutoProfiling( 5792): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5792): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 5792): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  838): failed to open /acct/uid_10013/pid_3811/cgroup.procs: No such file or directory
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Gmail   ( 5741): getAccountsCursor
I/CheckinService( 5614): Checkin interval check for package: unspecified last checkin: 1454523122378 min interval config: 0 actual interval: 5927
,I/CheckinService( 5614): Disabling old GoogleServicesFramework version
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 5614): Checking schedule, now: 1454523128398 next: 1454523152336
I/CheckinService( 5614): active receiver: disabled
,I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5822 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5822): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5481): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5481): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/Babel_SMS( 5822): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5822): MmsConfig.loadMmsSettings
I/Babel_SMS( 5822): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5822): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5822): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5822): MmsConfig.loadFromResources
E/Babel_SMS( 5822): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5822): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/art     ( 5822): Suspending all threads took: 5.046ms
,I/art     ( 5822): CheckpointMarkThreadRoots callback created = 0xb042d810
,I/Icing   ( 5614): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/SensorManager( 5822): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5822): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5822): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5822): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5822): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5822): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5822): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5822): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5822): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5822): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5822): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5822): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5822): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5822): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5822): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5822): found sensor: Motion Accel, handle=46
I/art     ( 5822): CheckpointMarkThreadRoots callback created = 0xb042d7f0
,I/ActivityManager(  838): Process com.lge.bnr (pid 5203) has died
,W/Settings( 5822): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5822): startup - clean
D/Icing   ( 5614): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 5614): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/Babel   ( 5822): deleted: false for 0
,W/jxcore-log( 5642): Initializing JXcore engine
,W/jxcore-log( 5642): JXcore engine is ready
W/AudioCapabilities( 5822): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5822): Unsupported mime audio/adpcm
W/AudioCapabilities( 5822): Unsupported mime audio/g726
W/AudioCapabilities( 5822): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5822): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5822): Unsupported mime video/mjpg
W/VideoCapabilities( 5822): Unsupported mime video/theora
W/Thread-676( 5772): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6259]" dev="sockfs" ino=6259 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/AudioCapabilities( 5822): Unsupported mime audio/evrc
,W/Thread-676( 5772): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6259]" dev="sockfs" ino=6259 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-676( 5772): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-676( 5772): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5817]" dev="sockfs" ino=5817 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/AudioCapabilities( 5822): Unsupported mime audio/qcelp
W/Thread-676( 5772): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-676( 5772): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-676( 5772): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26321]" dev="sockfs" ino=26321 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/VideoCapabilities( 5822): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5822): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5822): Unsupported mime audio/qcelp
W/AudioCapabilities( 5822): Unsupported mime audio/evrc
W/jxcore-log( 5642): Starting JXcore engine
,W/VideoCapabilities( 5822): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5822): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5822): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5822): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5822): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5822): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5822): onServiceConnected
,W/Babel   ( 5822): Attempted to change video mute state without an active call.
I/NotificationManager( 5822): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5822): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5822): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/jxcore-log( 5642): Platform android
W/jxcore-log( 5642): 
W/jxcore-log( 5642): Process ARCH arm
W/jxcore-log( 5642): 
,V/JNIHelp ( 5822): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5863 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5120): getMode name:com.lge.qremote
,I/AudioManager( 5120): getMode name:com.lge.qremote
W/System  ( 5822): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5822): Installed default security provider GmsCore_OpenSSL
,I/AudioManager( 5120): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5863): Quickset Services start...
,I/UEI.SmartControl( 5863): Manufacture = LGE
I/AudioManager( 5120): getMode name:com.lge.qremote
D/UEI.SmartControl( 5863): File observer start...
E/UEI.SmartControl( 5863): IR Port is disabled: false
D/UEI.SmartControl( 5863): Starting file observer...
D/UEI.SmartControl( 5863): Extracting JNI libs...
D/UEI.SmartControl( 5863): --- this system supports 32-bit or 64-bit only
I/AudioManager( 5120): getMode name:com.lge.qremote
E/MDM     ( 1730): [83] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5614): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5120): getMode name:com.lge.qremote
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
I/AudioManager( 5120): getMode name:com.lge.qremote
,I/NotificationManager( 5822): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5889 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,V/AlarmManager(  838): RTC_WAKEUP set : Alarm{1d54769b type 0 when 1454523130140 com.google.android.googlequicksearchbox} when 1454523130140
,I/AppUp4:AppBoxCP( 5889): onCreate
,D/UEI.SmartControl( 5863): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5863): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5863): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,W/AppUp4:DB( 5889):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 5889):  setFingerPrint start
I/AppUp4:DB( 5889):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/UEI.SmartControl( 5863): --- Selecting new region: 2
I/UEI.SmartControl( 5863): -- Running on KitKat(19) and above! JNI will be used.
I/AppUp4:DB( 5889):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5889):  SDK version = 0
I/AppUp4:DB( 5889):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5889): AppBoxApplication onCreate()
,D/UEI.SmartControl( 5863): Platform has CIR...
D/UEI.SmartControl( 5863): NO CIR support, need to check package...
I/UEI.SmartControl( 5863): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5863): QS Service created
I/AppUp4:CustModeStarterReceiver( 5889): onReceive
I/AppUp4:CustModeStarterReceiver( 5889): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5889): Context : android.app.ReceiverRestrictedContext@385a3e63
D/AppUp4:CustFacade( 5889): isCustomizationCompleted : false
E/UEI.SmartControl( 5863): QS start get config
D/AppUp4:CustFacade( 5889): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5889): begin check event
I/AppUp4:CustModeStarterReceiver( 5889): Event For Nothing, skip.
I/ActivityManager(  838): Killing 5392:com.android.contacts/u0a18 (adj 15): empty #11
D/UEI.SmartControl( 5863): Loading JNI Libs...
,D/UEI.SmartControl( 5863):  configuring local db...
I/jxcore-log( 5642): JXcore Cordova bridge is ready!
I/jxcore-log( 5642): 
,W/jxcore-log( 5642): JXcore engine is started
W/libprocessgroup(  838): failed to open /acct/uid_10018/pid_5392/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5912 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5912): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5912): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5912): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5863):  ---- Has DB8: true
,D/UEI.SmartControl( 5863): QS start statue = true Error code = 0
D/UEI.SmartControl( 5863): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5863): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5863): IRRCDataComm has AudioManager!!!!.
,I/jxcore-log( 5642): Toggling radios to true
I/jxcore-log( 5642): 
W/irrc_jni( 5863): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5863): IrrcClient ++ 
,D/irrcClient( 5863): getIrrcService ++ 
D/irrcClient( 5863): getIrrcService -- 
D/irrcClient( 5863): IrrcClient -- 
W/irrc_jni( 5863): IRRCPlayer_nativeInit -- 
D/BluetoothAdapter( 5642): enable(): BT is already enabled..!
D/UEI.SmartControl( 5863): Services init done
D/WifiServiceImplEx(  838): setWifiEnabled: true pid=5642, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/UEI.SmartControl( 5863): QS Service init finished
D/UEI.SmartControl( 5863): QS Service version name: 0.1.73
D/UEI.SmartControl( 5863): QS Service version code: 1073
D/UEI.SmartControl( 5863): Service requested: Control
D/WifiService(  838): setWifiEnabled: true pid=5642, uid=10316
I/UEI.SmartControl( 5863): Device manager: loading config....
D/WifiServiceImplEx(  838): disconnect pid=5642, uid=10316, packageName=com.test.thalitest
D/UEI.SmartControl( 5863): Config is loaded...
,D/WifiServiceImplEx(  838): reconnect pid=5642, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5642): Radios toggled
I/jxcore-log( 5642): 
I/jxcore-log( 5642): My device name is: LGE-LG-D722
I/jxcore-log( 5642): 
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2754): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/UEI.SmartControl( 5863):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5863): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5863): Request IControl service: devices are loaded...
,I/wpa_supplicant( 2754): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
D/UEI.SmartControl( 5863): Internal service binding...
E/WifiStateMachine(  838): WifiStateMachine: Leaving Connected state
D/UEI.SmartControl( 5863): -----IControl: 11
D/UEI.SmartControl( 5863): Caller: com.lge.qremote
D/UEI.SmartControl( 5863): ------------ IControl registerCallback...
D/WfdsMonitor( 1800): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/UEI.SmartControl( 5863): Registering callback...
D/UEI.SmartControl( 5863): -----IControl: 19
E/WifiConfigStore(  838): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/UEI.SmartControl( 5863): Caller: com.lge.qremote
I/UEI.SmartControl( 5863): Registering Services Ready callback...
I/UEI.SmartControl( 5863): Notify client services are ready...
,D/UEI.SmartControl( 5863): -----IControl: 8
D/UEI.SmartControl( 5863): Caller: com.lge.qremote
I/ActivityManager(  838): Killing 5429:com.lge.eula/1000 (adj 15): empty #11
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,D/LGWifiP2pService(  838): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  838): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  274): Clearing all IP addresses on wlan0
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1730): Read error: ssl=0xb045b600: I/O error during system call, Connection timed out
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/NativeCrypto( 1730): SSL shutdown failed: ssl=0xb045b600: I/O error during system call, Broken pipe
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService(  838): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): ValidatedState{ when=-4ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=-7ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Forcing reevaluation
,D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  838): Killing 5412:com.lge.lockscreensettings/u0a69 (adj 15): empty #12
D/ConnectivityService(  838): Default network via Wi-Fi disconnect. stop DSQN
,D/DSQN    (  838): disableDataServiceNotify
D/DSQN    (  838): stop dsqn bin
D/ConnectivityService(  838): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  838): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1367): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  838): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  838): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_5429/cgroup.procs: No such file or directory
,W/libprocessgroup(  838): failed to open /acct/uid_10069/pid_5412/cgroup.procs: No such file or directory
E/WifiStateMachine(  838): Start Disconnecting Watchdog 1
D/ConnectivityService(  838): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiHS20(  838): hidePasspointNotification off =false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/NetworkPolicy(  838): [LG_RESTRICTED] !!!isConnected  type  :1
D/LGWifiP2pService(  838): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  838): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  838): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  838): [LG_RESTRICTED] !!!isConnected  type  :1
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,D/DhcpStateMachine(  838): StoppedState
D/WifiHS20(  838): hidePasspointNotification off =false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/Tethering(  838): MasterInitialState.processMessage what=3
D/Tethering(  838): MasterInitialState.processMessage what=3
I/wpa_supplicant( 2754): wlan0: CTRL-EVENT-SCAN-STARTED 
D/DhcpStateMachine(  838): StoppedState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyNetworkFactory-1( 1748): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:11.028 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/NetworkManagementService(  838): Removing idletimer
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:11.029 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/WifiHS20(  838): hidePasspointNotification off =false
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = -1
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:11.036 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  838): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
D/WifiNetworkAgent(  838): NetworkAgent: NetworkAgent channel lost
I/AppConfig( 5912): Total System Memory = 906309632
I/GalleryUtils( 5912): Application Heap = 96 MB
D/TelephonyIcons( 1367): null signal icon name: drawable/stat_sys_signal_null
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/AppConfig( 5912): App Tier : NOT_DEF
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:11.063 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  838): hidePasspointNotification off =false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]LGNetworkController( 1367): updateLGTelephonySignalStrength : !hasService()
D/WIFI    (  838): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:11.068 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
D/SystemHelper( 5912): region [EU], country [EU], operator [OPEN], sub-operator []
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateSCANNING
D/TelephonyIcons( 1367): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1367): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/ActivityManager(  838): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5940 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  838): Killing 5448:com.google.android.apps.docs/u0a58 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10058/pid_5448/cgroup.procs: No such file or directory
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{1179e177 type 2 when 88929 com.google.android.gms} when 88929
W/ResourcesManager( 5940): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5940): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5940): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5940): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5940): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5940): BUILD Country: EU
I/SystemConfig( 5940): BUILD Operator: OPEN
,I/ActivityManager(  838): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5962 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  838): Killing 5518:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10086/pid_5518/cgroup.procs: No such file or directory
,I/SystemConfig( 5940): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5940): existFile = false
I/SystemConfig( 5940): canReadFile = false
I/SystemConfig( 5940): systemFeature RCS result false
D/SystemConfig( 5940): refreshRcsSupport() :false
I/LockScreenSettings( 5962): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5962): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5962): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5962): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5962): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5962): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  838): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5979 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  838): Killing 5547:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10036/pid_5547/cgroup.procs: No such file or directory
,W/ResourcesManager( 5979): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2754): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/ActivityManager(  838): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6004 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  838): onReceive
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:12.201 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateASSOCIATING
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:12.21 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2754): wlan0: Associated with c0:ff:d4:d3:aa:48
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
,D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateASSOCIATED
I/ActivityManager(  838): Killing 5741:com.google.android.gm/u0a53 (adj 15): empty #11
I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 127 ms] updated apps [took 127 ms] 
,I/wpa_supplicant( 2754): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2754): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:12.332 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/libprocessgroup(  838): failed to open /acct/uid_10053/pid_5741/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:12.343 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/WifiServiceExtension(  838): setVHTCapabilityType  : false
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/WifiServerServiceExt(  838): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  838): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,I/WifiServiceExtension(  838): setSecurityType  : 2
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:12.385 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:12.391 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
D/ConnectivityService(  838): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: ,null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  838): Got NetworkAgent Messenger
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  838): NetworkAgent connected
,D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
E/WifiConfigStore(  838): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]QPairHandler( 1367): onReceive = android.intent.action.PACKAGE_CHANGED
,E/WifiConfigStore(  838): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 9
I/[SystemUI]QSlideListController( 1367): onReceive = android.intent.action.PACKAGE_CHANGED
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
E/WifiStateMachine(  838): Start Dhcp Watchdog 2
D/DhcpStateMachine(  838): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  838): WaitBeforeStartState
I/InputReader(  838): Reconfiguring input devices.  changes=0x00000010
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,W/[SystemUI]QSlideLoader( 1367): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1367): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  838): Handling package changes for user 0
E/WifiStateMachine(  838): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  838): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  838): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1741a8dd target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@1741a8dd target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  838): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  838): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/DhcpStateMachine(  838): DHCP Start wake lock is acquired.
D/CommandListener(  274): Setting iface cfg
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
D/CommandListener(  274): Trying to bring up wlan0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/LgDhcpStateMachineHelper(  838): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  838): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,D/ConnectivityService(  838): ignoring duplicate network state non-change
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:12.664 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:12.667 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
,I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  838): Adding iface wlan0 to network 101
E/WifiStateMachine(  838): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:12.688 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:12.691 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/ConnectivityService(  838): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  838): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
E/Netd    (  274): netlink response contains error (File exists)
D/ConnectivityService(  838): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx,; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  838): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  838): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  838): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  838): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  838): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  838): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  838):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Connected
D/ConnectivityService(  838):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  838):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  838): currentScore = 0, newScore = 20
D/ConnectivityService(  838):    accepting network in place of null
D/ConnectivityService(  838): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  838): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/TelephonyNetworkFactory-1( 1748): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/CSLegacyTypeTracker(  838): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  838): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  838): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  838): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/ConnectivityService(  838): validation of new default Network = false
D/ConnectivityService(  838): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  838): enableDataServiceNotify 
D/DSQN    (  838): start dsqn bin
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] Start DNSResolver start to wait
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] wait 500ms before dns check
,V/NetworkPolicy(  838): [LG_RESTRICTED] checkMobilePolicy_type()
I/CheckinService( 5614): Checkin interval check for package: unspecified last checkin: 1454523122378 min interval config: 0 actual interval: 10369
I/CheckinService( 5614): Checking schedule, now: 1454523132763 next: 1454523152336
I/CheckinService( 5614): active receiver: disabled
D/TelephonyIcons( 1367): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1367): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/DhcpStateMachine(  838): DHCPV4 request on wlan0
D/ConnectivityService(  838): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
V/LgDhcpStateMachineHelper(  838): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  838): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/ConnectivityService(  838): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1367): CM callback handler got msg 524290
I/DSQN    ( 6032): DSQN samuel.seo ver 141203
E/DSQN    ( 6032): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6032): created command queue thread
I/DSQN    ( 6032): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6032): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/dhcpcd  ( 6033): version 5.5.6 starting
E/dhcpcd  ( 6033): get_duid: Read-only file system
I/ActivityManager(  838): Process com.google.process.gapps (pid 3969) has died
,I/dhcpcd  ( 6033): wlan0: rebinding lease of 192.168.1.134
,I/ActivityManager(  838): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6042 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{1e73216a type 2 when 90548 com.android.providers.calendar} when 90548
,I/NotificationService(  838): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  838): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  838): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  838): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateGROUP_HANDSHAKE
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateCOMPLETED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20(  838): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  838): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Tethering(  838): MasterInitialState.processMessage what=3
,D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
V/BackupManagerService(  838): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  838): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@9d79cca
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
W/ResourcesManager(  838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
,I/GservicesProvider( 6042): Gservices pushing to system: true; secure/global: true
,W/ResourceType(  838): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/GoogleHttpClient( 6042): GMS http client unavailable, use old client
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] DNSResolver start dns
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/GoogleHttpClient( 6042): GMS http client unavailable, use old client
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out(  838): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6032): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6032): restart monitoring
D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6032): dsqn report finish
D/DSQN    (  838): DSQM DsqnNotification wlan0  1
D/DSQN    (  838): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 03 Feb 2016 18:12:13 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454523133444], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454523133424]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Validated
D/ConnectivityService(  838): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  838): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  838):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  838):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  838): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  838): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  838): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  838): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1367): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1748): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  838): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  838): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1367): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1367): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/art     (  838): Explicit concurrent mark sweep GC freed 71639(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.652ms total 239.739ms
,D/LocationProviderProxy(  838): applying state to connected service
,D/Finsky  ( 6004): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/ConnectivityService(  838): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/Finsky  ( 6004): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6004): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6004): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6004): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@2a689da2 on behalf of 6004
D/Finsky  ( 6004): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6004): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6004): Skipping gmscore version check
,D/Finsky  ( 6004): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5614): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 6004): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AudioManager( 5120): getMode name:com.lge.qremote
I/PackageBroadcastService( 5614): Null package name or gms related package.  Ignoreing.
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  838): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  838): onReceive
D/LocSvc_java(  838): got connectivity action
D/LocSvc_java(  838): broadcast - no network connections
D/LocSvc_java(  838): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  838): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  838): onReceive
,D/LocSvc_java(  838): got connectivity action
D/LocSvc_java(  838): broadcast - no network connections
D/LocSvc_java(  838): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  838): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  838): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  838): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  838): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  838): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  838): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  838): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  838): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  838): identical MTU - not setting
D/Nat464Xlat(  838): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  838): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  838): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  838): enableDataServiceNotify 
D/DSQN    (  838): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1367): CM callback handler got msg 524295
I/Icing   ( 5614): updateResources: need to parse f{com.google.android.gms}
,D/GpsLocationProvider(  838): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:14.072 DNS addrs= 192.168.1.1, 0.0.0.0, 
,D/GpsLocationProvider(  838): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/dhcpcd  ( 6033): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
D/DSQN    (  838): dsqn is running restart
,D/GpsLocationProvider(  838): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  838): Process com.android.providers.calendar (pid 5481) has died
I/DSQN    ( 6099): DSQN samuel.seo ver 141203
E/DSQN    ( 6099): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6099): created command queue thread
I/DSQN    ( 6099): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6099): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/dhcpcd  ( 6033): wlan0: leased 192.168.1.134 for 86400 seconds
I/ActivityManager(  838): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6105 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 535us total 21.813ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.927ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 28.407ms
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  838): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  838): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  838): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  838): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  838): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  838): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  838): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  838): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  838): RunningState
,I/ActivityManager(  838): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6150 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  838): Process com.lge.appbox.client (pid 5889) has died
,E/UpdateRequestReceiver( 6150): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6150): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6150): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6150): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  838): Killing 5792:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10038/pid_5792/cgroup.procs: No such file or directory
,I/CheckinService( 5614): Checkin interval check for package: unspecified last checkin: 1454523122378 min interval config: 0 actual interval: 12462
,I/CheckinService( 5614): Checking schedule, now: 1454523134849 next: 1454523152336
I/CheckinService( 5614): active receiver: disabled
I/GservicesUpdateTask( 1935): Updating Gservices keys
,I/SystemUpdateService( 5614): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 5614): onCreate
,D/SystemUpdateService( 5614): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 5614): cancelUpdate (empty URL)
I/SystemUpdateService( 5614): active receiver: disabled
,I/NotificationManager( 5614): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 5614): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,I/art     ( 5614): Explicit concurrent mark sweep GC freed 45993(3MB) AllocSpace objects, 33(528KB) LOS objects, 25% free, 13MB/17MB, paused 1.017ms total 101.847ms
,I/art     ( 6042): Explicit concurrent mark sweep GC freed 8984(455KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 460us total 40.012ms
,I/Icing   ( 5614): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  838): Process com.google.android.talk (pid 5822) has died
,I/QCNEJ   ( 1836): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:12:15.515 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Icing   ( 5614): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
D/SystemUpdateService( 5614): onDestroy
,E/DynamiteModule( 5614): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 5614): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 5614): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 5614): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 5614): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 5614): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 5614): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 5614): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 5614): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 5614): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 5614): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 5614): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 5614): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 5614): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 5614): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 5614): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 5614): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 5614): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 5614): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 5614): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 5614): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 5614): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 5614): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 5614): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 5614): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 5614): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 5614): 		... 17 more
E/DynamiteModule( 5614): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 5614): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 5614): Selected local version of com.google.android.gms.flags
D/SystemEventReceiver( 5614): Received GSERVICES_CHANGED broadcast
,D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  838): onReceive
D/LocSvc_java(  838): got connectivity action
D/LocSvc_java(  838): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  838): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  838): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  838): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  838): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/UEI.SmartControl( 5863): Internal timer expired: 1
,D/GpsLocationProvider(  838): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  838): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/OcrUtils( 5614): Updating ocr activity enabled=false
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 6042): Explicit concurrent mark sweep GC freed 2630(101KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 941us total 27.734ms
,W/ActivityManager(  838): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
D/OcrModelManager( 5614): Updating downloaded model state (gservices changed)
,V/WifiInternetCheck(  838): Single check msg out of sync, ignoring.
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 18031(1265KB) AllocSpace objects, 24(384KB) LOS objects, 40% free, 13MB/22MB, paused 2.448ms total 77.534ms
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/GCM     ( 1730): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/NotificationManager(  838): android: cancelAsUser(-591465577) by android
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  838): Killing 5912:com.android.gallery3d/u0a23 (adj 15): empty #11
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
,I/DSQN    ( 6099): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6099): restart monitoring
,D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6099): dsqn report finish
D/DSQN    (  838): DSQM DsqnNotification wlan0  1
D/DSQN    (  838): start to monitor internet connection
W/libprocessgroup(  838): failed to open /acct/uid_10023/pid_5912/cgroup.procs: No such file or directory
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 6042): Explicit concurrent mark sweep GC freed 2529(100KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 885us total 25.637ms
,I/GCoreUlr( 1730): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,V/AlarmManager(  838): RTC_WAKEUP set : Alarm{2fab8f8c type 0 when 1454523136514 com.android.vending} when 1454523136514
D/Finsky  ( 6004): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/ActivityManager(  838): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6215 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/GCoreUlr( 1730): DispatchingService.onCreate()
,I/art     (  838): Explicit concurrent mark sweep GC freed 47346(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.351ms total 157.559ms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1730): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/NotificationManager(  838): android: cancelAsUser(2) by android
W/GeofencerStateMachine( 1730): Ignoring removeGeofence because network location is disabled.
E/ctxmgr  ( 1730): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,D/PhoneMonitor( 6215): Register our PhoneStateListener
,D/libc-netbsd( 6004): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6004): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6004): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6004): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
V/SetupWizard( 6215): Connected to Gservices successfully
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 6215): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,W/ctxmgr  ( 1730): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 6004): propertyValue:false
D/libc-netbsd( 6004): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6004): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/TelephonyAutoProfiling( 6215): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6215): [parse] Load xml
E/ctxmgr  ( 1730): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
V/TelephonyAutoProfiling( 6215): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6215): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6215): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/GCoreUlr( 1730): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/GCoreUlr( 1730): Unbound from all location providers
I/GCoreUlr( 1730): Place inference reporting - stopped
D/LocationInitializer( 5614): Restart initialization of location
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/GCoreUlr( 1730): DispatchingService.onDestroy()
I/GCoreUlr( 1730): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1730): Unbound from all location providers
I/GCoreUlr( 1730): Place inference reporting - stopped
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 94850258771; DSPS: 3205987; Offset : -2997317129
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  838): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6247 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  838): propertyValue:false
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  838): propertyValue:false
I/art     ( 1730): Explicit concurrent mark sweep GC freed 18739(1134KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 13MB/23MB, paused 2.072ms total 92.099ms
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,V/WifiInternetCheck(  838): isHttpConnectionAvailable - We got a valid response : 204
,D/libc-netbsd( 6004): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6004): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6247): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6247): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6247): Error finding the version of the Email provider.....
E/Gmail   ( 6247): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6247): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6247): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6247): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6247): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6247): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6247): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6247): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6247): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6247): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  838): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6247): Observing account changes for notifications
W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/NotificationManager(  838): android: cancelAsUser(2) by android
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Gmail   ( 6247): notifyAccountChanged
,I/Gmail   ( 6247): getAccountsCursor
I/Gmail   ( 6247): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  838): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6300 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Gmail   ( 6247): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6247): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6247): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ResourcesManager( 6300): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/qtaguid ( 6004): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6004): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6004): untagSocket(41) failed with errno -22
,D/Finsky  ( 6004): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
D/CalendarApplication( 6300): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6300): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6300): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2ee22492, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@385a3e63, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2100ea60, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3b0d3b19, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3af9f7de, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@19a85dbf, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@39fa4c8c, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@332d6fd5, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3629b3ea, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@158f16db, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@f45a578, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2be23451, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@22e724b6, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@245e45b7, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@17eba124, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@44c48d, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2338d642, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@9878653, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@10d3ab90, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@29c61c89, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@102148e, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3fa34af, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1beff0bc, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2deaf845, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2f0eeb9a, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@283f6ccb, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@26295ca8, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2bc7d3c1, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@ee02766, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@560aa7, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@b9b54, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@53ceafd, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@73753f2, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@d4eaa43, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@153118c0, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1ff239f9, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3762bd3e, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@6a7a79f, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2e6f00ec, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3a137cb5, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@13496f4a, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@33691ebb, lg_p
D/GeneralP,referenceUtils( 6300): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6300): [init]
,I/Config  ( 6300): LGCalendar ver.4.40.17
I/Config  ( 6300): start check model
I/Config  ( 6300): start check native_ca
I/Config  ( 6300): Config Operator=OPEN, Country=EU
D/Config  ( 6300): [setDefaultValuesToPref]
D/Config  ( 6300): [parseProfiles]
D/ProfilesParser( 6300): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6300): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6300): [updateProfiletoCountryInfo]
D/GeneralPreference( 6300): [checkAndMigrateOldPreference]
,I/ActivityManager(  838): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6320 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AlertReceiver( 6300): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/NotificationManager(  838): android: cancelAsUser(2) by android
,I/Gmail   ( 6247): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6320): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6320): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 5614): Explicit concurrent mark sweep GC freed 19056(1232KB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 13MB/22MB, paused 2.115ms total 73.894ms
,I/MultiDex( 6320): VM with version 2.1.0 has multidex support
I/MultiDex( 6320): install
I/MultiDex( 6320): VM has multidex support, MultiDex support library is disabled.
I/InitNotificationRingtoneService( 6300): Start InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6300): onHandleIntent
I/AlertUtils( 6300): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
D/HolidayDataLoader( 6300): readJsonAsset : holiday.json
,V/JNIHelp ( 6320): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AlertUtils( 6300): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,D/AlertService( 6300): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6300): [updateWidgets] 
I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
D/MonthWidgetProvider( 6300): [onReceive]
D/CalendarWidgetProvider( 6300): [onReceive]
D/CalendarWidgetProvider( 6300): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,D/CalendarTypeController( 6300): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6300): [onReceive]
D/CalendarWidgetProvider( 6300): [onReceive]
D/CalendarWidgetProvider( 6300): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
D/CalendarTypeController( 6300): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5120): getMode name:com.lge.qremote
I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/ActivityManager(  838): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6344 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/qtaguid ( 6004): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6004): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6004): untagSocket(41) failed with errno -22
W/ActivityThread( 6320): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6320): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bdeaa33: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6320): Installed default security provider GmsCore_OpenSSL
E/HolidayIntentService( 6300): onHandleIntent:holiday data empty
I/art     (  838): Explicit concurrent mark sweep GC freed 15002(768KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 12.207ms total 177.833ms
,I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/NotificationManager( 6320): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6320): com.google.android.gms: cancel(39789) by com.google.android.gms
I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
W/ResourcesManager( 6344): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6344): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6344): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
W/ResourcesManager( 6344): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6344): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6300): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6300): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6300): set default noti to content://media/internal/audio/media/38
,D/ChimeraCfgMgr( 6320): Reading stored module config
I/InitNotificationRingtoneService( 6300): End InitializeAlertRingtoneService.onHandleIntent
,D/ChimeraCfgMgr( 6320): Loading module com.google.android.gms.car from APK com.google.android.gms
I/IndexDatabaseHelper( 6344): Using schema version: 115
,I/IndexDatabaseHelper( 6344): Index is fine
D/CAR.SERVICE( 6320): Connecting to CarCallService...
,I/art     ( 6320): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6320): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6320): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6320): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6320): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6320): Creating a new PhoneAdapter instance
W/ActivityManager(  838): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6320): setListener: com.google.android.gms.car.dn@2ed9b29e
W/ActivityManager(  838): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6320): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6320): Starting CarCallService with initial phone null
I/art     ( 6004): CheckpointMarkThreadRoots callback created = 0xb057b270
,I/NotificationManager( 6320): com.google.android.gms: cancel(10436) by com.google.android.gms
I/art     ( 6004): CheckpointMarkThreadRoots callback created = 0xb057b240
,V/WiFiOffLoadBroadcast( 6344): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/CAR.SERVICE( 6320): Package validated; name: com.android.vending
,D/WiFiOffLoadBroadcast( 6344): MCCMNC not supported: null
I/NotificationManager( 6004): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 6004): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/ActivityManager(  838): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6374 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  838): Killing 5940:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10018/pid_5940/cgroup.procs: No such file or directory
,I/PCSuite ( 6374): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6374): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6374): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6396 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  838): Killing 5962:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5642): 
,W/libprocessgroup(  838): failed to open /acct/uid_10069/pid_5962/cgroup.procs: No such file or directory
V/AlarmManager(  838): RTC_WAKEUP set : Alarm{2ad45d7b type 0 when 1454523139496 com.android.vending} when 1454523139496
,I/ActivityManager(  838): Process com.google.android.gm (pid 6247) has died
,W/ResourcesManager( 6396): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6004): [725] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6004): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/NotificationManager(  838): android: cancelAsUser(2) by android
,I/Babel_SMS( 6396): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6396): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6396): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6396): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6396): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6396): MmsConfig.loadFromResources
E/Babel_SMS( 6396): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6396): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6396): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6396): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6396): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6396): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6396): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6396): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6396): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6396): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6396): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6396): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6396): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6396): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6396): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6396): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6396): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6396): found sensor: Motion Accel, handle=46
,I/art     ( 6396): CheckpointMarkThreadRoots callback created = 0xb042d810
,I/art     ( 6396): CheckpointMarkThreadRoots callback created = 0xb042d7f0
,I/ActivityManager(  838): Process com.google.android.apps.plus (pid 5979) has died
W/Settings( 6396): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6396): startup - clean
,I/Babel   ( 6396): deleted: false for 0
,I/qtaguid ( 6004): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6004): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6004): untagSocket(41) failed with errno -22
,V/WiFiOffLoadBroadcast( 6344): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6344): MCCMNC not supported: null
I/PCSuite ( 6374): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6374): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6374): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/AudioCapabilities( 6396): Unsupported mime audio/x-lg-flac
V/WiFiOffLoadBroadcast( 6344): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6396): Unsupported mime audio/adpcm
W/AudioCapabilities( 6396): Unsupported mime audio/g726
W/AudioCapabilities( 6396): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6396): Unsupported mime audio/wma-voice
D/WiFiOffLoadBroadcast( 6344): MCCMNC not supported: null
I/PCSuite ( 6374): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6374): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6374): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/VideoCapabilities( 6396): Unsupported mime video/mjpg
,V/WiFiOffLoadBroadcast( 6344): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6344): MCCMNC not supported: null
,W/VideoCapabilities( 6396): Unsupported mime video/theora
I/PCSuite ( 6374): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6374): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6374): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6344): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6344): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6344): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6344): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6344): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6344): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6344): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6344): MCCMNC not supported: null
W/AudioCapabilities( 6396): Unsupported mime audio/evrc
,V/WiFiOffLoadBroadcast( 6344): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6396): Unsupported mime audio/qcelp
W/VideoCapabilities( 6396): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6344): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6344): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6344): MCCMNC not supported: null
W/AudioCapabilities( 6396): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6396): Unsupported mime audio/qcelp
W/AudioCapabilities( 6396): Unsupported mime audio/evrc
V/WiFiOffLoadBroadcast( 6344): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6344): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6344): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6344): MCCMNC not supported: null
W/VideoCapabilities( 6396): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6396): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6396): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6396): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6396): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 6004): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6004): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 6396): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6396): onServiceConnected
,W/Babel   ( 6396): Attempted to change video mute state without an active call.
I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6426 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ResourcesManager( 6004): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  838): Process com.google.android.partnersetup (pid 6105) has died
,V/AlarmManager(  838): RTC_WAKEUP set : Alarm{23a1d12 type 0 when 1454523140731 com.google.android.googlequicksearchbox} when 1454523140731
D/Finsky  ( 6004): [1] DailyHygiene.access$600: Logging device features
I/NotificationManager( 6396): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/NotificationManager( 6396): com.google.android.talk: cancel(8) by com.google.android.talk
V/AlarmManager(  838): RTC_WAKEUP set : Alarm{1c783c6a type 0 when 1454523140891 com.android.vending} when 1454523140891
,W/ResourcesManager( 6396): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6396): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6396): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5642): 
D/DeviceConnectionService( 1730): client connected with version: 8296000
I/AppUp4:AppBoxCP( 6426): onCreate
,W/AppUp4:DB( 6426):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6426):  setFingerPrint start
I/AppUp4:DB( 6426):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6426):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6426):  SDK version = 0
I/AppUp4:DB( 6426):  beforefinger == newfinger no write in DB
,W/System  ( 6396): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6396): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  838): Process com.google.android.setupwizard (pid 6215) has died
,D/AppUp4:AppBoxApplication( 6426): AppBoxApplication onCreate()
D/Finsky  ( 6004): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6004): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5642): 
I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5642): 
,I/AppUp4:CustModeStarterReceiver( 6426): onReceive
I/AppUp4:CustModeStarterReceiver( 6426): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6426): Context : android.app.ReceiverRestrictedContext@385a3e63
D/AppUp4:CustFacade( 6426): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6426): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6426): begin check event
I/AppUp4:CustModeStarterReceiver( 6426): Event For Nothing, skip.
I/ActivityManager(  838): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6453 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5642): 
,I/ActivityManager(  838): Process com.android.settings (pid 6344) has died
I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5642): 
W/ResourcesManager( 6453): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6453): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6453): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/AppConfig( 6453): Total System Memory = 906309632
,I/GalleryUtils( 6453): Application Heap = 96 MB
I/AppConfig( 6453): App Tier : NOT_DEF
D/SystemHelper( 6453): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  838): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6478 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 308us total 24.170ms
I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.064ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 32.549ms
,W/ResourcesManager( 6478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6478): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6478): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6478): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6478): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 6478): BUILD Country: EU
I/SystemConfig( 6478): BUILD Operator: OPEN
,I/ActivityManager(  838): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6506 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6478): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6478): existFile = false
I/SystemConfig( 6478): canReadFile = false
I/SystemConfig( 6478): systemFeature RCS result false
D/SystemConfig( 6478): refreshRcsSupport() :false
,I/LockScreenSettings( 6506): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6506): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6506): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6506): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6506): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6506): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  838): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6527 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  838): Killing 6150:com.google.android.configupdater/u0a3 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  838): failed to open /acct/uid_10003/pid_6150/cgroup.procs: No such file or directory
,W/ResourcesManager( 6527): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  838): Killing 5863:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5120): android.os.DeadObjectException
,W/System.err( 5120): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5120): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5120): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5120): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5120): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5120): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5120): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5120): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5120): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5120): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5120): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5120): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5120): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5120): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5120): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5120): android.os.DeadObjectException
W/System.err( 5120): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5120): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5120): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5120): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5120): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5120): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5120): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5120): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5120): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5120): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5120): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5120): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5120): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5120): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5120): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  838): failed to open /acct/uid_10089/pid_5863/cgroup.procs: No such file or directory
,W/ActivityManager(  838): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6551 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  838): Process com.android.vending (pid 6004) has died
,D/CAR.SERVICE( 6320): mConnectedToCar = false, abort
,E/ActivityThread( 6320): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1c8750c6 that was originally bound here
E/ActivityThread( 6320): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1c8750c6 that was originally bound here
E/ActivityThread( 6320): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6320): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6320): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6320): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6320): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6320): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6320): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6320): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6320): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6320): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6320): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6320): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6320): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6320): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6320): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6320): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6320): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6320): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6320): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6320): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@78028d9 that was originally bound here
E/ActivityThread( 6320): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@78028d9 that was originally bound here
E/ActivityThread( 6320): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6320): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6320): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6320): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6320): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6320): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6320): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6320): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6320): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6320): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6320): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6320): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6320): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6320): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6320): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6320): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6320): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6320): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6320): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6320): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6320): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6320): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  838): Unbind failed: could not find connection for android.os.BinderProxy@2450941a
I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  838): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6577 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 60 ms] updated apps [took 60 ms] 
,D/UEI.SmartControl( 6551): Quickset Services start...
I/UEI.SmartControl( 6551): Manufacture = LGE
D/UEI.SmartControl( 6551): File observer start...
,E/UEI.SmartControl( 6551): IR Port is disabled: false
D/UEI.SmartControl( 6551): Starting file observer...
D/UEI.SmartControl( 6551): Extracting JNI libs...
D/UEI.SmartControl( 6551): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 6551): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6551): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 6551): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6551): --- Selecting new region: 2
,I/UEI.SmartControl( 6551): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6551): Platform has CIR...
D/UEI.SmartControl( 6551): NO CIR support, need to check package...
I/UEI.SmartControl( 6551): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6551): QS Service created
E/UEI.SmartControl( 6551): QS start get config
,D/UEI.SmartControl( 6551): Loading JNI Libs...
,D/UEI.SmartControl( 6551):  configuring local db...
D/Finsky  ( 6577): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/Finsky  ( 6577): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/UEI.SmartControl( 6551):  ---- Has DB8: true
,W/Settings( 6577): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6577): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/UEI.SmartControl( 6551): QS start statue = true Error code = 0
D/UEI.SmartControl( 6551): QS version = v2.7.11.1_RC1
I/NotificationManager( 6577): com.android.vending: cancel(-1050172287) by com.android.vending
D/UEI.SmartControl( 6551): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6551): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6551): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6551): IrrcClient ++ 
D/irrcClient( 6551): getIrrcService ++ 
,D/irrcClient( 6551): getIrrcService -- 
D/irrcClient( 6551): IrrcClient -- 
W/irrc_jni( 6551): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6551): Services init done
D/UEI.SmartControl( 6551): QS Service init finished
,D/UEI.SmartControl( 6551): QS Service version name: 0.1.73
D/UEI.SmartControl( 6551): QS Service version code: 1073
D/UEI.SmartControl( 6551): Service requested: Control
I/UEI.SmartControl( 6551): Device manager: loading config....
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@3bdeaa33 on behalf of 6577
,D/UEI.SmartControl( 6551): Config is loaded...
I/art     ( 6042): Explicit concurrent mark sweep GC freed 2885(115KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 428us total 29.046ms
,D/Finsky  ( 6577): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6577): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6577): Skipping gmscore version check
D/Finsky  ( 6577): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/UEI.SmartControl( 6551):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 6551): Request IControl service: devices are loaded...
I/UEI.SmartControl( 6551): Notify AllClients services are ready: 0
,I/ActivityManager(  838): Killing 6374:com.lge.sync/1000 (adj 15): empty #11
,D/UEI.SmartControl( 6551): -----IControl: 11
D/UEI.SmartControl( 6551): Caller: com.lge.qremote
D/UEI.SmartControl( 6551): ------------ IControl registerCallback...
I/UEI.SmartControl( 6551): Registering callback...
D/UEI.SmartControl( 6551): -----IControl: 19
D/UEI.SmartControl( 6551): Caller: com.lge.qremote
I/UEI.SmartControl( 6551): Registering Services Ready callback...
I/UEI.SmartControl( 6551): Notify client services are ready...
D/UEI.SmartControl( 6551): -----IControl: 8
D/UEI.SmartControl( 6551): Caller: com.lge.qremote
,D/Finsky  ( 6577): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/AlertService( 6300): Beginning updateAlertNotification
,D/UEI.SmartControl( 6551): Internal service binding...
,W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_6374/cgroup.procs: No such file or directory
D/PackageBroadcastService( 5614): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  838): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6628 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 5614): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  838): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6646 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ResourcesManager( 6628): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6628): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@ec392f4
,I/art     (  838): Explicit concurrent mark sweep GC freed 23456(1079KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.430ms total 157.462ms
,D/CalendarProvider2( 6628): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6628): Created com.android.providers.calendar.CalendarAlarmManager@3b0d3b19(com.android.providers.calendar.CalendarProvider2@ec392f4)
I/Icing   ( 5614): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6646): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6646): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6646): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6646): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6646): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/AlertService( 6300): No fired or scheduled alerts
,I/NotificationManager( 6300): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(18) by com.android.calendar
,I/NotificationManager( 6300): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6300): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6300): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  838): Killing 5120:com.lge.qremote/u0a106 (adj 15): empty #11
I/IndexDatabaseHelper( 6646): Using schema version: 115
,I/IndexDatabaseHelper( 6646): Index is fine
W/libprocessgroup(  838): failed to open /acct/uid_10106/pid_5120/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/AlarmScheduler( 6300): No events found starting within 1 week.
,I/ActivityManager(  838): Killing 6300:com.android.calendar/u0a13 (adj 15): empty #11
,V/WiFiOffLoadBroadcast( 6646): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6646): MCCMNC not supported: null
W/libprocessgroup(  838): failed to open /acct/uid_10013/pid_6300/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6676 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  838): Killing 6320:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10006/pid_6320/cgroup.procs: No such file or directory
,W/PackageSettings(  838): Skipping PackageSetting{3fd1c8c3 com.example.hello/10317} due to missing metadata
,I/ActivityManager(  838): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6698 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  838): Killing 6426:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10011/pid_6426/cgroup.procs: No such file or directory
,W/ResourcesManager( 6698): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33282b2b:true
,D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
V/WiFiOffLoadBroadcast( 6646): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6646): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6646): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6646): MCCMNC not supported: null
I/PCSuite ( 6676): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6676): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6646): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6646): MCCMNC not supported: null
I/PCSuite ( 6676): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6676): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  838): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6718 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6718): Register our PhoneStateListener
,I/ActivityManager(  838): Killing 6453:com.android.gallery3d/u0a23 (adj 15): empty #11
,D/PhoneMonitor( 6718): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6718): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6718): [parse] Load xml
V/TelephonyAutoProfiling( 6718): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6718): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6718): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  838): failed to open /acct/uid_10023/pid_6453/cgroup.procs: No such file or directory
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 5614): Checkin interval check for package: unspecified last checkin: 1454523122378 min interval config: 0 actual interval: 22738
D/CalendarProviderBroadcastReceiver( 6628): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6628): [IntentService] WakeLock acquire, start IntentSerivce
I/Icing   ( 5614): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/CalendarProvider2( 6628): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6628): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6628): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  838): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6739 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 5614): Checking schedule, now: 1454523145161 next: 1454523152336
I/CheckinService( 5614): active receiver: disabled
D/CalendarProvider2( 6628): [IntentService] Release Lock
,D/CalendarProvider2( 6628): CalendarProviderIntentService.onDestroy()
,D/Icing   ( 5614): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5614): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  838): Killing 6478:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10018/pid_6478/cgroup.procs: No such file or directory
,I/MusicStore( 6739): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6739): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6739): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6739): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6739): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6739): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
V/JNIHelp ( 6739): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
W/ActivityThread( 6739): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
W/System  ( 6739): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22e6c25a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6739): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6739): GMSCore installation verified
I/ConfigStore( 6739): Config Database version: 1
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,I/MediaRouter( 6739): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 6739): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6739): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  838): Killing 6396:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10061/pid_6396/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6739): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  838): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6776 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 320us total 23.320ms
,I/GHttpClientFactory( 6739): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.059ms
I/GoogleURLConnFactory( 6739): Using platform SSLCertificateSocketFactory
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.547ms
,I/ActivityManager(  838): Killing 6506:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/ResourcesManager( 6776): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6776): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6776): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  838): failed to open /acct/uid_10069/pid_6506/cgroup.procs: No such file or directory
,I/NotificationManager( 6739): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6776): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6776): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6776): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  838): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6808 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6776): JNI_OnLoad()
I/HubEmail( 6776): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6776): registerNatives()
I/HubEmail( 6776): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6776): registerNativeMethods()
I/HubEmail( 6776): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6776): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6776): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  838): Killing 6551:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10089/pid_6551/cgroup.procs: No such file or directory
,D/LGDMClient( 6808): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6808): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6808): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6808): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6808): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6808): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6808): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6808): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6833 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6808): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6808): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6808): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6808): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6808): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6808): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  838): Killing 6527:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10086/pid_6527/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6833): onCreate
W/AppUp4:DB( 6833):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6833):  setFingerPrint start
I/AppUp4:DB( 6833):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6833):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6833):  SDK version = 0
I/AppUp4:DB( 6833):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6833): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6833): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6833): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6833): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6833): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6833): onReceive
I/AppUp4:CustModeStarterReceiver( 6833): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6833): Context : android.app.ReceiverRestrictedContext@3af9f7de
D/AppUp4:CustFacade( 6833): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6833): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6833): begin check event
I/AppUp4:CustModeStarterReceiver( 6833): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6833): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6833): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6833): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6833): handleAsyncCustNotification do not startCustService
I/ActivityManager(  838): Killing 6577:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10036/pid_6577/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3260): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3260): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3260): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 6718): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6718): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 3211): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3211): DownloadService onCreate
I/NotificationManager( 3211): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3211): in removeSpuriousFiles
,V/DownloadManager( 3211): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@2c1c31f0 on behalf of 3211
,I/ActivityManager(  838): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6858 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3211): DownloadService onStartCommand
,V/DownloadManager( 3211): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3211): in trimDatabase
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@2dcfb68f on behalf of 3211
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@caa7d1c on behalf of 3211
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/DownloadManager( 3211): DownloadService onDestroy
,I/ActivityManager(  838): Killing 6646:com.android.settings/1000 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_6646/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2697): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:12:28
D/UpdateThreadPoolManager( 2697): 2 : This is isUpdating : false
D/WeatherAncestor( 2697): connectivity changed - connection : true
D/Weather_cast( 2697): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2697): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:12:28
D/WeatherService( 2697): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6876 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2697): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2697): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2697): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6876): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinService( 5614): Done disabling old GoogleServicesFramework version
,I/Babel_SMS( 6876): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6876): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6876): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6876): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6876): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6876): MmsConfig.loadFromResources
E/Babel_SMS( 6876): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6876): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6876): CheckpointMarkThreadRoots callback created = 0xb042d810
,I/art     ( 6876): CheckpointMarkThreadRoots callback created = 0xb042d800
,D/SensorManager( 6876): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6876): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6876): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6876): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6876): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6876): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6876): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6876): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6876): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6876): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6876): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6876): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6876): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6876): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6876): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6876): found sensor: Motion Accel, handle=46
W/Settings( 6876): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6876): startup - clean
I/Babel   ( 6876): deleted: false for 0
,I/ActivityManager(  838): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6913 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6876): Unsupported mime audio/x-lg-flac
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/AudioCapabilities( 6876): Unsupported mime audio/adpcm
W/AudioCapabilities( 6876): Unsupported mime audio/g726
,W/AudioCapabilities( 6876): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6876): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6876): Unsupported mime video/mjpg
W/VideoCapabilities( 6876): Unsupported mime video/theora
,W/AudioCapabilities( 6876): Unsupported mime audio/evrc
,W/AudioCapabilities( 6876): Unsupported mime audio/qcelp
W/VideoCapabilities( 6876): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6876): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6876): Unsupported mime audio/qcelp
W/AudioCapabilities( 6876): Unsupported mime audio/evrc
W/VideoCapabilities( 6876): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6876): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6876): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6876): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6876): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6876): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6876): onServiceConnected
,W/Babel   ( 6876): Attempted to change video mute state without an active call.
I/NotificationManager( 6876): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6876): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6876): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6876): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6876): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6876): propertyValue:false
I/Babel   ( 6876): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  838): Killing 6676:com.lge.sync/1000 (adj 15): empty #11
,I/art     (  838): Explicit concurrent mark sweep GC freed 20316(1237KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.491ms total 141.553ms
,W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_6676/cgroup.procs: No such file or directory
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6913): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6913): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6913): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6913): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6913): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6913):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6913):   adb logcat -s GAv4
W/GAv4    ( 6913): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6913): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6913): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6913): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6913): Time to load native libraries: 2 ms (timestamps 7608-7610)
,I/LibraryLoader( 6913): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6913): Binding Chromium to main looper Looper (main, tid 1) {37268623}
I/LibraryLoader( 6913): Expected native library version number "",actual native library version number ""
I/chromium( 6913): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6913): Initializing chromium process, singleProcess=true
,W/art     ( 6913): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6913): ApplicationContext is null in ApplicationStatus
W/chromium( 6913): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6913): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6913): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6913): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6913): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6913): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6913): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6913): Remote Branch: 
I/Adreno-EGL( 6913): Local Patches: 
I/Adreno-EGL( 6913): Reconstruct Branch: 
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/NSApplication( 6913): Starting up...
,V/AudioPolicyService(  278): registerClient() client 0xb39acb60, uid 10079
W/AudioManagerAndroid( 6913): Requires BLUETOOTH permission
I/ActivityManager(  838): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6978 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  838): Killing 6628:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10014/pid_6628/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6997 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  838): Killing 6739:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10081/pid_6739/cgroup.procs: No such file or directory
,W/ResourcesManager( 6997): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 5642): Test app app.js loaded
I/jxcore-log( 5642): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ca0d5d5 added. We now have 1 listener(s)
D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
,I/jxcore-log( 5642): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5642): 
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/chromium( 5642): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/iu.SyncManager( 5614): SYNC; picasa accounts
,D/NetworkLogImpl( 5614): Loaded NetworkSpeedPredictor
I/iu.Environment( 5614): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  838): Killing 6776:com.lge.email/u0a21 (adj 15): empty #11
I/iu.UploadsManager( 5614): num queued entries: 0
I/iu.UploadsManager( 5614): num updated entries: 0
I/iu.SyncManager( 5614): NEXT; no task
W/libprocessgroup(  838): failed to open /acct/uid_10021/pid_6776/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7025 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7025): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7025): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7025): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7025): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7025): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7025): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7025): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7025): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7025): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22e6c25a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7025): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7025): GMSCore installation verified
I/ConfigStore( 7025): Config Database version: 1
,I/MediaRouter( 7025): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7025): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7025): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7025): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  838): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7056 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7025): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7025): Using platform SSLCertificateSocketFactory
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  838): Killing 6808:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 7056): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7056): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7056): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_6808/cgroup.procs: No such file or directory
,I/NotificationManager( 7025): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7056): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7056): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7056): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  838): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7094 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7056): JNI_OnLoad()
I/HubEmail( 7056): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7056): registerNatives()
I/HubEmail( 7056): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7056): registerNativeMethods()
I/HubEmail( 7056): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7056): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  838): Killing 6833:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10011/pid_6833/cgroup.procs: No such file or directory
,W/Settings( 7056): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7094): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7094): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7094): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7094): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7094): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7094): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7094): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7094): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7118 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7094): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 334us total 22.685ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.430ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.896ms
E/LGDMClient( 7094): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7094): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7094): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7094): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7094): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  838): Killing 6718:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/AppUp4:AppBoxCP( 7118): onCreate
W/AppUp4:DB( 7118):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7118):  setFingerPrint start
I/AppUp4:DB( 7118):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7118):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7118):  SDK version = 0
I/AppUp4:DB( 7118):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  838): failed to open /acct/uid_10038/pid_6718/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 7118): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7118): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7118): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7118): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 7118): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7118): onReceive
I/AppUp4:CustModeStarterReceiver( 7118): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7118): Context : android.app.ReceiverRestrictedContext@3af9f7de
D/AppUp4:CustFacade( 7118): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7118): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7118): begin check event
I/AppUp4:CustModeStarterReceiver( 7118): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7118): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7118): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7118): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7118): handleAsyncCustNotification do not startCustService
I/ActivityManager(  838): Killing 6858:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10051/pid_6858/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3260): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3260): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3260): networkInfo.isConnected() = false
,I/ActivityManager(  838): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7142 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7142): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7142): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7142): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  838): Killing 6876:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7142): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7142): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7142): [parse] Load xml
V/TelephonyAutoProfiling( 7142): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7142): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/PhoneMonitor( 7142): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  838): failed to open /acct/uid_10061/pid_6876/cgroup.procs: No such file or directory
V/DownloadManager( 3211): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3211): DownloadService onCreate
I/NotificationManager( 3211): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3211): in removeSpuriousFiles
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@261b2cab on behalf of 3211
I/DownloadManager( 3211): in trimDatabase
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@38704f08 on behalf of 3211
I/ActivityManager(  838): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7164 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3211): DownloadService onStartCommand
,V/DownloadManager( 3211): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@1c8750c6 on behalf of 3211
I/CheckinService( 5614): Checkin interval check for package: unspecified last checkin: 1454523122378 min interval config: 0 actual interval: 30778
,I/CheckinService( 5614): Checking schedule, now: 1454523153170 next: 1454523152336
I/CheckinService( 5614): active receiver: enabled
,I/CheckinService( 5614): Preparing to send checkin request
V/DownloadManager( 3211): DownloadService onDestroy
I/EventLogService( 5614): Accumulating logs since 1454523112682
D/WeatherAncestor( 2697): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:12:33
,D/UpdateThreadPoolManager( 2697): 2 : This is isUpdating : false
D/WeatherAncestor( 2697): connectivity changed - connection : true
D/Weather_cast( 2697): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2697): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:12:33
D/WeatherService( 2697): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7182 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2697): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2697): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2697): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7182): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5614): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5614): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 7182): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7182): MmsConfig.loadMmsSettings
I/art     (  838): Explicit concurrent mark sweep GC freed 16990(865KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.735ms total 153.383ms
,I/Babel_SMS( 7182): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7182): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7182): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7182): MmsConfig.loadFromResources
E/Babel_SMS( 7182): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7182): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7182): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7182): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7182): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7182): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7182): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7182): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7182): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7182): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7182): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7182): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7182): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
,D/SensorManager( 7182): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7182): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7182): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7182): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7182): found sensor: Motion Accel, handle=46
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 7182): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7182): startup - clean
I/art     ( 7182): CheckpointMarkThreadRoots callback created = 0xb042d810
,I/Babel   ( 7182): deleted: false for 0
,I/art     ( 7182): CheckpointMarkThreadRoots callback created = 0xb042d800
I/ActivityManager(  838): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7218 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/AudioCapabilities( 7182): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7182): Unsupported mime audio/adpcm
W/AudioCapabilities( 7182): Unsupported mime audio/g726
W/ResourcesManager( 7218): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7218): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AudioCapabilities( 7182): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7182): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7182): Unsupported mime video/mjpg
I/AudioManager( 6698): getMode name:com.lge.qremote
,W/VideoCapabilities( 7182): Unsupported mime video/theora
I/AudioManager( 6698): getMode name:com.lge.qremote
,W/AudioCapabilities( 7182): Unsupported mime audio/evrc
W/AudioCapabilities( 7182): Unsupported mime audio/qcelp
W/VideoCapabilities( 7182): Unrecognized profile 2130706433 for video/avc
,I/MultiDex( 7218): VM with version 2.1.0 has multidex support
I/MultiDex( 7218): install
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/MultiDex( 7218): VM has multidex support, MultiDex support library is disabled.
W/AudioCapabilities( 7182): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7182): Unsupported mime audio/qcelp
W/AudioCapabilities( 7182): Unsupported mime audio/evrc
W/VideoCapabilities( 7182): Unsupported mime video/mp4v-esdp
,V/JNIHelp ( 7218): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/VideoCapabilities( 7182): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7182): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7182): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7182): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7182): Unrecognized profile 2130706433 for video/avc
,W/ActivityThread( 7218): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7218): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bdeaa33: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7218): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  838): Process com.google.android.music:main (pid 7025) has died
,I/ActivityManager(  838): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7238 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager( 7218): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7218): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/vclib   ( 7182): onServiceConnected
W/Babel   ( 7182): Attempted to change video mute state without an active call.
I/NotificationManager( 7182): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7182): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7182): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7182): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7182): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 7182): propertyValue:false
,I/art     ( 7218): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7218): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Babel   ( 7182): connection state changed from UNKNOWN to CONNECTED
,I/MusicStore( 7238): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7238): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/NativeLibraryUtils( 7218): Install completed successfully. count=14 extracted=0
D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): CdmEngine::OpenSession
I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  278): L1 library not specified. Falling Back to L3
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7238): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7238): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  838): Process com.lge.email (pid 7056) has died
V/AlarmManager(  838): RTC_WAKEUP set : Alarm{36759ce9 type 0 when 1454523152336 com.google.android.gms} when 1454523152336
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=2176383163
I/ActivityManager(  838): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7269 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  838): RTC_WAKEUP set : Alarm{b18fd6e type 0 when 1454523154531 com.android.vending} when 1454523154531
,W/ResourcesManager( 7238): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7238): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7238): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7238): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7238): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22e6c25a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7238): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7238): GMSCore installation verified
I/ActivityManager(  838): Process com.lge.appbox.client (pid 7118) has died
,I/ConfigStore( 7238): Config Database version: 1
,D/Finsky  ( 7269): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/WVCdm   (  278): CdmEngine::OpenSession
,I/MediaRouter( 7238): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 7238): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7238): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  838): Process com.lge.lgdmsclient (pid 7094) has died
,D/Finsky  ( 7269): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/NetworkMonitor( 7238): type=WIFI subType= reason=null isConnected=true
W/Settings( 7269): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7269): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7269): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  838): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7313 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@173f53b4 on behalf of 7269
,I/art     ( 6042): Explicit concurrent mark sweep GC freed 1887(69KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 408us total 40.571ms
,W/ResourcesManager( 7313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7313): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7313): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/Ads     ( 7269): Skipping gmscore version check
,D/Finsky  ( 7269): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7269): [1] Libraries$2.run: Finished loading 1 libraries.
I/GHttpClientFactory( 7238): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7238): Using platform SSLCertificateSocketFactory
D/Finsky  ( 7269): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7269): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/NotificationManager( 7238): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 7313): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7313): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/Finsky  ( 7269): [930] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7269): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/eas_req ( 7313): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  838): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7341 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7313): JNI_OnLoad()
I/HubEmail( 7313): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7313): registerNatives()
I/HubEmail( 7313): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7313): registerNativeMethods()
I/HubEmail( 7313): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7313): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7313): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 7341): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7341): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7341): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7341): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7341): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7341): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7341): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7341): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7365 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7341): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7341): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7341): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7341): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7341): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7341): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  838): Killing 7164:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10051/pid_7164/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7365): onCreate
,W/AppUp4:DB( 7365):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7365):  setFingerPrint start
I/AppUp4:DB( 7365):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7365):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 7365):  SDK version = 0
I/AppUp4:DB( 7365):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7365): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7365): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7365): onReceive
I/AppUp4:CustModeStarterReceiver( 7365): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7365): Context : android.app.ReceiverRestrictedContext@3af9f7de
,D/AppUp4:CustFacade( 7365): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7365): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7365): begin check event
I/AppUp4:CustModeStarterReceiver( 7365): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7365): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7365): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7365): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7365): handleAsyncCustNotification do not startCustService
I/ActivityManager(  838): Killing 7182:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10061/pid_7182/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3260): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3260): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3260): networkInfo.isConnected() = true
,D/PhoneState( 3260): setPdpRejectCasuse : false
D/MobileConnectivityChangeReceiver( 7142): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7142): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3211): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3211): DownloadService onCreate
,I/DownloadManager( 3211): in removeSpuriousFiles
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@22afabdd on behalf of 3211
I/DownloadManager( 3211): in trimDatabase
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/NotificationManager( 3211): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@1517b352 on behalf of 3211
I/ActivityManager(  838): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7390 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3211): DownloadService onStartCommand
V/DownloadManager( 3211): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@78028d9 on behalf of 3211
,V/DownloadManager( 3211): DownloadService onDestroy
,I/ActivityManager(  838): Killing 6913:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10079/pid_6913/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2697): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:12:36
D/UpdateThreadPoolManager( 2697): 2 : This is isUpdating : false
D/WeatherAncestor( 2697): connectivity changed - connection : true
D/Weather_cast( 2697): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2697): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 19:12:36
D/WeatherService( 2697): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7410 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2697): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  305): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 23.855ms
,D/WeatherService( 2697): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,D/WeatherService( 2697): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/art     (  305): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.491ms
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 23.426ms
,W/ResourcesManager( 7410): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/WVCdm   (  278): CdmEngine::CloseSession
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=4174469211
,I/Babel_SMS( 7410): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7410): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7410): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7410): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7410): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7410): MmsConfig.loadFromResources
E/Babel_SMS( 7410): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7410): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 7410): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7410): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7410): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7410): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7410): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7410): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7410): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7410): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7410): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7410): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7410): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7410): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7410): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7410): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7410): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7410): found sensor: Motion Accel, handle=46
,W/Settings( 7410): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     ( 7410): CheckpointMarkThreadRoots callback created = 0xaaf58580
,I/Babel_Crash( 7410): startup - clean
I/art     ( 7410): CheckpointMarkThreadRoots callback created = 0xaaf58570
,I/Babel   ( 7410): deleted: false for 0
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  838): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7446 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 114850955950; DSPS: 3861370; Offset : -2997321385
,W/AudioCapabilities( 7410): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7410): Unsupported mime audio/adpcm
W/AudioCapabilities( 7410): Unsupported mime audio/g726
W/AudioCapabilities( 7410): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7410): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7410): Unsupported mime video/mjpg
W/VideoCapabilities( 7410): Unsupported mime video/theora
,W/AudioCapabilities( 7410): Unsupported mime audio/evrc
,W/AudioCapabilities( 7410): Unsupported mime audio/qcelp
W/VideoCapabilities( 7410): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7410): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7410): Unsupported mime audio/qcelp
W/AudioCapabilities( 7410): Unsupported mime audio/evrc
W/VideoCapabilities( 7410): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7410): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7410): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7410): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7410): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7410): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7410): onServiceConnected
,W/Babel   ( 7410): Attempted to change video mute state without an active call.
I/NotificationManager( 7410): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7410): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7410): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7410): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7410): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 7410): propertyValue:false
,I/art     (  838): Explicit concurrent mark sweep GC freed 24921(1119KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.110ms total 158.562ms
,I/Babel   ( 7410): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  838): Killing 6978:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10048/pid_6978/cgroup.procs: No such file or directory
,I/GAv4    ( 7446): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7446):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7446):   adb logcat -s GAv4
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7446): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7446): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7446): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7446): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7446): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7446): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7446): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 7446): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7446): Time to load native libraries: 1 ms (timestamps 5619-5620)
I/LibraryLoader( 7446): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7446): Binding Chromium to main looper Looper (main, tid 1) {37268623}
I/LibraryLoader( 7446): Expected native library version number "",actual native library version number ""
I/chromium( 7446): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7446): Initializing chromium process, singleProcess=true
,W/art     ( 7446): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7446): ApplicationContext is null in ApplicationStatus
W/chromium( 7446): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7446): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7446): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7446): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7446): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7446): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7446): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7446): Remote Branch: 
I/Adreno-EGL( 7446): Local Patches: 
I/Adreno-EGL( 7446): Reconstruct Branch: 
V/AudioPolicyService(  278): registerClient() client 0xb39ace40, uid 10079
,W/AudioManagerAndroid( 7446): Requires BLUETOOTH permission
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/NSApplication( 7446): Starting up...
I/ActivityManager(  838): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7517 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  838): Killing 6997:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10086/pid_6997/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7539 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  838): Killing 7238:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10081/pid_7238/cgroup.procs: No such file or directory
,W/ResourcesManager( 7539): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/MusicWidget( 2671): mDelayedStopHandler : unbind
,I/MusicBrowser( 2703): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2703): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2703): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2703): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2703): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2703): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2703): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2703): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  838):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1beff0bccom.lge.music.MediaPlaybackService$6@2deaf845
D/MusicBrowser( 2703): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2703): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2703): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2703): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2703): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3629b3ea
I/MusicBrowser( 2703): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2703): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
,I/MusicBrowser( 2703): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2703): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2703): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2703): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2703): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2703): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2703): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2703): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2703): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2703): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2703): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2703): reset
V/MediaPlayer[Native]( 2703): setListener
V/MediaPlayer[Native]( 2703): disconnect
V/MediaPlayer[Native]( 2703): destructor
,V/AudioFlinger(  278): releasing 18 from 2703 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/MediaPlayer[Native]( 2703): disconnect
D/MusicBrowser( 2703): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2703): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2703): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2703): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2703): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2703): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2703): [SmartShareManagerClient] unregisterListener: 789506970
W/SmartShareClient( 2703): [SmartShareManagerClient] unregisterListener invalid listener: 789506970
I/SmartShareClient( 2703): [SmartShareManagerClient] terminate service: 2703/MediaPlaybackService/553708128
E/HomeCloudIF( 2703): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2703): [SmartShareManagerClient] unbindService context:android.app.Application@283f6ccb
V/CloudHub( 2703): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2703): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2703): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2703): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2703): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  838): Killing 7269:com.android.vending/u0a36 (adj 15): empty #11
I/CloudHub( 2703): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
I/WVCdm   (  278): CdmEngine::CloseSession
,I/WVCdm   (  278): L3 Terminate.
W/libprocessgroup(  838): failed to open /acct/uid_10036/pid_7269/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Killing 7313:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10021/pid_7313/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  838): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7573 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7573): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dex2oat ( 7593): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/GAV2    ( 7573): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7573): getAccountsCursor
,E/Gmail   ( 7573): Error finding the version of the Email provider.....
E/Gmail   ( 7573): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7573): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7573): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7573): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7573): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7573): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7573): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7573): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7573): We do not support migrating this version of the Email provider.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/dex2oat ( 7593): dex2oat took 112.797ms (threads: 4)
W/ActivityManager(  838): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Adreno-EGL( 7218): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7218): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7218): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7218): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7218): Remote Branch: 
I/Adreno-EGL( 7218): Local Patches: 
I/Adreno-EGL( 7218): Reconstruct Branch: 
,I/Gmail   ( 7573): Observing account changes for notifications
W/ActivityManager(  838): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
D/LocationInitializer( 5614): Restart initialization of location
I/ActivityManager(  838): Waited long enough for: ServiceRecord{348237a5 u0 com.lge.qremote/.QRemoteService}
E/MDM     ( 1730): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 6698): getMode name:com.lge.qremote
I/ActivityManager(  838): Killing 7341:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_1000/pid_7341/cgroup.procs: No such file or directory
,I/AudioManager( 6698): getMode name:com.lge.qremote
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
I/ActivityManager(  838): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7629 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Adreno-EGL( 7218): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7218): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7218): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7218): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7218): Remote Branch: 
I/Adreno-EGL( 7218): Local Patches: 
I/Adreno-EGL( 7218): Reconstruct Branch: 
I/Adreno-EGL( 7218): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7218): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7218): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7218): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7218): Remote Branch: 
I/Adreno-EGL( 7218): Local Patches: 
I/Adreno-EGL( 7218): Reconstruct Branch: 
,I/Gmail   ( 7573): notifyAccountChanged
I/Gmail   ( 7573): getAccountsCursor
I/Gmail   ( 7573): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7573): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7573): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7573): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/CheckinRequestBuilder( 5614): Classify the device as Phone.
,D/Finsky  ( 7629): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Gmail   ( 7573): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd( 5614): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5614): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5614): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5614): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5614): propertyValue:false
,D/libc-netbsd( 5614): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5614): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5614): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5614): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5614): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5614): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Finsky  ( 7629): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 7629): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinTask( 5614): Sending checkin request (9749 bytes)
W/Settings( 7629): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7629): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@b51617f on behalf of 7629
D/Finsky  ( 7629): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7629): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7629): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 7629): Skipping gmscore version check
D/Finsky  ( 7629): [984] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7629): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  838): android: cancelAsUser(2) by android
,I/ActivityManager(  838): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7681 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6698): Create singleton instance
,D/libc-netbsd( 7629): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7629): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7629): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7629): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/UEI.SmartControl( 7681): Quickset Services start...
,I/UEI.SmartControl( 7681): Manufacture = LGE
D/UEI.SmartControl( 7681): File observer start...
E/UEI.SmartControl( 7681): IR Port is disabled: false
D/UEI.SmartControl( 7681): Starting file observer...
D/UEI.SmartControl( 7681): Extracting JNI libs...
D/UEI.SmartControl( 7681): --- this system supports 32-bit or 64-bit only
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 7629): propertyValue:false
,I/AudioManager( 6698): getMode name:com.lge.qremote
,I/AudioManager( 6698): getMode name:com.lge.qremote
D/UEI.SmartControl( 7681): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7681): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7681): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/MDM     ( 1730): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5614): Restart initialization of location
I/UEI.SmartControl( 7681): --- Selecting new region: 2
I/UEI.SmartControl( 7681): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7681): Platform has CIR...
D/UEI.SmartControl( 7681): NO CIR support, need to check package...
I/UEI.SmartControl( 7681): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7681): QS Service created
I/CheckinRequestBuilder( 5614): Checkin reason type: 8 attempt count: 1
,I/art     (  838): Explicit concurrent mark sweep GC freed 24149(1110KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.575ms total 162.569ms
,E/ActivityThread( 5614): Failed to find provider info for com.google.android.wearable.settings
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
I/CheckinService( 5614): Checkin interval check for package: unspecified last checkin: 1454523122378 min interval config: 0 actual interval: 38447
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
E/UEI.SmartControl( 7681): QS start get config
,W/ContextImpl( 3630): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager(  838): Killing 7365:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/UEI.SmartControl( 7681): Loading JNI Libs...
,D/UEI.SmartControl( 7681):  configuring local db...
W/libprocessgroup(  838): failed to open /acct/uid_10011/pid_7365/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 5614): Classify the device as Phone.
,I/CheckinTask( 5614): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5614): Checking schedule, now: 1454523161085 next: 1455050410080
I/CheckinService( 5614): active receiver: disabled
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinService( 5614): Checking schedule, now: 1454523161126 next: 1455050410080
I/CheckinService( 5614): active receiver: disabled
D/CheckinService( 5614): Recording last checkin time for package unspecified as 1454523161139
,D/UEI.SmartControl( 7681):  ---- Has DB8: true
,V/SetupWizard( 7142): Connected to Gservices successfully
D/UEI.SmartControl( 7681): QS start statue = true Error code = 0
D/UEI.SmartControl( 7681): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7681): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7681): IRRCDataComm has AudioManager!!!!.
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/irrc_jni( 7681): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7681): IrrcClient ++ 
D/irrcClient( 7681): getIrrcService ++ 
,D/irrcClient( 7681): getIrrcService -- 
D/irrcClient( 7681): IrrcClient -- 
W/irrc_jni( 7681): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7681): Services init done
I/UEI.SmartControl( 7681): Device manager: loading config....
D/UEI.SmartControl( 7681): QS Service init finished
D/UEI.SmartControl( 7681): QS Service version name: 0.1.73
D/UEI.SmartControl( 7681): QS Service version code: 1073
D/UEI.SmartControl( 7681): Service requested: Control
,D/UEI.SmartControl( 7681): Config is loaded...
D/UEI.SmartControl( 7681):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7681): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7681): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7681): Internal service binding...
D/UEI.SmartControl( 7681): -----IControl: 11
,D/UEI.SmartControl( 7681): Caller: com.lge.qremote
,D/UEI.SmartControl( 7681): ------------ IControl registerCallback...
I/UEI.SmartControl( 7681): Registering callback...
D/UEI.SmartControl( 7681): -----IControl: 19
D/UEI.SmartControl( 7681): Caller: com.lge.qremote
I/UEI.SmartControl( 7681): Registering Services Ready callback...
I/UEI.SmartControl( 7681): Notify client services are ready...
D/UEI.SmartControl( 7681): -----IControl: 8
D/UEI.SmartControl( 7681): Caller: com.lge.qremote
I/AudioManager( 6698): getMode name:com.lge.qremote
,I/ActivityManager(  838): Killing 7446:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/ActivityManager(  838): Killing 7390:com.lge.drmservice/u0a51 (adj 15): empty #12
,W/libprocessgroup(  838): failed to open /acct/uid_10079/pid_7446/cgroup.procs: No such file or directory
,W/libprocessgroup(  838): failed to open /acct/uid_10051/pid_7390/cgroup.procs: No such file or directory
I/AudioManager( 6698): getMode name:com.lge.qremote
I/AudioManager( 6698): getMode name:com.lge.qremote
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1367): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1367): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1367): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1367): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1367): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1367): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/InputReader(  838): Reconfiguring input devices.  changes=0x00000010
,D/administrator(  838): Handling package changes for user 0
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  838): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7758 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 7410): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7410): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7410): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 7758): onCreate
,W/AppUp4:DB( 7758):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7758):  setFingerPrint start
,I/AppUp4:DB( 7758):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7758):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7758):  SDK version = 0
I/AppUp4:DB( 7758):  beforefinger == newfinger no write in DB
V/JNIHelp ( 7410): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AppUp4:AppBoxApplication( 7758): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7758): onReceive
,I/AppUp4:CustModeStarterReceiver( 7758): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7758): Context : android.app.ReceiverRestrictedContext@385a3e63
D/AppUp4:CustFacade( 7758): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7758): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7758): begin check event
I/AppUp4:CustModeStarterReceiver( 7758): Event For Nothing, skip.
I/NotificationService(  838): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  838): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  838): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/System  ( 7410): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7410): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  838): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7780 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/BackupManagerService(  838): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  838): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  838): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1e69ad07
,W/ResourcesManager( 7780): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7780): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7780): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager(  838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  838): Process com.android.vending (pid 7629) has died
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
I/ActivityManager(  838): Process com.google.android.apps.plus (pid 7539) has died
,I/AppConfig( 7780): Total System Memory = 906309632
W/ResourceType(  838): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/GalleryUtils( 7780): Application Heap = 96 MB
I/AppConfig( 7780): App Tier : NOT_DEF
,D/SystemHelper( 7780): region [EU], country [EU], operator [OPEN], sub-operator []
I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/ActivityManager(  838): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7802 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 7802): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7802): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7802): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7802): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 7802): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LocationProviderProxy(  838): applying state to connected service
I/SystemConfig( 7802): BUILD Country: EU
,I/SystemConfig( 7802): BUILD Operator: OPEN
I/ActivityManager(  838): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7822 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7802): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7802): existFile = false
I/SystemConfig( 7802): canReadFile = false
I/SystemConfig( 7802): systemFeature RCS result false
D/SystemConfig( 7802): refreshRcsSupport() :false
,I/LockScreenSettings( 7822): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7822): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7822): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7822): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7822): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7822): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  838): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7839 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  838): Killing 7517:com.android.chrome/u0a48 (adj 15): empty #11
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 351us total 25.062ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 260us total 20.414ms
,W/libprocessgroup(  838): failed to open /acct/uid_10048/pid_7517/cgroup.procs: No such file or directory
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.048ms
,I/GAV2    ( 7573): Thread[GAThread,5,main]: No campaign data found.
,W/ResourcesManager( 7839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GAv4-SVC( 5614): Google Analytics 8.4.89 is starting up.
,I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  838): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7869 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 49 ms] updated apps [took 49 ms] 
I/ActivityManager(  838): Killing 2703:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  278): 2703 died, releasing its sessions
V/AudioFlinger(  278):  pid 1748 @ 0
V/AudioFlinger(  278):  pid 3260 @ 1
,V/AudioFlinger(  278):  pid 3260 @ 2
W/libprocessgroup(  838): failed to open /acct/uid_10028/pid_2703/cgroup.procs: No such file or directory
,D/Finsky  ( 7869): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/Finsky  ( 7869): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7869): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7869): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7869): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3211): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3211): created cursor android.database.sqlite.SQLiteCursor@495654c on behalf of 7869
D/Ads     ( 7869): Skipping gmscore version check
,D/Finsky  ( 7869): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7869): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  838): Killing 7573:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10053/pid_7573/cgroup.procs: No such file or directory
,D/Finsky  ( 7869): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5614): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 5614): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7869): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Icing   ( 5614): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  838): Killing 7142:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10038/pid_7142/cgroup.procs: No such file or directory
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 7681): Internal timer expired: 1
,I/Icing   ( 5614): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5614): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  838): Killing 7758:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10011/pid_7758/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  838): Killing 7410:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  838): failed to open /acct/uid_10061/pid_7410/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1367): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1367): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1367): On Skip Timer : true
D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1367): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  838): battery changed pluggedType: 2
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1367): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 134851898807; DSPS: 4516761; Offset : -2997324156
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=889479013, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
,D/WeatherService( 2697): 2 : TimeTick Intent has been received, Time(hour:min:sec) 19:13:0
,D/WeatherService( 2697): 2 : TimeTick Intent And Screen On
D/WeatherService( 2697): 2 : SDK version : 21
W/ActivityManager(  838): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2697): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2697): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2697): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2697): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2697): 2 : This is isUpdating : false
D/WeatherService( 2697): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2697): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2697): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2697): 2 : Fixed theme : optimus
D/WeatherReflect( 2697): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1367): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1367): called onTimeUpdated()
I/[SystemUI]Clock( 1367): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1367): handleTimeUpdate
D/lim     ( 2697): 2 : time = 19:13
,I/WeatherReflect( 2697): Model Name : LG-D722
D/WeatherTheme( 2697): 2 : Different view - status_min_formatted : 12 != 13
D/WeatherTheme( 2697): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2697): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2697): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2697): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2697): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2697): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2697): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2697): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2697): forecast size is 0
D/Theme   ( 2697): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2697): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2697): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2697): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2697): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2697): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2697): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2697): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2697): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2697): WEATHER_CP_ACCU : 
,I/Theme_WeatherAncestor_optimus( 2697): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2697): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2697): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2697): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2697): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2697): url is : null
D/Theme   ( 2697): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2697): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2697): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2697): 2 : update view, appWidgetId: 2
D/WeatherService( 2697): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 19:13:0
,D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=889479013 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{150b943a type 2 when 145993 com.google.android.gms} when 145993
,I/art     (  838): Explicit concurrent mark sweep GC freed 36573(1822KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 1.929ms total 155.843ms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1730): Vacuum at: now=1454523188729 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PhenotypeConfigurator( 1730): Scheduling Phenotype for one-off execution 7328 seconds from now (1454523189198)
,D/GetConfigurationSnapshotOperation( 1730): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1730): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 48498(2MB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 14MB/23MB, paused 10.204ms total 142.249ms
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
,D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/NotificationManager(  838): android: cancelAsUser(2) by android
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  838): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/PowerManagerService(  838): ALS enabled for SRE
,D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (30307 ms ago)
D/qdlights(  838): set_light_backlight: 254
,D/qdlights(  838): set_light_backlight: 251
D/qdlights(  838): set_light_backlight: 248
,D/qdlights(  838): set_light_backlight: 244
,D/qdlights(  838): set_light_backlight: 241
,D/qdlights(  838): set_light_backlight: 238
,D/qdlights(  838): set_light_backlight: 234
,D/qdlights(  838): set_light_backlight: 231
,D/qdlights(  838): set_light_backlight: 228
,D/qdlights(  838): set_light_backlight: 224
,D/qdlights(  838): set_light_backlight: 221
,D/qdlights(  838): set_light_backlight: 218
,D/qdlights(  838): set_light_backlight: 214
,D/qdlights(  838): set_light_backlight: 211
,D/qdlights(  838): set_light_backlight: 208
,D/qdlights(  838): set_light_backlight: 204
,D/qdlights(  838): set_light_backlight: 201
,D/qdlights(  838): set_light_backlight: 198
,D/qdlights(  838): set_light_backlight: 194
,D/qdlights(  838): set_light_backlight: 191
,D/qdlights(  838): set_light_backlight: 188
,D/qdlights(  838): set_light_backlight: 184
,D/qdlights(  838): set_light_backlight: 181
,D/qdlights(  838): set_light_backlight: 178
,D/qdlights(  838): set_light_backlight: 174
,D/qdlights(  838): set_light_backlight: 171
,D/qdlights(  838): set_light_backlight: 168
,D/qdlights(  838): set_light_backlight: 164
,D/qdlights(  838): set_light_backlight: 161
,D/qdlights(  838): set_light_backlight: 158
,D/qdlights(  838): set_light_backlight: 154
,D/qdlights(  838): set_light_backlight: 151
,D/qdlights(  838): set_light_backlight: 148
,D/qdlights(  838): set_light_backlight: 144
,D/qdlights(  838): set_light_backlight: 141
,D/qdlights(  838): set_light_backlight: 138
,D/qdlights(  838): set_light_backlight: 134
,D/qdlights(  838): set_light_backlight: 131
,D/qdlights(  838): set_light_backlight: 128
,D/qdlights(  838): set_light_backlight: 124
,D/qdlights(  838): set_light_backlight: 121
,D/qdlights(  838): set_light_backlight: 118
,D/qdlights(  838): set_light_backlight: 114
,D/qdlights(  838): set_light_backlight: 111
,D/qdlights(  838): set_light_backlight: 108
,D/qdlights(  838): set_light_backlight: 104
,D/qdlights(  838): set_light_backlight: 101
,D/qdlights(  838): set_light_backlight: 98
,D/qdlights(  838): set_light_backlight: 94
,D/qdlights(  838): set_light_backlight: 91
,D/qdlights(  838): set_light_backlight: 88
,D/qdlights(  838): set_light_backlight: 84
,D/qdlights(  838): set_light_backlight: 81
,D/qdlights(  838): set_light_backlight: 78
,D/qdlights(  838): set_light_backlight: 74
,D/qdlights(  838): set_light_backlight: 71
,D/qdlights(  838): set_light_backlight: 68
,D/qdlights(  838): set_light_backlight: 64
,D/qdlights(  838): set_light_backlight: 61
,D/qdlights(  838): set_light_backlight: 58
,D/qdlights(  838): set_light_backlight: 54
,D/qdlights(  838): set_light_backlight: 51
,D/qdlights(  838): set_light_backlight: 48
,D/qdlights(  838): set_light_backlight: 44
,D/qdlights(  838): set_light_backlight: 41
,D/qdlights(  838): set_light_backlight: 38
,D/qdlights(  838): set_light_backlight: 34
,D/qdlights(  838): set_light_backlight: 31
,D/qdlights(  838): set_light_backlight: 28
,D/qdlights(  838): set_light_backlight: 24
,D/qdlights(  838): set_light_backlight: 21
,D/qdlights(  838): set_light_backlight: 18
,D/qdlights(  838): set_light_backlight: 14
,D/qdlights(  838): set_light_backlight: 11
,D/qdlights(  838): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 154852571248; DSPS: 5172143; Offset : -2997323102
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  838): ALS enabled for SRE
D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (37292 ms ago)
I/PowerManagerService(  838): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  838): ALS enabled for SRE
D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (37307 ms ago)
,W/ContextImpl(  838): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  838): Sleeping (uid 1000)...
,D/LPWGController(  838): [updateScreenState] screen on = false
D/LPWGController(  838): disable proximity sensor
D/LPWGController(  838): enable proximity sensor
,I/SensorManager(  838): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@f4e2242] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  838): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  838): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  838): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  838): activate: handle is 48, enable
,V/sensors_hal_Ctx(  838): activate sensors is 1400000000000
D/sensors_hal_Thresh(  838): enable: handle=48
I/sensors_hal_SAM(  838): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  838): waitForResponse: timeout=1000
V/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  838): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  838): enable: Received response: 0
D/PowerManagerServiceEx(  838): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (37371 ms ago)
I/Adreno-EGL(  838): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  838): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  838): Build Date: 03/02/15 Mon
I/Adreno-EGL(  838): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  838): Remote Branch: 
I/Adreno-EGL(  838): Local Patches: 
I/Adreno-EGL(  838): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1401 us)
,I/Sensors (  421): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  838): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  838): processInd: handle 48, count=1
V/sensors_hal_Thresh(  838): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  838): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  838): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  838): poll: count: 256
I/sensors_hal_Ctx(  838): poll: released wakelock sensor_ind
D/sensors_hal_Util(  838): waitForResponse: timeout=0
D/LPWGController(  838): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  838): current mode = 1  value = 1 1
I/LPWGController(  838): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  838): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  838): set_light_backlight: 0
,I/SensorManager(  838): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  838): activate: handle is 46, disable
V/sensors_hal_Ctx(  838): activate sensors is 1000000000000
D/sensors_hal_LP2(  838): enable: handle=46
D/sensors_hal_LP2(  838): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  838): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  838): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  838): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  838): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,V/ActivityManager(  838): Display changed displayId=0
,D/DSDPConnection( 1748): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  838): Excessive delay in setPowerMode(): 183ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  838): Got set_interactive hint
D/KeyguardViewMediator( 1367): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1367): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
D/KeyguardViewMediator( 1367): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1367): handleNotifyScreenOff
D/WifiServerServiceExt(  838): sendKtScanInterval  mRtspPlay : false
,D/ScreenTurnOffBySensor( 1367): unregisterProximitySensor
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 838
D/StatusBarWindowView( 1367): onScreenTurnedOff why = 3
,D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: enter: screen_state=on
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  278): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/WifiServerServiceExt(  838): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1367): handleTimeUpdate
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,D/GpsLocationProvider(  838): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:true
I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
,D/LNfcService( 1783): action : android.intent.action.SCREEN_ON
I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1800): stopPatternFlashing()
D/Cliptray Service( 1800): lockStatus = 0
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): updateLightsLocked : turn off led
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/NfcServiceNXP( 1783): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1783): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
,D/NfcService( 1783): newParams.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 3
D/NfcService( 1783): Discovery configuration equal, not updating.
D/LEDHandler( 1800): RESTART MSG
,D/SplitWindow(  838): check instance of lgWin Window{14a4d889 u0 SearchPanel}
,D/Ulp_jni (  838): JNI:system_update. Event-0
,D/InputDispatcher(  838): Window went away: Window{2d7025a2 u0 SearchPanel}
I/[SystemUI]Clock( 1367): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1367): time changed, timezoneChanged : false
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2697): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:13:21
,D/WeatherService( 2697): 2 : ACTION screen on
D/WeatherService( 2697): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2697): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2697): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 19:13:21
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): ACTION_SCREEN_ON
D/AppCleanupService( 4105): android.intent.action.SCREEN_ON
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 838
,D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
D/WifiController(  838): CMD_SCREEN_OFF 
D/WifiController(  838): shouldWifiStayAwake TRUE
I/Sensors (  421): sns_pwr.c(301):releasing wakelock
D/GpsLocationProvider(  838): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:false
,I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1800): stopPatternFlashing()
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1800): clear
D/LNfcService( 1783): action : android.intent.action.SCREEN_OFF
I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1800): updateLightsLocked : turn on led
E/LEDService( 1800): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1800): Can't handle this request of patternId:0
D/LEDHandler( 1800): RESTART MSG
D/NfcServiceNXP( 1783): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1873): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
D/WeatherService( 2697): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:13:21
,D/WeatherService( 2697): 2 : ACTION screen off
D/WeatherService( 2697): 2 : TimeTick Receiver Unregister
D/WeatherService( 2697): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 19:13:21
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): ACTION_SCREEN_OFF
D/AppCleanupService( 4105): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4105): AppUsageStatsSaveTask
E/NxpNfcJni( 1783): getReconnectState = 0x0
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): newParams.techmask= mTechMask: 0
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 1
E/NxpNfcJni( 1783): getReconnectState = 0x0
,D/KeyguardViewMediator( 1367): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{720208e type 2 when 163248 com.android.systemui} when 163248
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1748): getCallState : 0
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1367): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1367): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 174853244313; DSPS: 5827525; Offset : -2997321162
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{e6d50af type 2 when 183630 android} when 183630
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1367): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1367): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1367): On Skip Timer : true
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1367): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1367): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  838): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{97adcbc type 2 when 189218 com.google.android.gms} when 189218
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 194854008419; DSPS: 6482910; Offset : -2997320283
,I/ClearcutLoggerApiImpl( 1730): disconnect managed GoogleApiClient
,I/[SystemUI]TimeTickManager( 1367): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1367): called onTimeUpdated()
I/[SystemUI]Clock( 1367): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1367): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 214854758204; DSPS: 7138295; Offset : -2997333177
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 234855436789; DSPS: 7793677; Offset : -2997326682
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1367): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1367): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1367): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1367): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1367): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1367): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1367): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  838): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 254856191209; DSPS: 8449062; Offset : -2997334680
,I/[SystemUI]TimeTickManager( 1367): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1367): called onTimeUpdated()
I/[SystemUI]Clock( 1367): called onTimeUpdated()
I/LgeClockWidgetControlView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
I/[SystemUI]DateView( 1367): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1367): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 274856961722; DSPS: 9104447; Offset : -2997328774
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5642): TAP version 13
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 1 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # multiplex can send data
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 2 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 3 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 4 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # enqueue and run in order
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 5 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 6 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 7 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # basic
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 8 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-,log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 9 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 10 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # another
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 11 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 12 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 13 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/j,xcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 14 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 15 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 16 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 17 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modu,les/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 18 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 19 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 20 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 21 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 22 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):      , exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # failed to get mobile documents path
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 23 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 24 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 25 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 26 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 27 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 28 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxc,ore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #init should register the networkChanged event
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 29 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 30 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
,I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 31 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startBroadcasting should throw on null device name
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 32 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 33 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 34 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 35 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I,/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 36 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 37 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 38 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 39 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 40 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 41 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     operator: error,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown,
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 42 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 43 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startBroadcasting should throw on negative port
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 44 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 45 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 46 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startBroadcasting should throw on too large port
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 47 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5,642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # teardown,
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 48 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 49 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5642): ,
I/jxcore-log( 5642): not ok 50 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): ,
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 51 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 52 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 53 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 54 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 55 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcor,e-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 56 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 57 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 58 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 59 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 60 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 61 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 62 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):    ,   bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 63 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 64 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 65 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 66 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 67 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 68 ReferenceError: _name is not defined,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 69 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 70 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 71 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 72 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 73 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 74 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 75 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 76 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 77 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 78 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 79 ReferenceError: _name is not defined,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 80 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): ,
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
,I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 81 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 82 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     operator: error,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # ThaliEmitter throws on disconnect to bad peer
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 83 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 84 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 85 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 86 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 87 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 88 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
,I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startUpdateAdvertisingAndListening should use different USN after every invocation
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 89 ReferenceError: _name is not defined
,I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined],
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 90 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 91 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # messages with invalid location or USN should be ignored
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 92 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 93 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 94 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tap,e/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # verify that Thali-specific messages are filtered correctly
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 95 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ...,
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 96 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 97 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # #start should fail if called twice in a row,
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 98 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 99 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
,I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 100 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startUpdateAdvertisingAndListening should fail invalid router has been passed
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 101 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 102 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 103 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startUpdateAdvertisingAndListening should fail if router server starting fails
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 104 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/,www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 105 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): ,
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 106 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startUpdateAdvertisingAndListening should start hosting given router object
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 107 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 108 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 109 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-,
,I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
,I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): ,
I/jxcore-log( 5642): # #stop can be called multiple times in a row
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 110 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
,I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 111 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
,I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): ,
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): ,
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 112 ReferenceError: _name is not defined,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #startListeningForAdvertisements can be called multiple times in a row
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 113 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 114 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 115 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # #stopListeningForAdvertisements can be called multiple times in a row,
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 116 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): ,
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       ,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): ,
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
I/jxcore-log( 5642): not ok 117 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
,I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 118 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): ,
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # #stopAdvertisingAndListening can be called multiple times in a row
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 119 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 120 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # setup
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 121 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       [ReferenceError: _name is not defined],
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:61:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28,
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): # functions are run from a queue in the right order
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): not ok 122 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): ,
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:84:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): # teardown
I/jxcore-log( 5642): 
I/jxcore-log( 5642): not ok 123 ReferenceError: _name is not defined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):   ---
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     operator: error
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     expected: |-
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       undefined
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     actual: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       [ReferenceError: _name is not defined]
I/jxcore-log( 5642): 
I/jxcore-log( 5642):     stack: |-
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       declareTest/<@/data/data/com.test.thalitest/files/www/jxcore/lib/thali-tape.js:92:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):       exports.Test.prototype.run@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape-catch/index.js:17:5
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       bound@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/test.js:61:28
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       next@/data/data/com.test.thalitest/files/www/jxcore/node_modules/tape/lib/results.js:70:13
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       $v@timers.js:363:1
I/jxcore-log( 5642): 
I/jxcore-log( 5642):       
I/jxcore-log( 5642): 
,I/jxcore-log( 5642):   ...
I/jxcore-log( 5642): 
I/jxcore-log( 5642): Tests Complete
I/jxcore-log( 5642): 
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  838): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  838): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  838): tsOffsetIs: Apps: 294857644318; DSPS: 9759829; Offset : -2997315899
,I/jxcore-log( 5642): Toggling radios to false
I/jxcore-log( 5642): 
,D/BluetoothManagerService(  838): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  838): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2df97445 mBinding = false
,D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  838): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  838): JNI:system_update. Event-4
D/BluetoothManagerService(  838): Message: 2
D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
D/BluetoothManagerService(  838): Sending off request.
D/WifiServiceImplEx(  838): setWifiEnabled: false pid=5642, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  838): setWifiEnabled: false pid=5642, uid=10316
,D/BluetoothAdapterService(858615765)( 1987): disable() called...
D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
D/BluetoothAdapterState( 1987): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 1987): Setting state to 13
I/BluetoothAdapterState( 1987): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(858615765)( 1987): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothAdapterProperties( 1987): onBluetoothDisable()
,E/WifiStateMachine(  838): WifiStateMachine: Leaving Connected state
I/jxcore-log( 5642): Radios toggled
I/jxcore-log( 5642): 
I/BluetoothAdapterState( 1987): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/bt-btif ( 1987): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 1987): Scan Mode:20
D/BluetoothAdapterState( 1987): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 1987): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 1987): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 1987): btsock_ctrl_hci_cleanup(L202): poll handle:4
,I/bt-btif ( 1987): BTA_JvDeleteRecord
D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
D/BluetoothManagerService(  838): Message: 60
D/LocationManagerService(  838): getAllProviders()=[passive, gps, network]
E/WifiConfigStore(  838): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  838): Bluetooth State Change Intent: 12 -> 13
D/Ulp_jni (  838): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  838): JNI:system_update. Event-4
I/bt-btif ( 1987): BTA_JvRfcommStopServer
,I/bt-btif ( 1987): BTA_JvDeleteRecord
I/bt-btif ( 1987): BTA_JvRfcommStopServer
W/bt-btif ( 1987): invalid rfc slot id: 1
W/bt-btif ( 1987): invalid rfc slot id: 2
D/IOP_DB_BT( 1987): db_close: nbr users 0
D/IOP_DB_BT( 1987): db_close: free database
D/btif_config_util( 1987): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 1987): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 1987): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 1987): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:G3s-1
D/btif_config_util( 1987): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 1987): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
W/bt-btif ( 1987): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/btif_config_util( 1987): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 1987): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 1987): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 1987): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
,D/btif_config_util( 1987): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 1987): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 1987): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 1987): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 1987): enum_config(L344): out, value:x
D/btif_config_util( 1987): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 1987): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 1987): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 1987): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 1987): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 1987): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 1987): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 1987): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 1987): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 1987): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 1987): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 1987): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 1987): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300,): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:�
D/btif_config_util( 1987): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 1987): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
,D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1987): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:$
D/btif_config_util( 1987): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 1987): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, ,key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int,
,D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
,D/btif_config_util( 1987): enum_config(L344): out, value:�,
,D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:A5-1
,D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
,D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
,D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
,D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
,D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
,D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae ,
,E/bt-btif ( 1987): btif_hf_upstreams_evt: wrong handle = 1280 
W/bt-obex ( 1987): Ignore event 10 in state 1
I/bt-btif ( 1987): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 1987): ops_state_cb(L223):  ops_state_cb state:3
,W/bt-obex ( 1987): Ignore event 10 in state 1
D/btif_config_util( 1987): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
,D/btif_config_util( 1987): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:#,
,D/btif_config_util( 1987): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 1987): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
,D/btif_config_util( 1987): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
,D/btif_config_util( 1987): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1987): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
,D/btif_config_util( 1987): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
,D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:�
D/btif_config_util( 1987): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:XT1072
D/btif_config_util( 1987): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
,D/btif_config_util( 1987): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
,D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/OppService( 1987): onOpsStateChange() :3
,D/btif_config_util( 1987): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
,V/BluetoothPbapService( 1987): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/LGWifiP2pService(  838): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/btif_config_util( 1987): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
,D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
,D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
,D/btif_config_util( 1987): enum_config(L344): out, value:a
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:S5-1
,D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int,
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
,D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
,D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string,
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
,D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
,D/btif_config_util( 1987): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
,D/btif_config_util( 1987): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
,D/btif_config_util( 1987): enum_config(L344): out, value:	a
D/btif_config_util( 1987): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:G4-1
,D/btif_config_util( 1987): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
,D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1987): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
,D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:a
D/btif_config_util( 1987): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
,D/btif_config_util( 1987): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 1987): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
,D/btif_config_util( 1987): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:�
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e,:51:18:22, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:�
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:,JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:A
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1987): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:	a
D/btif_config_util( 1987): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:Note3-1
D/btif_config_util( 1987): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:�
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:A3-1
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1987): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:�
D/btif_config_util( 1987): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:XT1039
D/btif_config_util( 1987): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/OppService( 1987): Recieved MESSAGE_OPS_DISABLE
D/btif_config_util( 1987): enum_config(L344): out, value:	a
D/btif_config_util( 1987): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 1987): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 1987): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 1987): enum_config(L300): in, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:T\���K�`�D�`�D�
D/btif_config_util( 1987): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:���
D/btif_config_util( 1987): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:ALE-L21
D/btif_config_util( 1987): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Service, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 1987): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 1987): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:#
D/btif_config_util( 1987): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:onem9-1
D/btif_config_util( 1987): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:00:00:00:00:08:00, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:00:00:00:00:08:00, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:08:00, value name:DevType, value type:int
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/btif_config_util( 1987): enum_config(L343): out, key:94:06:6b:a0:e3:f1, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:08:00:00:00:67:73, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:00:00:00:67:73, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:08:00:00:00:67:73, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:00:00:00:67:73, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:00:00:00:67:73, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
D/btif_config_util( 1987): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:38:94:96:b5:06:dc, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:�
D/btif_config_util( 1987): enum_config(L300): in, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:38:94:96:b5:06:dc, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:Galaxy S5-2
D/btif_config_util( 1987): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:DevType, value type:int
D/LGBluetoothAPIService( 1800): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/btif_config_util( 1987): enum_config(L343): out, key:38:94:96:b5:06:dc, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:38:94:96:b5:06:dc, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:38:94:96:b5:06:dc, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:38:94:96:b5:06:dc, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Manufacturer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Manufacturer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpVer
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:LmpSubVer, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:00:00:00:00:5a:ad, value:LmpSubVer
D/btif_config_util( 1987): enum_config(L344): out, value:�
D/btif_config_util( 1987): enum_config(L300): in, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:00:00:00:00:5a:ad, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:A3-1
D/btif_config_util( 1987): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:Z
D/btif_config_util( 1987): enum_config(L300): in, key:00:00:00:00:5a:ad, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:00:00:00:00:5a:ad, value:DevType,
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:JustWorks, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:00:00:00:00:5a:ad, value:JustWorks
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:5a:ad, value name:GlobalTrust, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:00:00:00:00:5a:ad, value:GlobalTrust
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:00:00:00:67:53, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:08:00:00:00:67:53, value:DevType
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:08:00:00:00:67:53, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:08:00:00:00:67:53, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
,D/btif_config_util( 1987): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:Name
,D/btif_config_util( 1987): enum_config(L344): out, value:$��
D/btif_config_util( 1987): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevClass
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:`��
,D/btif_config_util( 1987): enum_config(L300): in, key:84:24:c0:aa:ff:ff, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:84:24:c0:aa:ff:ff, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:84:24:c0:aa:ff:ff, value:DevType
,D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevClass
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:���
,D/btif_config_util( 1987): enum_config(L300): in, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:a0:01:c0:b4:bc:d6, value name:DevType, value type:int
,D/btif_config_util( 1987): enum_config(L343): out, key:a0:01:c0:b4:bc:d6, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
,D/btif_config_util( 1987): enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevClass
,D/btif_config_util( 1987): enum_config(L344): out, value:�_
D/btif_config_util( 1987): enum_config(L300): in, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:94:16:79:a0:e3:01, value name:DevType, value type:int
,D/btif_config_util( 1987): enum_config(L343): out, key:94:16:79:a0:e3:01, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:00:00:00:00:41:9e, value:Name
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:00:00:00:00:41:9e, value:Name
D/btif_config_util( 1987): enum_config(L344): out, value:4g�
,D/btif_config_util( 1987): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevClass
,D/btif_config_util( 1987): enum_config(L344): out, value:��f
,D/btif_config_util( 1987): enum_config(L300): in, key:00:00:00:00:41:9e, value:DevType
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:00:00:00:00:41:9e, value name:DevType, value type:int
,D/btif_config_util( 1987): enum_config(L343): out, key:00:00:00:00:41:9e, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/btif_config_util( 1987): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:Name
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:Name, value type:string
D/btif_config_util( 1987): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:Name
,D/btif_config_util( 1987): enum_config(L344): out, value:4g�������v��
D/btif_config_util( 1987): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevClass, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 1987): enum_config(L344): out, value:��\
D/btif_config_util( 1987): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevType
,D/btif_config_util( 1987): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevType, value type:int
D/btif_config_util( 1987): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevType
D/btif_config_util( 1987): enum_config(L344): out, value:
D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
D/DhcpStateMachine(  838): RunningState{ when=-22ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
,I/BluetoothMapService( 1987): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1987): STATE_TURNING_OFF
V/BluetoothMapService( 1987): Handler(): got msg=4
D/BluetoothMapService( 1987): MAP Service closeService in
D/BluetoothMapMasInstance( 1987): MAP Service shutdown
,V/BluetoothMapMasInstance( 1987): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 1987): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 1987): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 1987): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 1987): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 1987): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 1987): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 1987): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,D/LGBluetoothMapAdapter( 1987): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1987): MAP Service closeService out
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1367): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,V/NativeCrypto( 1730): Read error: ssl=0xb045da00: I/O error during system call, Connection timed out
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/NativeCrypto( 1730): SSL shutdown failed: ssl=0xb045da00: I/O error during system call, Broken pipe
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  838): NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
,D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  838): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=8096 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/WifiNetworkAgent(  838): NetworkAgent: NetworkAgent channel lost
D/LGWifiP2pService(  838): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  838): P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiHS20(  838): hidePasspointNotification off =false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  838): hidePasspointNotification off =false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  838): P2pDisablingState
D/LGWifiP2pService(  838): P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): p2p socket connection lost
D/LGWifiP2pService(  838): P2pDisabledState
D/WifiScanningService(  838): SCAN_AVAILABLE : 1
D/RttService(  838): SCAN_AVAILABLE : 1
D/WifiScanningService(  838): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/RttService(  838): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  838): DefaultState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WfdsService( 1800): WifiP2pState is changed : false
D/WfdsService( 1800): WfdsEnabledState: Receive the WFDS_DISABLE message
,D/WfdsJNI ( 1800): doCommand: P2P_STOP_FIND
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:15:40.232 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:15:40.242 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WfdsService( 1800): Set the WFDS Monitor: false
D/ConnectivityService(  838): reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10006
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): ValidatedState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=-2ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Forcing reevaluation
D/WfdsMonitor( 1800): WFDS Monitor is stopped
D/CtrlSupplicant( 1800): Received on exit socket, terminate
E/CtrlSupplicant( 1800): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1800): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1800): WfdsMonitorThread is received the interrupt - closing
D/WfdsService( 1800): STATE : WfdsDisabledState - enter
D/WfdsService( 1800): WFDS: Scanner is paused
D/WfdsDiscoveryStore( 1800): Clear Discovery Method Map: ScanAlwaysMode false
W/WfdsSession:Controller( 1800): DefaultState - msg [9441355] is not handled
D/CommandListener(  274): Clearing all IP addresses on wlan0
D/ConnectivityService(  838): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  838): disableDataServiceNotify
D/DSQN    (  838): stop dsqn bin
,D/WifiHS20(  838): hidePasspointNotification off =false
W/Settings(  838): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  838): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  838): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:15:40.28 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServiceExtension( 1800): isInternetCheckAvailable return false
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:15:40.285 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  838): WIFI_STATE_CHANGED_ACTION [0]
D/WifiServerServiceExt(  838): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  838): setSupplicantStateDISCONNECTED
,D/ConnectivityService(  838): notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  838): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  838): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  838): Disconnected - quitting
,D/CSLegacyTypeTracker(  838): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  838): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  838): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/DhcpStateMachine(  838): StoppedState
D/DhcpStateMachine(  838): StoppedState{ when=-103ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  838): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  838): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  838): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  838): Removing idletimer
W/Settings(  838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  838): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WIFI    (  838): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  838):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1367): CM callback handler got msg 524292
,D/TelephonyNetworkFactory-1( 1748): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
V/NetworkPolicy(  838): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1836): |CORE| No family connected
D/Tethering(  838): MasterInitialState.processMessage what=3
D/Tethering(  838): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1836): |CORE| No family connected
I/QCNEJ   ( 1836): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
V/NetworkPolicy(  838): [LG_RESTRICTED] !!!isConnected  type  :1
,I/QCNEJ   ( 1836): |CORE| sendDefaultNwMsg: default = -1
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
,I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 5
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 10
I/wpa_supplicant( 2754): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2754): monitor socket send errors count : 1
I/wpa_supplicant( 2754): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1800-2\x00 that cannot receive messages
I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 7
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.p2p.STATE_CHANGED at null
I/[SystemUI]StatusBar.NetworkController( 1367): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1367): Remote
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.WIFI_STATE_CHANGED at null
I/wpa_supplicant( 2754): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 2754): USIM:  scard_deinit function
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ResourcesManager( 8096): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8096): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8096): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 8096): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 8096): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  838): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  838): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/TelephonyIcons( 1367): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1367): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1367): null signal icon name: drawable/stat_sys_signal_null
I/art     ( 1367): Background sticky concurrent mark sweep GC freed 59054(3MB) AllocSpace objects, 52(1761KB) LOS objects, 17% free, 24MB/29MB, paused 2.928ms total 198.014ms
,I/[SystemUI]LGNetworkController( 1367): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/IndexDatabaseHelper( 8096): Using schema version: 115
,I/IndexDatabaseHelper( 8096): Index is fine
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 5
I/wpa_supplicant( 2754): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  838): InitialState.processMessage what=4
,D/Tethering(  838): sendTetherStateChangedBroadcast 0, 0, 0
,W/ContextImpl( 8096): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 1987): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1987): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1987): ***********state = 13
V/BluetoothPbapReceiver( 1987): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 1987): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1987): state: 13
V/BluetoothPbapService( 1987): Pbap Service closeService in
V/BluetoothPbapService( 1987): successfully stopped pbap service
V/BluetoothPbapService( 1987): Pbap Service closeService out
V/BluetoothPbapService( 1987): Pbap Service onDestroy
V/BluetoothPbapService( 1987): Pbap Service closeService in
V/BluetoothPbapService( 1987): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 1987): [BTUI] cleanup
V/WiFiOffLoadBroadcast( 8096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WfdsService( 1800): Supplicant Connection state is changed : false
D/WifiOffDelayIfNotUsed(  838): stopMonitoring
D/WfdsService( 1800): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1800): Set the WFDS Monitor: false
D/WfdsMonitor( 1800): WFDS Monitor is stopped
I/QCNEJ   ( 1836): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
,I/QCNEJ   ( 1836): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-03 19:15:40.648 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1836): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings( 1730): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt(  838): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt(  838): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  838): batteryPsActivateMsgHandler : this is not treated
,I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1367): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.wifi.WIFI_STATE_CHANGED at null
,D/WiFiOffLoadBroadcast( 8096): MCCMNC not supported: null
D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f7708a8:true
,D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
,D/BluetoothManagerService(  838): Message: 30
,D/BluetoothManagerService(  838): Message: 30
,D/LocalBluetoothProfileManager( 8096): Adding local MAP profile
D/BluetoothMap( 8096): Create BluetoothMap proxy object
D/BluetoothManagerService(  838): Message: 30
D/BluetoothManagerService(  838): Message: 30
,D/LocalBluetoothProfileManager( 8096): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 8096):  get() - isFeatureLoaded : false
D/LGBluetoothUserBindClient( 8096): [BTUI] initUserBindClient
,W/ContextImpl( 8096): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 8096): finishStartingService: stopping service
,D/BluetoothInputDevice( 8096): Proxy object connected
D/HidProfile( 8096): Bluetooth service connected
,D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
D/BluetoothPan( 8096): BluetoothPAN Proxy object connected
D/PanProfile( 8096): Bluetooth service connected
D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
D/BluetoothMap( 8096): Proxy object connected
D/MapProfile( 8096): Bluetooth service connected
D/BluetoothMap( 8096): getConnectedDevices()
D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
D/BluetoothMap( 8096): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 8096): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 8096): [BTUI] cancel All Notification
I/NotificationManager( 8096): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 8096): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 8096): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 8096): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 8096): com.android.settings: cancel(-1000031) by com.android.settings
,I/NotificationManager( 8096): com.android.settings: cancel(-1000041) by com.android.settings
I/ActivityManager(  838): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8125 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BluetoothPermissionRequest( 8096): onReceive
,D/LGBluetoothAuthorization( 8096): [BTUI] cancel All Notification
I/NotificationManager( 8096): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 8096): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 8096): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 8096): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 8096): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 8096): com.android.settings: cancel(-1000041) by com.android.settings
I/ActivityManager(  838): Killing 7780:com.android.gallery3d/u0a23 (adj 15): empty #11
,V/BluetoothOppReceiver( 1987): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 1987): [BTUI] cancel opp incoming file confirm notification
I/NotificationManager( 1987): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/BluetoothOppNotification( 1987): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 1987): com.android.bluetooth: cancel(-1) by com.android.bluetooth
W/libprocessgroup(  838): failed to open /acct/uid_10023/pid_7780/cgroup.procs: No such file or directory
V/BluetoothSapReceiver( 1987): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 1987): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,I/PCSuite ( 8125): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 8125): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 8125): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  838): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=8146 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
V/WiFiOffLoadBroadcast( 8096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 8096): MCCMNC not supported: null
I/PCSuite ( 8125): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 8125): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 8125): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,W/ResourcesManager( 8146): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  838): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=8163 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/ActivityManager(  838): Killing 7802:com.android.contacts/u0a18 (adj 15): empty #11
,W/bt_userial( 1987): select_read return size <=0:0, exiting userial_read_thread
W/bt-l2cap( 1987): L2CAP - PSM: 0x0019 not found for deregistration
D/bt_hwcfg( 1987): hw_epilog_process
W/bt-l2cap( 1987): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1987): ag scb idx 1 not allocated
E/bt-btif ( 1987): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1987): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1987): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1987): ag scb idx 1 not allocated
E/bt-btif ( 1987): BTA AG is already disabled, ignoring ...
E/bt-btif ( 1987): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 1987): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_userial_vendor( 1987): device fd = 67 close
E/bt_vendor( 1987): [BTUI] Proto is enabled. Set Proto disable!!
,I/ActivityManager(  838): Killing 7822:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/PowerManagerServiceEx(  838): acquireWakeLockInternal: lock=889479013, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=838
D/AuthorizationBluetoothService( 1730): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{25f60633 type 2 when 298688 com.google.android.gms} when 298688
,W/libprocessgroup(  838): failed to open /acct/uid_10069/pid_7822/cgroup.procs: No such file or directory
W/libprocessgroup(  838): failed to open /acct/uid_10018/pid_7802/cgroup.procs: No such file or directory
I/GKI_LINUX( 1987): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1987): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1987): GKI_destroy_task(): task [BTU] terminated
I/bt-btif ( 1987): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1987): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1987): Unable to read settings
D/BtSettings.ProfileConfig( 1987): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 1987): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 1987): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 1987): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 1987): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 1987): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 1987): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 1987): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 1987): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 1987): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 1987): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 1987): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(858615765)( 1987): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
,D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(858615765)( 1987): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 1987): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(858615765)( 1987): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(858615765)( 1987): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(858615765)( 1987): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
I/LGBluetoothHfpAdapter( 1987): [BTUI] LGBluetoothHfpAdapter cleanup
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(858615765)( 1987): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/HeadsetStateMachine( 1987): Exit Disconnected: -1
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 1987): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(858615765)( 1987): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
W/LGBluetoothHeadsetServiceJni( 1987): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@332d6fd5
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
D/BtSettings.ProfileC,onfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/ResourcesManager( 8163): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/BluetoothAdapterService( 1987): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(858615765)( 1987): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothHeadset(  838): Proxy object disconnected
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
D/A2dpService( 1987): Received stop request...Stopping profile...
W/BluetoothAdapterService( 1987): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(858615765)( 1987): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/AudioService(  838): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1748): Proxy object disconnected
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 1987): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1987): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 1987): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(858615765)( 1987): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterState( 1987): Stopping profile services that were post enabled
D/A2dpStateMachine( 1987): Exit Disconnected: -1
D/BluetoothHeadset( 1748): Proxy object disconnected
D/BluetoothHeadset( 1748): Proxy object disconnected
,D/LGBluetoothA2dpAdapter( 1987): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 1987): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 1987): [BTUI] terminate
D/BluetoothManagerService(  838): Message: 31
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@332d6fd5
D/BluetoothA2dp(  838): Proxy object disconnected
D/AudioService(  838): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 1987): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@332d6fd5
D/HealthService( 1987): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@332d6fd5
D/BluetoothInputDevice( 8096): Proxy object disconnected
D/HidProfile( 8096): Bluetooth service disconnected
D/PanService( 1987): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@332d6fd5
D/BluetoothPan( 8096): BluetoothPAN Proxy object disconnected
D/BtGatt.DebugUtils( 1987): handleDebugAction() action=null
D/PanProfile( 8096): Bluetooth service disconnected
D/BtGatt.GattService( 1987): Received stop request...Stopping profile...
D/BtGatt.GattService( 1987): stop()
D/BtGatt.AdvertiseManager( 1987): advertise clients cleared
D/LGBluetoothGattAdapter( 1987): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@332d6fd5
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1987): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 1987): Received stop request...Stopping profile...
D/BluetoothMapService( 1987): stop()
D/BluetoothMapEmailAppObserver( 1987): deinitObservers()
D/BluetoothMapEmailAppObserver( 1987): removeReceiver()
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@332d6fd5
D/BluetoothMap( 8096): Proxy object disconnected
D/MapProfile( 8096): Bluetooth service disconnected
D/HeadsetStateMachine( 1987): Unbinding service...
D/HeadsetPhoneState( 1987): [BTUI] listenForPhoneState : start = false
,D/LGBluetoothHfpManager( 1987): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 1987): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1987): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 1987): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1987): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 1987): [BTUI] LGBluetoothHfpAdapter cleanup
D/SapService( 1987): Received stop request...Stopping profile...
D/SapService( 1987): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 1987): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 1987): [BTUI] terminateSapManager
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@332d6fd5
D/**BluetoothFTPService( 1987): Received stop request...Stopping profile...
D/**BluetoothFTPService( 1987): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 1987): closeFtpServerNative
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@332d6fd5
D/**OppService( 1987): Received stop request...Stopping profile...
D/OppService( 1987): Stopping Bluetooth OppService
D/OppService( 1987): cleanup OPP Service
W/BluetoothOPPServiceJni( 1987): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 1987): Cleaning up Bluetooth OPP callback object
D/OppService( 1987): remove callbacks and handler
D/LGBluetoothOppAdapter( 1987): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 1987): cleanup done
D/BluetoothAdapterService( 1987): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@332d6fd5
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1987): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/BluetoothA2dpServiceJni( 1987): cleanupNative
I/GKI_LINUX( 1987): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1987): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1987): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1987): Profile still running:, com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHidServiceJni( 1987): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 1987): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1987): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/LgeBluetoothSimManager( 1748): [BTUI] SAP_DISABLE_EVT
W/BluetoothHealthServiceJni( 1987): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1987): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 1987): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
,D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1987): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 1987): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1987): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1987): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 1987): Handler(): got msg=4
D/BluetoothMapService( 1987): MAP Service closeService in
D/LGBluetoothMapAdapter( 1987): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1987): MAP Service closeService out
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1987): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 1987): cleanup()
D/BluetoothMapService( 1987): MAP Service closeService in
D/LGBluetoothMapAdapter( 1987): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1987): MAP Service closeService out
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChan,ged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1987): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 1987): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 1987): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 1987): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 1987): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothFTPService( 1987): cleanup FTP Service
V/BluetoothFTPServiceJni( 1987): closeFtpServerNative
V/BluetoothFTPServiceJni( 1987): cleanupNative
W/BluetoothFTPServiceJni( 1987): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 1987): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 1987): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 1987): cleanup done
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - Message: 1
D/BluetoothAdapterService(858615765)( 1987): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 1987): isTurningOnRadio()=false
D/BluetoothAdapterState( 1987): isTurningOffRadio()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 1987): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 1987): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(858615765)( 1987): onProfileServiceStateChange() - All profile services stopped...
D/OppService( 1987): cleanup OPP Service
D/OppService( 1987): remove callbacks and handler
D/LGBluetoothOppAdapter( 1987): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 1987): cleanup done
D/BluetoothAdapterState( 1987): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1987): Setting state to 10
I/BluetoothAdapterState( 1987): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(858615765)( 1987): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  838): Message: 60
D/BluetoothManagerService(  838): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  838): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothHeadset( 1748): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 1987): Entering OffState
D/BluetoothHeadset( 1748): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1748): onBluetoothStateChange:, up=false
D/BluetoothMap( 8096): onBluetoothStateChange: up=false
D/BluetoothPan( 8096): onBluetoothStateChange on: false
D/BluetoothInputDevice( 8096): onBluetoothStateChange: up=false
D/BluetoothPbap( 8096): onBluetoothStateChange: up=false
D/BluetoothHeadset(  838): onBluetoothStateChange: up=false
D/BluetoothA2dp(  838): onBluetoothStateChange: up=false
D/BluetoothAdapterService(858615765)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9878653
D/BluetoothManagerService(  838): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  838): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothManagerService(  838): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  838): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService(  838): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2df97445 mBinding = false
D/BluetoothManagerService(  838): Sending unbind request.
D/BluetoothManagerService(  838): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService(858615765)( 1987): onUnbind() - calling cleanup
D/LGBluetoothAPIService( 1800): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1800): Message: 2
D/BluetoothAdapter( 1367): 222032121: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1367): 222032121: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapterService(858615765)( 1987): cleanup()
D/LGBluetoothAPIService( 1800): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@281646a1 mBinding = false
D/LGBluetoothAPIService( 1800): Sending unbind request.
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1367): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
D/LGBluetoothFeatureConfig( 8096): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 8096): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 8096): [BTUI] clear device connection state
W/ContextImpl( 8096): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/BluetoothAdapterService(858615765)( 1987): cleanup() - Cleaning up adapter native
I/bt-btif ( 1987): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 1987): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 1987): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 1987): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 1987): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 1987): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1987): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1987): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1987): GKI_exit_task 2 done
I/GKI_LINUX( 1987): GKI_exit_task 1 done
I/GKI_LINUX( 1987): GKI_exit_task 0 done
I/BluetoothServiceJni( 1987): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 1987): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 1987): [BTUI] unregister observer for LG device name DB
D/BluetoothAdapterService(858615765)( 1987): cleanup() - Bluetooth process exited normally.
D/BluetoothAdapterService(858615765)( 1987): cleanup() done
D/BluetoothAdapter( 1730): 161039912: getState() :  mService = null. Returning STATE_OFF
D/DockEventReceiver( 8096): finishStartingService: stopping service
D/BluetoothAdapter( 1730): 161039912: getState() :  mService = null. Returning STATE_OFF
I/art     ( 1987): System.exit called, status: 0
I/AndroidRuntime( 1987): VM exiting with result code 0, cleanup skipped.
V/AudioFlinger(  278): 1987 died, releasing its sessions
V/AudioFlinger(  278):  pid 1748 @ 0
V/AudioFlinger(  278):  pid 3260 @ 1
V/AudioFlinger(  278):  pid 3260 @ 2
D/LGBluetoothUserBindClient( 8096): [BTUI] onServiceDisconnected
D/FMFRW_FmProxy( 1800): Fm Proxy object disconnected
,I/ActivityManager(  838): Process com.android.bluetooth (pid 1987) has died
W/ActivityManager(  838): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager(  838): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 11000ms
,D/BluetoothPermissionRequest( 8096): onReceive
D/LGBluetoothUtils( 8096): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 8096): cancelDiscoverableAlarm(): Enter
,I/ActivityManager(  838): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=8189 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
I/Babel_SMS( 8163): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 8163): MmsConfig.loadMmsSettings
,I/Babel_SMS( 8163): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 8163): MmsConfig.loadFromDatabase
W/ResourcesManager( 8189): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 8189): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8189): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 8189): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
,E/Babel_SMS( 8163): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 8163): MmsConfig.loadFromResources
E/Babel_SMS( 8163): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 8163): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/BluetoothAdapterApp( 8189): Loading JNI Library
E/BluetoothServiceJni( 8189): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
,D/SensorManager( 8163): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 8163): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 8163): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 8163): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 8163): found sensor: LGE Gravity Sensor, handle=29
D/BluetoothAdapterApp( 8189): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@ec392f4 Instance Count = 1
D/SensorManager( 8163): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 8163): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 8163): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 8163): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 8163): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 8163): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 8163): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 8163): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 8163): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 8163): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 8163): found sensor: Motion Accel, handle=46
I/art     ( 8163): CheckpointMarkThreadRoots callback created = 0xaaf23ee0
D/BluetoothAdapterApp( 8189): onCreate
I/LGBluetoothServiceJni( 8189): classInitNative: succeeds
D/BtSettings.ProfileConfig( 8189): [BTUI] HeadsetServiceis supported
W/Settings( 8163): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BtSettings.ProfileConfig( 8189): Adding HeadsetService
,D/BtSettings.ProfileConfig( 8189): [BTUI] A2dpServiceis supported
D/BtSettings.ProfileConfig( 8189): Adding A2dpService
D/BtSettings.ProfileConfig( 8189): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 8189): Adding HidService
D/BtSettings.ProfileConfig( 8189): [BTUI] HealthServiceis supported
D/BtSettings.ProfileConfig( 8189): Adding HealthService
D/LGBluetoothFeatureConfig( 8189): isSupportPan() :  mTargetOp=OPEN
,I/Babel_Crash( 8163): startup - clean
D/LGBluetoothFeatureConfig( 8189): isSupportPan() :  mTargetOp=OPEN
I/art     ( 8163): CheckpointMarkThreadRoots callback created = 0xaaf23ed0
D/BtSettings.ProfileConfig( 8189): [BTUI] PanServiceis supported
D/BtSettings.ProfileConfig( 8189): Adding PanService
D/BtSettings.ProfileConfig( 8189): [BTUI] GattServiceis supported
D/BtSettings.ProfileConfig( 8189): Adding GattService
D/BtSettings.ProfileConfig( 8189): [BTUI] BluetoothMapServiceis supported
D/BtSettings.ProfileConfig( 8189): Adding BluetoothMapService
V/LGBluetoothServiceAdapter( 8189): [BTUI] region:EU country:EU
D/BtSettings.ProfileConfig( 8189): [BTUI] SapServiceis supported
D/BtSettings.ProfileConfig( 8189): Adding SapService
D/BtSettings.ProfileConfig( 8189): [BTUI] FTPServiceis supported
D/BtSettings.ProfileConfig( 8189): Adding FTPService
E/BtSettings.ProfileConfig( 8189): [BTUI] HeadsetClientServiceis NOT supported
D/BtSettings.ProfileConfig( 8189): [BTUI] OppServiceis supported
D/BtSettings.ProfileConfig( 8189): Adding OppService
D/BtSettings.ProfileConfig( 8189): deviceMode from shared preference   -1
D/BtSettings.ProfileConfig( 8189): checkAndAdjustDeviceModeConfiguration deviceMode1
D/BtSettings.ProfileConfig( 8189): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 8189): Unable to read settings
D/BtSettings.ProfileConfig( 8189): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 8189): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 8189): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 8189): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 8189): 	at com.broadcom.bt.service.ProfileConfig.checkAndAdjustDeviceModeConfiguration(ProfileConfig.java:400)
D/BtSettings.ProfileConfig( 8189): 	at com.broadcom.bt.service.ProfileConfig.init(ProfileConfig.java:550)
D/BtSettings.ProfileConfig( 8189): 	at com.lge.bluetooth.adapter.LGBluetoothProfileConfigAdapter.init(LGBluetoothProfileConfigAdapter.java:30)
D/BtSettings.ProfileConfig( 8189): 	at com.android.bluetooth.btservice.AdapterApp.onCreate(AdapterApp.java:67)
D/BtSettings.ProfileConfig( 8189): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
D/BtSettings.ProfileConfig( 8189): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
D/BtSettings.ProfileConfig( 8189): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
D/BtSettings.ProfileConfig( 8189): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
D/BtSettings.ProfileConfig( 8189): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 8189): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 8189): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
D/BtSettings.ProfileConfig( 8189): 	at java.lang.reflect.Method.invoke(Native Method)
D/BtSettings.ProfileConfig( 8189): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/BtSettings.ProfileConfig( 8189): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
D/BtSettings.ProfileConfig( 8189): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,D/BtSettings.ProfileConfig( 8189): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 8189): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 8189): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 8189): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 8189): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 8189): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 8189): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/BtSettings.ProfileConfig( 8189): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 8189): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/LGBluetoothOppAdapter( 8189): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/LGBluetoothUserBindClient( 8096): [BTUI] onServiceConnected
I/Babel   ( 8163): deleted: false for 0
V/WiFiOffLoadBroadcast( 8096): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/FmServiceJni( 8189): classInitNative: succeeds
D/WiFiOffLoadBroadcast( 8096): MCCMNC not supported: null
,I/PCSuite ( 8125): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 8125): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 8125): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/FmService( 8189): FmReceiverServiceStub createdcom.broadcom.fm.fmreceiver.FmService$FmReceiverServiceStub@2100ea60servicecom.broadcom.fm.fmreceiver.FmService@3b0d3b19
D/FmNativehandler( 8189): start
D/BluetoothRadioManager( 8189): [BTUI] getRadioManager()
D/BluetoothRadioManager( 8189): [BTUI] BluetoothRadioManager()
V/WiFiOffLoadBroadcast( 8096): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothManagerService(  838): Message: 20
D/BluetoothManagerService(  838): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3313e4d9:true
W/AudioCapabilities( 8163): Unsupported mime audio/x-lg-flac
,D/WiFiOffLoadBroadcast( 8096): MCCMNC not supported: null
W/AudioCapabilities( 8163): Unsupported mime audio/adpcm
D/PCSuite ( 8125): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 8163): Unsupported mime audio/g726
,W/AudioCapabilities( 8163): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 8163): Unsupported mime audio/wma-voice
D/UsbSettingsReceiver( 8096): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 8096): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 8096): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 8096): [AUTORUN] persist.sys.usb.config = ptp_only,adb
W/VideoCapabilities( 8163): Unsupported mime video/mjpg
D/UsbSettingsReceiver( 8096): [AUTORUN] onReceive() : app userid = 0, current userid = 0
W/VideoCapabilities( 8163): Unsupported mime video/theora
D/BluetoothRadioManager( 8189): doBind: com.broadcom.bt.service.radiomanager.IBluetoothRadioManager
V/FmService( 8189): FM Service  onCreate
D/FmService( 8189): Binding service...
D/FMFRW_FmProxy( 1800): Fm proxy onServiceConnected() name = ComponentInfo{com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService}, service = android.os.BinderProxy@1c8750c6
D/UsbSettingsControl( 8096): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 8096): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 8096): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 8096): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 8096): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsControl( 8096): [AUTORUN] setTetherStatus() : status=false
W/AudioCapabilities( 8163): Unsupported mime audio/evrc
W/AudioCapabilities( 8163): Unsupported mime audio/qcelp
W/VideoCapabilities( 8163): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 8163): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 8163): Unsupported mime audio/qcelp
,W/AudioCapabilities( 8163): Unsupported mime audio/evrc
W/VideoCapabilities( 8163): Unsupported mime video/mp4v-esdp
,D/BluetoothAdapterService( 8189): Set JNI Library before classInit
I/ActivityManager(  838): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=8221 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BluetoothAdapterService(908702698)( 8189): AdapterService() - REFCOUNT: CREATED. INSTANCE_COUNT1
D/BluetoothAdapterService(908702698)( 8189): onCreate()
D/BluetoothAdapterState( 8189): make
,I/bluedroid( 8189): init
I/BluetoothAdapterState( 8189): Entering OffState
I/bte_conf( 8189): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 8189): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
E/bt_osi_config( 8189): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 8189): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
D/BTIF_CORE( 8189): [BTUI] lge_load_bluetooth_address
D/bt-btif ( 8189):  [BTUI] Load_abtddress
D/BTIF_CORE( 8189): [BTUI] lge_wait_for_load_bluetooth_address : waiting...
D/lge_bdaddr_loader( 8233): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 8233): [BTUI] bluetooth_load_bdaddress
I/LGFTMITEM( 8233): [GET_FTM][id=8], offset=16384
D/lge_bdaddr_loader( 8233): [BTUI] bdaddr to set in property : F8:95:C7:87:85:54
,I/VideoCapabilities( 8163): Unsupported profile 4 for video/mp4v-es
,E/lge_bdaddr_loader( 8233): [BTUI] bluetooth_load_bdaddress : OK => F8:95:C7:87:85:54
D/lge_bdaddr_loader( 8233): [BTUI] bdaddr_loader ::: END
,W/VideoCapabilities( 8163): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 8163): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8163): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 8163): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  838): Killing 7839:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,D/BTIF_CORE( 8189): [BTUI] lge_wait_for_load_bluetooth_address : success!
D/bt-btif ( 8189): PERSIST_BDADDR_PROPERTY is  F8:95:C7:87:85:54
D/bt-btif ( 8189): Got prior random BDA F8:95:C7:87:85:54
I/bluedroid( 8189): get_profile_interface socket
I/bluedroid( 8189): get_profile_interface map_client
E/BluetoothServiceJni( 8189): Error getting mapclient interface
I/bt-btif ( 8189): btif_get_adapter_property 2
I/bt-btif ( 8189): btif_get_adapter_property 1
,I/GKI_LINUX( 8189): gki_task_entry task_id=1 [BTIF] starting
,D/bt-btif ( 8189): btif task starting
D/bt-btif ( 8189): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 8189): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 8189): execute storage request event : 3
D/bt-btif ( 8189): btif_storage_get_adapter_property property->type:2 
I/bt-btif ( 8189): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 8189): Address is:F8:95:C7:87:85:54
I/bt-btif ( 8189): execute storage request event : 3
D/bt-btif ( 8189): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 8189): in, bd addr:, prop type:1, len:512
I/bt-btif ( 8189): HAL bt_hal_cbacks->adapter_properties_cb
W/libprocessgroup(  838): failed to open /acct/uid_10086/pid_7839/cgroup.procs: No such file or directory
,D/BluetoothAdapterProperties( 8189): Name is: G3s-1
D/BluetoothManagerService(  838): Bluetooth Adapter name changed to G3s-1
I/vclib   ( 8163): onServiceConnected
D/BluetoothManagerService(  838): Stored Bluetooth name: G3s-1
W/Babel   ( 8163): Attempted to change video mute state without an active call.
D/BluetoothAdapterService( 8189): getAdapterService() - Service not available
D/LGBluetoothServiceAdapter( 8189): [BTUI] check adapter is available - false.
D/LGBluetoothSettingsDBObserver( 8189): [BTUI] register observer for LG device name DB
D/BluetoothAdapterService(908702698)( 8189): onBind()
V/BluetoothSapReceiver( 8189): [BTUI] checkServiceStart
D/BluetoothRadioManager( 8189): onServiceConnected: connected to AdapterService com.android.bluetooth.btservice.AdapterService
I/NotificationManager( 8163): com.google.android.talk: cancel(10436) by com.google.android.talk
D/LGDMClient( 8221): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/BluetoothRadioManager( 8189): Message: 40
D/BluetoothRadioManager( 8189): MESSAGE_RADIO_SERVICE_CONNECTED: 1
D/LGDMClient( 8221): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/BluetoothRadioManager( 8189):  Turning on BT modules Radio on = false
D/LGBluetoothStateChangeReceiver( 8189): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothProfileConnectionReceiver_EasySetting( 8146): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
,D/AuthorizationBluetoothService( 1730): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/ContextImpl( 8221): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 8221): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/WiFiOffLoadBroadcast( 8096): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 8096): MCCMNC not supported: null
I/PCSuite ( 8125): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 8125): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 8125): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 8221): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,D/LGDMClient( 8221): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 8221): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  838): Killing 7218:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  838): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  838): failed to open /acct/uid_10006/pid_7218/cgroup.procs: No such file or directory
,I/ActivityManager(  838): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8253 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 8253): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8253): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@385a3e63
,D/PowerManagerServiceEx(  838): releaseWakeLockInternal: lock=889479013 [*alarm*], flags=0x0
I/ActivityManager(  838): Killing 7869:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  838): failed to open /acct/uid_10036/pid_7869/cgroup.procs: No such file or directory
,D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  838): onReceive
D/LocSvc_java(  838): got connectivity action
D/LocSvc_java(  838): broadcast - no network connections
D/LocSvc_java(  838): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  838): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  838): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  838): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  838): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  838): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  838): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  838): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=8279 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LocSvc_java(  838): onReceive
,D/LocSvc_java(  838): got connectivity action
D/LocSvc_java(  838): broadcast - no network connections
D/LocSvc_java(  838): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  838): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  838): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  838): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  838): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  838): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  838): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  838): updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[SystemUI]QuickSettingsHandler( 1367): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/NetworkChangeNotifierAutoDetect( 1935): Network connectivity changed, type is: 6
,V/AlarmManager(  838): ELAPSED_WAKEUP set : Alarm{bca9a13 type 2 when 301232 com.google.android.gms} when 301232
,I/MusicStore( 8279): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8279): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8279): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 8279): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/art     (  838): Explicit concurrent mark sweep GC freed 78313(3MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.166ms total 156.605ms
,W/ResourcesManager( 8279): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 8279): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 8279): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 8279): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 8279): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@22e6c25a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 8279): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 8279): GMSCore installation verified
,I/ConfigStore( 8279): Config Database version: 1
,I/MediaRouter( 8279): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }

```
