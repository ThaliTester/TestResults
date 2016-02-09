#### Test 58751238ee11130_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/GoogleHttpClient( 5502): GMS http client unavailable, use old client
I/GoogleHttpClient( 5502): GMS http client unavailable, use old client
--------- beginning of system
I/ActivityManager(  962): Killing 5258:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 162 ms] updated apps [took 162 ms] 
W/libprocessgroup(  962): failed to open /acct/uid_10014/pid_5258/cgroup.procs: No such file or directory
I/ActivityManager(  962): Killing 5280:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10021/pid_5280/cgroup.procs: No such file or directory
D/Finsky  ( 5520): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/AndroidRuntime( 5559): 
D/AndroidRuntime( 5559): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5559): CheckJNI is OFF
D/Finsky  ( 5520): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 5520): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5520): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5520): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@34d58259 on behalf of 5520
I/NotificationManager( 5520): com.android.vending: cancel(1003285959) by com.android.vending
D/Finsky  ( 5520): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5520): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 5520): Skipping gmscore version check
D/Finsky  ( 5520): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  962): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5605 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/Finsky  ( 5520): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5520): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  962): Killing 5307:com.google.android.partnersetup/u0a9 (adj 15): empty #11
D/AndroidRuntime( 5559): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  962): failed to open /acct/uid_10009/pid_5307/cgroup.procs: No such file or directory
I/ActivityManager(  962): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/ResourcesManager( 5605): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5605): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/ActivityManager(  962): setTaskToReturnTo : TaskRecord{35b7a4a1 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  962): setTaskToReturnTo : TaskRecord{35b7a4a1 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  962): AppWindowTokenEx init.. 
I/MultiDex( 5605): VM with version 2.1.0 has multidex support
I/MultiDex( 5605): install
I/MultiDex( 5605): VM has multidex support, MultiDex support library is disabled.
D/ContextHelper(  962): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  962): Focus left window: Window{3066b5a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5559): Shutting down VM
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  962): check instance of lgWin Window{180cf423 u0 Starting com.test.thalitest}
I/ActivityManager(  962): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5631 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1935): Closing mic
I/MicrophoneInputStream( 1935): mic_close com.google.android.apps.gsa.speech.audio.u@3052c1c0
V/AudioRecord( 1935): stop()
D/AudioRecord( 1935): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb4393000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/WindowStateAnimator(  962): Starting window displayed
I/SystemUI[Framework](  962): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  962): Call!!!getLGSystemUiVisibility. =0x0
,D/PhoneStatusBar( 1368): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
D/StatusBarManagerServiceEx(  962): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  962): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  962): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2e0affb0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  962): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1368): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1368):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1368): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1368): draw background and invalidate : color = a000000
D/BarTransitions( 1368): draw background and invalidate : color = b0b0b0b
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb4393000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioRecord( 1935): stop()
V/AudioRecord( 1935): stop()
V/AudioRecord( 1935): stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): releasing 16 from 1935 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioSystem(  962): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread 0xb4393000 exiting
V/AudioSystem( 1368): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioSystem( 2691): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioSystem( 3184): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1751): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1964): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioSystem( 1935): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  282): removeClient_l() pid 1935, calling pid 282
I/HotwordRecognitionRnr( 1935): Hotword detection finished
I/HotwordRecognitionRnr( 1935): Stopping hotword detection.
V/JNIHelp ( 5605): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ContextHelper( 5631): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
W/ActivityThread( 5605): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5605): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e801500: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5605): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5605): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5605): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 5605): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 5605): Reading stored module config
I/WebViewFactory( 5631): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/ChimeraCfgMgr( 5605): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5605): Loading module APK com.google.android.play.games
I/LibraryLoader( 5631): Time to load native libraries: 13 ms (timestamps 2122-2135)
I/LibraryLoader( 5631): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5631): Binding Chromium to main looper Looper (main, tid 1) {28fbfc28}
I/LibraryLoader( 5631): Expected native library version number "",actual native library version number ""
I/chromium( 5631): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5631): Initializing chromium process, singleProcess=true
W/art     ( 5631): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5631): ApplicationContext is null in ApplicationStatus
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/NativeLibraryUtils( 5605): Install completed successfully. count=14 extracted=0
D/charger_monitor(  484): init target 500000
W/chromium( 5631): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5631): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5631): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5631): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5631): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5631): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5631): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5631): Remote Branch: 
I/Adreno-EGL( 5631): Local Patches: 
I/Adreno-EGL( 5631): Reconstruct Branch: 
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/MainApplication( 5167): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/charger_monitor(  484): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/MainApplication( 5167): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/WifiController(  962): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
V/AudioPolicyService(  282): registerClient() client 0xb4027520, uid 10316
,D/BluetoothManagerService(  962): Message: 20
D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@16170768:true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
,I/art     ( 5605): CheckpointMarkThreadRoots callback created = 0xb042d380
,I/art     ( 5605): CheckpointMarkThreadRoots callback created = 0xb042d360
,W/art     ( 5631): Attempt to remove local handle scope entry from IRT, ignoring
,D/ChimeraCfgMgr( 5605): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5605): Module APK com.google.android.play.games already loaded
W/AwContents( 5631): onDetachedFromWindow called when already detached. Ignoring
,D/ChimeraCfgMgr( 5605): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/SystemWebViewEngine( 5631): CordovaWebView is running on device made by: LGE
,I/PeopleDatabaseHelper( 5605): cleanUpNonGplusAccounts done.
D/AsyncTaskServiceImpl( 5605): Submit a task: k
D/ChimeraCfgMgr( 5605): Loading module com.google.android.gms.gass from APK com.google.android.gms
W/art     ( 5631): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5631): Attempt to remove local handle scope entry from IRT, ignoring
D/ChimeraCfgMgr( 5605): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/Icing   ( 5605): Storage manager: low false usage 1.76MB avail 2.38GB capacity 4.06GB
D/k       ( 5605): Processing package: com.test.thalitest
,D/GassUtils( 5605): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5605): Found info for package com.test.thalitest in db.
,I/ActivityManager(  962): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5703 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Activity( 5631): Activity.onPostResume() called 
,D/OpenGLRenderer( 5631): Render dirty regions requested: true
I/OpenGLRenderer( 5631): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5631): Enabling debug mode 0
W/BaseAppContext( 5605): Using Auth Proxy for data requests.
,I/art     ( 5605): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5605): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/Atlas   ( 5631): Validating map...
D/SplitWindow(  962): check instance of lgWin Window{1dddef29 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/chromium( 5631): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
E/BaseAppContext( 5605): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/InputDispatcher(  962): Focus entered window: Window{1dddef29 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/BaseAppContext( 5605): Using Auth Proxy for data requests.
W/BaseAppContext( 5605): Using Auth Proxy for data requests.
,W/InputMethodManagerService(  962): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  962): Displayed com.test.thalitest/.MainActivity: +1s460ms
I/Timeline(  962): Timeline: Activity_windows_visible id: ActivityRecord{8e056c6 u0 com.test.thalitest/.MainActivity t222} time:82969
W/BaseAppContext( 5605): Using Auth Proxy for data requests.
,W/BaseAppContext( 5605): Using Auth Proxy for data requests.
W/BaseAppContext( 5605): Using Auth Proxy for data requests.
I/Timeline( 5631): Timeline: Activity_idle id: android.os.BinderProxy@240a1117 time:83017
,W/BindingManager( 5631): Cannot call determinedVisibility() - never saw a connection for the pid: 5631
,W/BaseAppContext( 5605): Using Auth Proxy for data requests.
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/JsMessageQueue( 5631): Set native->JS mode to OnlineEventsBridgeMode
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/Gmail   ( 5703): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5703): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5703): Error finding the version of the Email provider.....
E/Gmail   ( 5703): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5703): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5703): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5703): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5703): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5703): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5703): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5703): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5703): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5703): getAccountsCursor
I/ActivityManager(  962): Killing 5327:com.lge.appbox.client/u0a11 (adj 15): empty #11
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5605): updateResources: need to parse f{com.google.android.gms}
,W/ActivityManager(  962): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/libprocessgroup(  962): failed to open /acct/uid_10011/pid_5327/cgroup.procs: No such file or directory
W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5703): Observing account changes for notifications
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@3675ce1e on behalf of 5605
I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5769 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     ( 5605): Background sticky concurrent mark sweep GC freed 16922(1591KB) AllocSpace objects, 16(256KB) LOS objects, 11% free, 12MB/14MB, paused 12.771ms total 170.243ms
W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
D/jxcore_app_log( 5631): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426138112
,W/InstanceID/Rpc( 5605): Found 10006
,V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@1e2a16ff on behalf of 5605
,V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@3327accc on behalf of 5605
I/art     ( 5502): Explicit concurrent mark sweep GC freed 7922(399KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.011ms total 130.546ms
,I/chromium( 5631): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/PhoneMonitor( 5769): Register our PhoneStateListener
,I/ActivityManager(  962): Process com.android.contacts (pid 5366) has died
I/art     ( 5631): CheckpointMarkThreadRoots callback created = 0x9ca63600
,D/ChimeraCfgMgr( 5605): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5605): Module APK com.google.android.play.games already loaded
,I/art     ( 5605): Background sticky concurrent mark sweep GC freed 12236(879KB) AllocSpace objects, 7(112KB) LOS objects, 9% free, 13MB/14MB, paused 11.777ms total 53.453ms
I/Gmail   ( 5703): notifyAccountChanged
I/art     ( 5631): CheckpointMarkThreadRoots callback created = 0x9ca635d0
I/Gmail   ( 5703): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5703): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5703): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/art     ( 5605): No such thread id for suspend: 35
D/PhoneMonitor( 5769): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 5769): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5769): [parse] Load xml
V/TelephonyAutoProfiling( 5769): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5769): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/Gmail   ( 5703): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PhoneMonitor( 5769): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/Gmail   ( 5703): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Icing   ( 5605): Internal init done: storage state 0
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 5605): Checkin interval check for package: unspecified last checkin: 1455027659817 min interval config: 0 actual interval: 6716
I/CheckinService( 5605): Disabling old GoogleServicesFramework version
,I/NotificationManager( 5605): com.google.android.gms: cancel(10436) by com.google.android.gms
I/Icing   ( 5605): Post-init done
,I/art     (  962): Explicit concurrent mark sweep GC freed 28207(1319KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.367ms total 229.172ms
,I/ActivityManager(  962): Process com.lge.bnr (pid 5167) has died
,I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5802 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/Gmail   ( 5703): getAccountsCursor
,I/CheckinService( 5605): Checking schedule, now: 1455027666852 next: 1455027689780
I/CheckinService( 5605): active receiver: disabled
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5802): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/InitAlarmsService( 3859): Clearing and rescheduling alarms.
,I/ActivityManager(  962): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5824 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.262ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 35.139ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.913ms
W/ResourcesManager( 5824): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Babel_SMS( 5802): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5802): MmsConfig.loadMmsSettings
I/Babel_SMS( 5802): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5802): MmsConfig.loadFromDatabase
,W/art     ( 5802): Suspending all threads took: 7.187ms
,D/CalendarProvider2( 5824): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@22d9ca2f
,E/Babel_SMS( 5802): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5802): MmsConfig.loadFromResources
E/Babel_SMS( 5802): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5802): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 5802): CheckpointMarkThreadRoots callback created = 0xaaf21f90
,D/CalendarProvider2( 5824): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5824): Created com.android.providers.calendar.CalendarAlarmManager@28fbfc28(com.android.providers.calendar.CalendarProvider2@22d9ca2f)
D/CalendarProvider2( 5824): Scheduling check of next Alarm
,D/CalendarProvider2( 5824): SCHEDULE_ALARM_REMOVE
D/SensorManager( 5802): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5802): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5802): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5802): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5802): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5802): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5802): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5802): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5802): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5802): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5802): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5802): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5802): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5802): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5802): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5802): found sensor: Motion Accel, handle=46
,W/Settings( 5802): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 5802): CheckpointMarkThreadRoots callback created = 0xaaf21f80
I/Babel_Crash( 5802): startup - clean
I/Babel   ( 5802): deleted: false for 0
,W/AudioCapabilities( 5802): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5802): Unsupported mime audio/adpcm
W/AudioCapabilities( 5802): Unsupported mime audio/g726
W/AudioCapabilities( 5802): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5802): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5802): Unsupported mime video/mjpg
W/VideoCapabilities( 5802): Unsupported mime video/theora
,W/AudioCapabilities( 5802): Unsupported mime audio/evrc
,W/AudioCapabilities( 5802): Unsupported mime audio/qcelp
W/VideoCapabilities( 5802): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5802): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5802): Unsupported mime audio/qcelp
W/AudioCapabilities( 5802): Unsupported mime audio/evrc
,W/VideoCapabilities( 5802): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5802): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5802): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5802): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5802): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5802): Unrecognized profile 2130706433 for video/avc
,W/art     ( 5631): Suspending all threads took: 20.844ms
I/art     ( 5631): Background sticky concurrent mark sweep GC freed 1388(91KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 22.069ms total 39.754ms
,I/vclib   ( 5802): onServiceConnected
W/Babel   ( 5802): Attempted to change video mute state without an active call.
W/jxcore-log( 5631): Initializing JXcore engine
W/jxcore-log( 5631): JXcore engine is ready
,I/NotificationManager( 5802): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5802): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5802): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 5605): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,W/Thread-661( 5787): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7380]" dev="sockfs" ino=7380 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-661( 5787): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-661( 5787): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6693]" dev="sockfs" ino=6693 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-661( 5787): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-661( 5787): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-661( 5787): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[27693]" dev="sockfs" ino=27693 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5631): Starting JXcore engine
I/ActivityManager(  962): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5856 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5146): getMode name:com.lge.qremote
,V/JNIHelp ( 5802): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AudioManager( 5146): getMode name:com.lge.qremote
,I/AudioManager( 5146): getMode name:com.lge.qremote
,I/AudioManager( 5146): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5856): Quickset Services start...
I/UEI.SmartControl( 5856): Manufacture = LGE
D/UEI.SmartControl( 5856): File observer start...
E/UEI.SmartControl( 5856): IR Port is disabled: false
D/UEI.SmartControl( 5856): Starting file observer...
D/UEI.SmartControl( 5856): Extracting JNI libs...
I/AudioManager( 5146): getMode name:com.lge.qremote
D/UEI.SmartControl( 5856): --- this system supports 32-bit or 64-bit only
D/WearableService( 1733): callingUid 10006, callindPid: 1733
,D/Icing   ( 5605): Loaded CLD2 Version V2.0 - 20141016
W/jxcore-log( 5631): Platform android
W/jxcore-log( 5631): 
,W/jxcore-log( 5631): Process ARCH arm
W/jxcore-log( 5631): 
W/System  ( 5802): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5802): Installed default security provider GmsCore_OpenSSL
E/MDM     ( 1733): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5605): Restart initialization of location
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AudioManager( 5146): getMode name:com.lge.qremote
,I/Icing   ( 5605): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/NotificationManager( 5802): com.google.android.talk: cancel(8) by com.google.android.talk
,W/IcingInternalCorpora( 5605): getNumBytesRead when not calculated.
,I/art     ( 5605): Background sticky concurrent mark sweep GC freed 3173(248KB) AllocSpace objects, 4(64KB) LOS objects, 2% free, 14MB/14MB, paused 9.693ms total 46.706ms
I/art     ( 5605): WaitForGcToComplete blocked for 15.224ms for cause HeapTrim
I/ActivityManager(  962): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5886 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/CalendarProvider2( 5824): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5824): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  962): Killing 3859:com.android.calendar/u0a13 (adj 15): empty #11
,D/UEI.SmartControl( 5856): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5856): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5856): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5856): --- Selecting new region: 2
I/UEI.SmartControl( 5856): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5856): Platform has CIR...
D/UEI.SmartControl( 5856): NO CIR support, need to check package...
I/UEI.SmartControl( 5856): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5856): QS Service created
W/libprocessgroup(  962): failed to open /acct/uid_10013/pid_3859/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 5856): QS start get config
,I/AppUp4:AppBoxCP( 5886): onCreate
W/AppUp4:DB( 5886):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5886):  setFingerPrint start
,I/AppUp4:DB( 5886):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5886):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5886):  SDK version = 0
I/AppUp4:DB( 5886):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5886): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5886): onReceive
I/AppUp4:CustModeStarterReceiver( 5886): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5886): Context : android.app.ReceiverRestrictedContext@346d9f1a
D/AppUp4:CustFacade( 5886): isCustomizationCompleted : false
D/UEI.SmartControl( 5856): Loading JNI Libs...
,D/AppUp4:CustFacade( 5886): isSimDevice : true
D/UEI.SmartControl( 5856):  configuring local db...
D/AppUp4:CustModeStarterReceiver( 5886): begin check event
I/AppUp4:CustModeStarterReceiver( 5886): Event For Nothing, skip.
I/ActivityManager(  962): Killing 5345:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10023/pid_5345/cgroup.procs: No such file or directory
,V/AlarmManager(  962): RTC_WAKEUP set : Alarm{37be5be7 type 0 when 1455027668855 com.google.android.googlequicksearchbox} when 1455027668855
I/jxcore-log( 5631): JXcore Cordova bridge is ready!
I/jxcore-log( 5631): 
W/jxcore-log( 5631): JXcore engine is started
,I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5910 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/UEI.SmartControl( 5856):  ---- Has DB8: true
,D/UEI.SmartControl( 5856): QS start statue = true Error code = 0
D/UEI.SmartControl( 5856): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5856): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5856): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5856): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5856): IrrcClient ++ 
D/irrcClient( 5856): getIrrcService ++ 
,D/irrcClient( 5856): getIrrcService -- 
D/irrcClient( 5856): IrrcClient -- 
W/irrc_jni( 5856): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5856): Services init done
I/UEI.SmartControl( 5856): Device manager: loading config....
D/UEI.SmartControl( 5856): QS Service init finished
D/UEI.SmartControl( 5856): QS Service version name: 0.1.73
D/UEI.SmartControl( 5856): QS Service version code: 1073
,D/UEI.SmartControl( 5856): Service requested: Control
D/UEI.SmartControl( 5856): Config is loaded...
W/ResourcesManager( 5910): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5910): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5910): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5856): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5856):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5856): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5856): Internal service binding...
D/UEI.SmartControl( 5856): -----IControl: 11
D/UEI.SmartControl( 5856): Caller: com.lge.qremote
D/UEI.SmartControl( 5856): ------------ IControl registerCallback...
I/UEI.SmartControl( 5856): Registering callback...
D/UEI.SmartControl( 5856): -----IControl: 19
D/UEI.SmartControl( 5856): Caller: com.lge.qremote
I/UEI.SmartControl( 5856): Registering Services Ready callback...
I/UEI.SmartControl( 5856): Notify client services are ready...
,D/UEI.SmartControl( 5856): -----IControl: 8
D/UEI.SmartControl( 5856): Caller: com.lge.qremote
I/ActivityManager(  962): Killing 5408:com.lge.eula/1000 (adj 15): empty #11
,I/jxcore-log( 5631): Toggling radios to true
I/jxcore-log( 5631): 
,D/BluetoothAdapter( 5631): enable(): BT is already enabled..!
I/ActivityManager(  962): Killing 5390:com.lge.lockscreensettings/u0a69 (adj 15): empty #12
,W/libprocessgroup(  962): failed to open /acct/uid_1000/pid_5408/cgroup.procs: No such file or directory
,W/libprocessgroup(  962): failed to open /acct/uid_10069/pid_5390/cgroup.procs: No such file or directory
D/WifiServiceImplEx(  962): setWifiEnabled: true pid=5631, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  962): setWifiEnabled: true pid=5631, uid=10316
I/AppConfig( 5910): Total System Memory = 906309632
D/WifiServiceImplEx(  962): disconnect pid=5631, uid=10316, packageName=com.test.thalitest
I/GalleryUtils( 5910): Application Heap = 96 MB
D/WifiServiceImplEx(  962): reconnect pid=5631, uid=10316, packageName=com.test.thalitest
,I/AppConfig( 5910): App Tier : NOT_DEF
I/jxcore-log( 5631): Radios toggled
I/jxcore-log( 5631): 
I/jxcore-log( 5631): My device name is: LGE-LG-D722
I/jxcore-log( 5631): 
D/SystemHelper( 5910): region [EU], country [EU], operator [OPEN], sub-operator []
I/wpa_supplicant( 2809): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2809): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1803): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiStateMachine(  962): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  962): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  278): Clearing all IP addresses on wlan0
D/DhcpStateMachine(  962): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1733): Read error: ssl=0xaaf4c200: I/O error during system call, Connection timed out
V/NativeCrypto( 1733): SSL shutdown failed: ssl=0xaaf4c200: I/O error during system call, Broken pipe
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5934 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  962): Killing 5429:com.google.android.apps.docs/u0a58 (adj 15): empty #11
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  962): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  962): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  962): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): ValidatedState{ when=-5ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): DefaultState{ when=-7ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): Forcing reevaluation
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
,W/libprocessgroup(  962): failed to open /acct/uid_10058/pid_5429/cgroup.procs: No such file or directory
,D/ConnectivityService(  962): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  962): disableDataServiceNotify
D/DSQN    (  962): stop dsqn bin
D/WifiHS20(  962): hidePasspointNotification off =false
E/WifiStateMachine(  962): Start Disconnecting Watchdog 1
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,D/WifiHS20(  962): hidePasspointNotification off =false
D/LGWifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): wlan0: CTRL-EVENT-SCAN-STARTED 
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/CommandListener(  278): Clearing all IP addresses on wlan0
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:09.418 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:09.419 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  962): hidePasspointNotification off =false
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:09.423 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/ResourcesManager( 5934): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5934): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5934): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5934): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5934): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/WifiNetworkAgent(  962): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/WifiHS20(  962): hidePasspointNotification off =false
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:09.448 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  962): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityManager.CallbackHandler( 1368): CM callback handler got msg 524292
D/Nat464Xlat(  962): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): Disconnected - quitting
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:09.459 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
D/CSLegacyTypeTracker(  962): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  962): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateDISCONNECTED
D/ConnectivityService(  962): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  962): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  962): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  962): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  962): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  962):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1751): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  962): MasterInitialState.processMessage what=3
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/QCNEJ   ( 1839): |CORE| No family connected
D/Tethering(  962): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
V/NetworkPolicy(  962): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  962): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkManagementService(  962): Removing idletimer
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateSCANNING
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
W/Settings(  962): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  962): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyIcons( 1368): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1368): updateLGTelephonySignalStrength : !hasService()
D/DhcpStateMachine(  962): StoppedState
D/DhcpStateMachine(  962): StoppedState{ when=-90ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1368): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1368): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/SystemConfig( 5934): BUILD Country: EU
I/SystemConfig( 5934): BUILD Operator: OPEN
,I/ActivityManager(  962): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5957 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 5460:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10086/pid_5460/cgroup.procs: No such file or directory
I/SystemConfig( 5934): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5934): existFile = false
I/SystemConfig( 5934): canReadFile = false
I/SystemConfig( 5934): systemFeature RCS result false
D/SystemConfig( 5934): refreshRcsSupport() :false
,I/LockScreenSettings( 5957): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/[SystemUI]QPairHandler( 1368): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1368): onReceive = android.intent.action.PACKAGE_CHANGED
D/administrator(  962): Handling package changes for user 0
,W/[SystemUI]QSlideLoader( 1368): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1368): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/LockScreenSettings( 5957): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5957): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5957): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5957): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5957): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5981 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 5520:com.android.vending/u0a36 (adj 15): empty #11
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationService(  962): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  962): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  962): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/libprocessgroup(  962): failed to open /acct/uid_10036/pid_5520/cgroup.procs: No such file or directory
I/BackupManagerService(  962): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager( 5981): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  962): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 31113(2038KB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 13MB/22MB, paused 1.475ms total 118.615ms
V/BackupManagerService(  962): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  962): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3c49304a
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,W/ResourceType(  962): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  962): Process com.google.android.gm (pid 5703) has died
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  962): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6007 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/lowmemorykiller(  242): Error writing /proc/5502/oom_score_adj; errno=22
,E/lowmemorykiller(  242): Error writing /proc/5502/oom_score_adj; errno=22
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2809): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/ActivityThread( 5981): Removing dead content provider:android.content.ContentProviderProxy@2cb75394
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 90 ms] updated apps [took 90 ms] 
I/ActivityManager(  962): Process com.google.process.gapps (pid 5502) has died
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2809): wlan0: Associated with c0:ff:d4:d3:aa:48
I/ActivityManager(  962): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6026 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/wpa_supplicant( 2809): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2809): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
D/LocSvc_java(  962): onReceive
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:10.655 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:10.659 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:10.668 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/WifiServiceExtension(  962): setVHTCapabilityType  : false
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:10.679 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/ActivityManager(  962): Process com.google.android.setupwizard (pid 5769) has died
,I/WifiServerServiceExt(  962): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  962): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  962): setSecurityType  : 2
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:10.833 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:10.841 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/ConnectivityService(  962): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  962): Got NetworkAgent Messenger
D/ConnectivityService(  962): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  962): NetworkAgent connected
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
E/WifiConfigStore(  962): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
E/WifiConfigStore(  962): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Setting iface cfg
E/WifiStateMachine(  962): Start Dhcp Watchdog 2
D/DhcpStateMachine(  962): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): WaitBeforeStartState
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateASSOCIATED
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  962): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/GservicesProvider( 6026): Gservices pushing to system: true; secure/global: true
E/WifiStateMachine(  962): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
,D/LGWifiP2pService(  962): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d36fcf4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@d36fcf4 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  962): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  962): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/CommandListener(  278): Setting iface cfg
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  962): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  962): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  962): setSupplicantStateCOMPLETED
I/GoogleHttpClient( 6026): GMS http client unavailable, use old client
D/ConnectivityService(  962): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  962): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  962): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  962): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  962): ignoring duplicate network state non-change
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:11.004 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/ConnectivityService(  962): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  962): Adding iface wlan0 to network 101
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:11.011 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  962): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:11.023 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
E/WifiStateMachine(  962): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/WifiHS20(  962): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = true, mWifiLevel = 2
E/ConnectivityService(  962): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  962): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  962): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:11.043 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
E/Netd    (  278): netlink response contains error (File exists)
D/ConnectivityService(  962): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  962): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  962): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  962): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/Nat464Xlat(  962): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  962): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  962): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  962):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  962):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  962):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  962): currentScore = 0, newScore = 20
D/ConnectivityService(  962):    accepting network in place of null
D/ConnectivityService(  962): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  962): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  962):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1751): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): [LWD] Start DNSResolver start to wait
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  962): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  962): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  962): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  962): [e] list.add(nai) empty : false size: 1
D/ConnectivityService( , 962): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/Tethering(  962): MasterInitialState.processMessage what=3
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
I/GoogleHttpClient( 6026): GMS http client unavailable, use old client
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): [LWD] wait 500ms before dns check
D/ConnectivityService(  962): validation of new default Network = false
D/ConnectivityService(  962): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  962): enableDataServiceNotify 
D/DSQN    (  962): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = true, mWifiLevel = 2
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
V/NetworkPolicy(  962): [LG_RESTRICTED] checkMobilePolicy_type()
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/ConnectivityService(  962): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/ConnectivityManager.CallbackHandler( 1368): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/DSQN    ( 6051): DSQN samuel.seo ver 141203
E/DSQN    ( 6051): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6051): created command queue thread
,I/DSQN    ( 6051): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6051): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/TelephonyIcons( 1368): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1368): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,D/DhcpStateMachine(  962): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  962): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  962): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6054): version 5.5.6 starting
E/dhcpcd  ( 6054): get_duid: Read-only file system
,I/dhcpcd  ( 6054): wlan0: rebinding lease of 192.168.1.134
,I/art     (  962): Explicit concurrent mark sweep GC freed 61787(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.273ms total 226.756ms
,D/LocationProviderProxy(  962): applying state to connected service
,D/Finsky  ( 6007): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): [LWD] DNSResolver start dns
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/Finsky  ( 6007): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6007): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  962): propertyValue:false
W/Settings( 6007): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): Checking http://clients3.google.com/generate_204 on "NG700"
I/NotificationManager( 6007): com.android.vending: cancel(-1050172287) by com.android.vending
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 6051): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6051): restart monitoring
,I/DSQN    ( 6051): dsqn report finish
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  962): DSQM DsqnNotification wlan0  1
D/DSQN    (  962): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 14:21:11 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455027671675], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455027671656]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  962): Validated
D/ConnectivityService(  962): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  962):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  962): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  962): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  962): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  962):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiDataContinuityService(  962): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityManager.CallbackHandler( 1368): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1751): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  962): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1368): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1368): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/Finsky  ( 6007): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6007): [1] Libraries$2.run: Finished loading 1 libraries.
,V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/Ads     ( 6007): Skipping gmscore version check
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@1052eb15 on behalf of 6007
D/PackageBroadcastService( 5605): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 6007): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/PackageBroadcastService( 5605): Null package name or gms related package.  Ignoreing.
I/AudioManager( 5146): getMode name:com.lge.qremote
I/Icing   ( 5605): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 6007): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/AudioManager( 5146): getMode name:com.lge.qremote
I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6105 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  962): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,D/PhoneMonitor( 6105): Register our PhoneStateListener
,I/ActivityManager(  962): Process com.android.gallery3d (pid 5910) has died
,V/SetupWizard( 6105): Connected to Gservices successfully
,D/PhoneMonitor( 6105): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6105): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6105): [parse] Load xml
V/TelephonyAutoProfiling( 6105): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6105): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6105): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
E/MDM     ( 1733): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5605): Restart initialization of location
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/dhcpcd  ( 6054): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  962): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6136 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/dhcpcd  ( 6054): wlan0: leased 192.168.1.134 for 86400 seconds
V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{d440ef3 type 2 when 90361 com.android.providers.calendar} when 90361
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
,D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  962): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  962): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  962): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  962): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LocSvc_java(  962): onReceive
D/LocSvc_java(  962): got connectivity action
,D/LocSvc_java(  962): broadcast - no network connections
D/LocSvc_java(  962): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  962): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  962): onReceive
D/LocSvc_java(  962): got connectivity action
D/LocSvc_java(  962): broadcast - no network connections
D/LocSvc_java(  962): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  962): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  962): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  962): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  962): identical MTU - not setting
D/Nat464Xlat(  962): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:12.659 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  962): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  962):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  962): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  962): enableDataServiceNotify 
D/ConnectivityManager.CallbackHandler( 1368): CM callback handler got msg 524295
D/DSQN    (  962): start dsqn bin
D/DSQN    (  962): dsqn is running restart
,I/DSQN    ( 6175): DSQN samuel.seo ver 141203
E/DSQN    ( 6175): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6175): created command queue thread
I/DSQN    ( 6175): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6175): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  962): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  962): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  962): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  962): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  962): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  962): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  962): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  962): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  962): RunningState
I/Gmail   ( 6136): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6136): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6136): Error finding the version of the Email provider.....
E/Gmail   ( 6136): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6136): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6136): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6136): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6136): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6136): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6136): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6136): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6136): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6136): getAccountsCursor
,I/ActivityManager(  962): Killing 5824:com.android.providers.calendar/u0a14 (adj 15): empty #11
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  962): failed to open /acct/uid_10014/pid_5824/cgroup.procs: No such file or directory
,W/ActivityManager(  962): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6136): Observing account changes for notifications
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5605): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  962): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6200 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.736ms
I/Icing   ( 5605): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 309us total 21.172ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 358us total 21.717ms
,I/Gmail   ( 6136): notifyAccountChanged
I/Gmail   ( 6136): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6136): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6200): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Gmail   ( 6136): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6136): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6136): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/CalendarApplication( 6200): CalendarApplication.onCreate()
I/Gmail   ( 6136): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PreferenceKeysParser( 6200): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6200): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@328e49c5, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@346d9f1a, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2142da4b, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@28fbfc28, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@290ebd41, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1a3692e6, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@de2d027, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2a28b2d4, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3dc8ec7d, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2c48f772, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2aa247c3, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1cc82840, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1efcd379, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2ab18be, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@25579d1f, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3d27886c, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@4ee2e35, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1d7c02ca, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@8e2ec3b, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1d3abf58, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2e6078b1, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2dbf8196, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@240a1117, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@38487904, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@28d2eeed, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1eea2122, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@214a7b3, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@15562170, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@207c8ce9, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2d2d2d6e, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@11280c0f, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2453e49c, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@34080ea5, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1482b27a, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@12635a2b, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@208ae88, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@80ff021, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@24797c46, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2fbb6e07, lg_preference_defaultCalendar=com.android.calendar.adaptation.Pref,erenceKey$KeyData@ebe2b34, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@165a6d5d, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@4c116d
,D/GeneralPreferenceUtils( 6200): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6200): [init]
I/Config  ( 6200): LGCalendar ver.4.40.17
I/Config  ( 6200): start check model
I/Config  ( 6200): start check native_ca
,I/Config  ( 6200): Config Operator=OPEN, Country=EU
D/Config  ( 6200): [setDefaultValuesToPref]
D/Config  ( 6200): [parseProfiles]
D/ProfilesParser( 6200): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6200): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6200): [updateProfiletoCountryInfo]
D/GeneralPreference( 6200): [checkAndMigrateOldPreference]
D/AlertReceiver( 6200): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/ActivityManager(  962): Killing 5802:com.google.android.talk/u0a61 (adj 15): empty #11
I/InitNotificationRingtoneService( 6200): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6200): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,W/libprocessgroup(  962): failed to open /acct/uid_10061/pid_5802/cgroup.procs: No such file or directory
,I/AlertUtils( 6200): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
W/HolidayIntentService( 6200): onHandleIntent
,D/HolidayDataLoader( 6200): readJsonAsset : holiday.json
E/AgendaWidgetManager( 6200): [updateWidgets] 
D/MonthWidgetProvider( 6200): [onReceive]
D/CalendarWidgetProvider( 6200): [onReceive]
D/CalendarWidgetProvider( 6200): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/AlertService( 6200): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/CalendarTypeController( 6200): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6200): [onReceive]
D/CalendarWidgetProvider( 6200): [onReceive]
D/CalendarWidgetProvider( 6200): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6200): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5146): getMode name:com.lge.qremote
,I/ActivityManager(  962): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6227 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/HolidayIntentService( 6200): onHandleIntent:holiday data empty
,I/art     (  962): Explicit concurrent mark sweep GC freed 40081(1956KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.125ms total 183.591ms
,I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6200): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,I/AlertUtils( 6200): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6200): set default noti to content://media/internal/audio/media/38
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:21:13.892 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/InitNotificationRingtoneService( 6200): End InitializeAlertRingtoneService.onHandleIntent
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/WifiInternetCheck(  962): Single check msg out of sync, ignoring.
,I/NotificationManager( 1935): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/UEI.SmartControl( 5856): Internal timer expired: 1
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/ConnectivityService(  962): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  962): Process com.google.android.apps.plus (pid 5981) has died
,D/LocSvc_java(  962): onReceive
D/LocSvc_java(  962): got connectivity action
D/LocSvc_java(  962): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  962): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  962): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  962): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/ResourcesManager( 6227): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6227): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6227): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6227): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6227): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/GpsLocationProvider(  962): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/IndexDatabaseHelper( 6227): Using schema version: 115
I/IndexDatabaseHelper( 6227): Index is fine
,I/ActivityManager(  962): Process com.android.contacts (pid 5934) has died
,V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6252 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6252): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6252): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6252): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6277 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6277): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/AlarmManager(  962): RTC_WAKEUP set : Alarm{81c15d4 type 0 when 1455027674957 com.android.vending} when 1455027674957
,D/Finsky  ( 6007): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/NotificationManager(  962): android: cancelAsUser(2) by android
I/Babel_SMS( 6277): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6277): MmsConfig.loadMmsSettings
I/Babel_SMS( 6277): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6277): MmsConfig.loadFromDatabase
D/libc-netbsd( 6007): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6007): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6007): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6007): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
E/Babel_SMS( 6277): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6277): MmsConfig.loadFromResources
E/Babel_SMS( 6277): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6277): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6277): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6277): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6277): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6277): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6277): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6277): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6277): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6277): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6277): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6277): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6277): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6277): found sensor: LGE Orientation Sensor, handle=49
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
D/SensorManager( 6277): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6277): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6277): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6277): found sensor: Motion Accel, handle=46
I/System.out( 6007): propertyValue:false
D/libc-netbsd( 6007): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6007): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6175): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6175): restart monitoring
,I/DSQN    ( 6175): dsqn report finish
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/DSQN    (  962): DSQM DsqnNotification wlan0  1
D/DSQN    (  962): start to monitor internet connection
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out(  962): propertyValue:false
W/Settings( 6277): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  962): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  962): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/Babel_Crash( 6277): startup - clean
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  962): propertyValue:false
I/art     ( 6277): CheckpointMarkThreadRoots callback created = 0xb042d910
,V/WifiInternetCheck(  962): isHttpConnectionAvailable - We got a valid response : 204
I/Babel   ( 6277): deleted: false for 0
,I/art     ( 6277): CheckpointMarkThreadRoots callback created = 0xb042d8f0
D/libc-netbsd( 6007): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6007): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
I/PCSuite ( 6252): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6252): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6252): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6277): Unsupported mime audio/x-lg-flac
D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
W/AudioCapabilities( 6277): Unsupported mime audio/adpcm
W/AudioCapabilities( 6277): Unsupported mime audio/g726
I/PCSuite ( 6252): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6252): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6252): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6277): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6277): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6277): Unsupported mime video/mjpg
,W/VideoCapabilities( 6277): Unsupported mime video/theora
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
I/PCSuite ( 6252): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6252): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6252): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
,W/AudioCapabilities( 6277): Unsupported mime audio/evrc
,W/AudioCapabilities( 6277): Unsupported mime audio/qcelp
W/VideoCapabilities( 6277): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6277): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6277): Unsupported mime audio/qcelp
W/AudioCapabilities( 6277): Unsupported mime audio/evrc
W/VideoCapabilities( 6277): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6277): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6277): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6277): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6277): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6277): Unrecognized profile 2130706433 for video/avc
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  962): android: cancelAsUser(2) by android
I/vclib   ( 6277): onServiceConnected
,W/Babel   ( 6277): Attempted to change video mute state without an active call.
I/AppUp4:CustModeStarterReceiver( 5886): onReceive
I/AppUp4:CustModeStarterReceiver( 5886): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5886): Context : android.app.ReceiverRestrictedContext@346d9f1a
D/AppUp4:CustFacade( 5886): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5886): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5886): begin check event
I/AppUp4:CustModeStarterReceiver( 5886): Event For Nothing, skip.
I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6317 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/qtaguid ( 6007): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6007): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6007): untagSocket(41) failed with errno -22
,D/Finsky  ( 6007): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/NotificationManager( 6277): com.google.android.talk: cancel(10436) by com.google.android.talk
I/NotificationManager( 6277): com.google.android.talk: cancel(8) by com.google.android.talk
,W/art     ( 6007): Suspending all threads took: 27.537ms
W/ResourcesManager( 6277): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6277): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6317): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6317): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6317): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/art     ( 6277): Suspending all threads took: 5.782ms
,V/JNIHelp ( 6277): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  962): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6338 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AppConfig( 6317): Total System Memory = 906309632
I/GalleryUtils( 6317): Application Heap = 96 MB
,I/NotificationManager(  962): android: cancelAsUser(2) by android
I/AppConfig( 6317): App Tier : NOT_DEF
W/System  ( 6277): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6277): Installed default security provider GmsCore_OpenSSL
,D/SystemHelper( 6317): region [EU], country [EU], operator [OPEN], sub-operator []
,W/ResourcesManager( 6338): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6338): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6338): VM with version 2.1.0 has multidex support
,I/MultiDex( 6338): install
I/MultiDex( 6338): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6359 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,V/JNIHelp ( 6338): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/qtaguid ( 6007): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6007): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6007): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6359): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6359): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6359): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6359): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6359): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ActivityThread( 6338): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6338): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e2cae2a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6338): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  962): Process com.google.android.gm (pid 6136) has died
,I/NotificationManager( 6338): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6338): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6338): Reading stored module config
,I/SystemConfig( 6359): BUILD Country: EU
I/SystemConfig( 6359): BUILD Operator: OPEN
,D/ChimeraCfgMgr( 6338): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/SystemConfig( 6359): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6359): existFile = false
I/SystemConfig( 6359): canReadFile = false
I/SystemConfig( 6359): systemFeature RCS result false
D/SystemConfig( 6359): refreshRcsSupport() :false
D/LockScreenSettings( 5957): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5957): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5957): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5957): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5957): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6383 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6007): CheckpointMarkThreadRoots callback created = 0xb055b7d0
,D/CAR.SERVICE( 6338): Connecting to CarCallService...
,I/art     ( 6007): CheckpointMarkThreadRoots callback created = 0xb055b7a0
,I/art     ( 6338): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6338): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6338): Install completed successfully. count=14 extracted=0
W/ResourcesManager( 6383): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CAR.SERVICE( 6338): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6338): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6338): Creating a new PhoneAdapter instance
W/ActivityManager(  962): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6338): setListener: com.google.android.gms.car.dn@3e41301
W/ActivityManager(  962): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6338): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 6338): Starting CarCallService with initial phone null
D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 94769243197; DSPS: 3203913; Offset : -3014766875
,I/NotificationManager( 6338): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6338): Package validated; name: com.android.vending
,I/NotificationManager( 6007): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6007): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  962): Killing 6105:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 56 ms] updated apps [took 56 ms] 
,W/libprocessgroup(  962): failed to open /acct/uid_10038/pid_6105/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 5605): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
I/PackageBroadcastService( 5605): Null package name or gms related package.  Ignoreing.
,D/WiFiOffLoadBroadcast( 6227): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/Icing   ( 5605): updateResources: need to parse f{com.google.android.gms}
,D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
I/PCSuite ( 6252): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6252): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6227): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6227): MCCMNC not supported: null
I/PCSuite ( 6252): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6252): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/AudioManager( 5146): getMode name:com.lge.qremote
,I/AudioManager( 5146): getMode name:com.lge.qremote
I/ActivityManager(  962): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6421 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  962): android: cancelAsUser(2) by android
,W/ResourcesManager( 6421): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6421): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@22d9ca2f
,D/CalendarProvider2( 6421): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6421): Created com.android.providers.calendar.CalendarAlarmManager@28fbfc28(com.android.providers.calendar.CalendarProvider2@22d9ca2f)
D/CalendarProviderBroadcastReceiver( 6421): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6421): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6421): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6421): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 6421): [getOrCreateCalendarAlarmManager]
,I/ActivityManager(  962): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6441 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/qtaguid ( 6007): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6007): Untagging socket 41 failed errno=-22
,W/NetworkManagementSocketTagger( 6007): untagSocket(41) failed with errno -22
,I/art     (  962): Explicit concurrent mark sweep GC freed 23373(1091KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 5.192ms total 181.285ms
,D/CalendarProvider2( 6421): [IntentService] Release Lock
,D/CalendarProvider2( 6421): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  962): Killing 5886:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/ResourcesManager( 6007): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6007): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  962): failed to open /acct/uid_10011/pid_5886/cgroup.procs: No such file or directory
W/ResourcesManager( 6007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/MusicStore( 6441): Database version: 120
,D/Finsky  ( 6007): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  962): RTC_WAKEUP set : Alarm{2280ef4 type 0 when 1455027678194 com.android.vending} when 1455027678194
D/DeviceConnectionService( 1733): client connected with version: 8296000
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
D/Finsky  ( 6007): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6007): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  962): Killing 6317:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10023/pid_6317/cgroup.procs: No such file or directory
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6441): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/jxcore-log( 5631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5631): 
,I/Icing   ( 5605): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6441): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6441): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6441): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6441): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 5605): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  962): Killing 6359:com.android.contacts/u0a18 (adj 15): empty #11
,V/JNIHelp ( 6441): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 6441): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6441): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@407d0ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6441): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6441): GMSCore installation verified
D/AlertService( 6200): Beginning updateAlertNotification
,W/libprocessgroup(  962): failed to open /acct/uid_10018/pid_6359/cgroup.procs: No such file or directory
,I/ConfigStore( 6441): Config Database version: 1
D/AlertService( 6200): No fired or scheduled alerts
I/NotificationManager( 6200): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 6200): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(15) by com.android.calendar
,I/NotificationManager( 6200): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6200): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6200): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6200): No events found starting within 1 week.
,I/MediaRouter( 6441): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/ActivityManager(  962): Killing 6200:com.android.calendar/u0a13 (adj 15): empty #11
V/MusicLeanback( 6441): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6441): type=WIFI subType= reason=null isConnected=true
,W/libprocessgroup(  962): failed to open /acct/uid_10013/pid_6200/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  962): Killing 5957:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10069/pid_5957/cgroup.procs: No such file or directory
,V/AlarmManager(  962): RTC_WAKEUP set : Alarm{1c393b31 type 0 when 1455027679094 com.google.android.googlequicksearchbox} when 1455027679094
I/NetworkMonitor( 6441): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  962): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6478 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6441): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6441): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  962): Killing 6383:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/ResourcesManager( 6478): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6478): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6478): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  962): failed to open /acct/uid_10086/pid_6383/cgroup.procs: No such file or directory
,I/NotificationManager( 6441): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6478): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6478): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/jxcore-log( 5631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5631): 
,I/ActivityManager(  962): Process com.android.settings (pid 6227) has died
,I/jxcore-log( 5631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5631): 
I/jxcore-log( 5631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5631): 
,I/ActivityManager(  962): Process com.lge.qremote (pid 5146) has died
D/UEI.SmartControl( 5856): Service.onUnbind: IControl
D/UEI.SmartControl( 5856): Service.onDestroy
D/UEI.SmartControl( 5856): Shutdown IRRCPlayer... 
W/irrc_jni( 5856): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5856): ~IrrcClient ++ 
D/irrcClient( 5856): ~IrrcClient -- 
,W/irrc_jni( 5856): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5856): Blaster closed
D/UEI.SmartControl( 5856): Blaster closed
D/UEI.SmartControl( 5856): Shut down QS...
D/UEI.SmartControl( 5856): Stopped file observer...
I/UEI.SmartControl( 5856): QS lib stop result = true
,D/UEI.SmartControl( 5856): QS shutdown complete
I/jxcore-log( 5631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5631): 
,D/eas_req ( 6478): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  962): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6501 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 23.937ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 24.663ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 22.005ms
,I/HubEmail( 6478): JNI_OnLoad()
I/HubEmail( 6478): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6478): registerNatives()
I/HubEmail( 6478): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6478): registerNativeMethods()
I/HubEmail( 6478): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6478): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6478): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6501): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6501): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6501): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6501): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6501): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6501): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6501): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6501): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  962): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6530 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6501): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,E/LGDMClient( 6501): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6501): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6501): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6501): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6501): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 6530): onCreate
,W/AppUp4:DB( 6530):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6530):  setFingerPrint start
I/AppUp4:DB( 6530):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6530):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6530):  SDK version = 0
I/AppUp4:DB( 6530):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6530): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6530): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6530): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6530): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6530): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6530): onReceive
I/AppUp4:CustModeStarterReceiver( 6530): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6530): Context : android.app.ReceiverRestrictedContext@290ebd41
D/AppUp4:CustFacade( 6530): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6530): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6530): begin check event
I/AppUp4:CustModeStarterReceiver( 6530): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6530): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6530): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6530): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6530): handleAsyncCustNotification do not startCustService
I/ActivityManager(  962): Killing 5856:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10089/pid_5856/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3184): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3184): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3184): networkInfo.isConnected() = false
,I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6555 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6555): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6555): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6555): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  962): Killing 6252:com.lge.sync/1000 (adj 15): empty #11
,D/PhoneMonitor( 6555): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6555): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6555): [parse] Load xml
V/TelephonyAutoProfiling( 6555): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6555): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6555): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  962): failed to open /acct/uid_1000/pid_6252/cgroup.procs: No such file or directory
,V/DownloadManager( 3262): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/CheckinService( 5605): Checkin interval check for package: unspecified last checkin: 1455027659817 min interval config: 0 actual interval: 21289
V/DownloadManager( 3262): DownloadService onCreate
I/DownloadManager( 3262): in removeSpuriousFiles
I/NotificationManager( 3262): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@1e2cae2a on behalf of 3262
,I/DownloadManager( 3262): in trimDatabase
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@1493241b on behalf of 3262
I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6584 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3262): DownloadService onStartCommand
,I/CheckinService( 5605): Checking schedule, now: 1455027681146 next: 1455027689780
I/CheckinService( 5605): active receiver: disabled
V/DownloadManager( 3262): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@22bf82f6 on behalf of 3262
I/ActivityManager(  962): Killing 6277:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10061/pid_6277/cgroup.procs: No such file or directory
V/DownloadManager( 3262): DownloadService onDestroy
I/ActivityManager(  962): Killing 6421:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10014/pid_6421/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2677): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:21
,D/UpdateThreadPoolManager( 2677): 2 : This is isUpdating : false
D/WeatherAncestor( 2677): connectivity changed - connection : true
D/Weather_cast( 2677): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2677): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:21
D/WeatherService( 2677): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6609 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  962): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2677): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2677): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2677): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6609): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6609): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6609): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6609): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6609): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6609): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6609): MmsConfig.loadFromResources
E/Babel_SMS( 6609): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6609): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6609): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6609): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6609): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6609): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6609): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6609): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6609): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 6609): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6609): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6609): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6609): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6609): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6609): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6609): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6609): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6609): found sensor: Motion Accel, handle=46
D/CAR.SERVICE( 6338): mConnectedToCar = false, abort
,W/Settings( 6609): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6609): startup - clean
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/ActivityThread( 6338): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@12ceb3c9 that was originally bound here
E/ActivityThread( 6338): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@12ceb3c9 that was originally bound here
E/ActivityThread( 6338): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6338): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6338): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6338): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6338): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6338): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6338): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6338): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6338): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6338): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6338): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6338): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6338): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6338): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6338): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6338): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6338): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6338): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6338): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6338): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6338): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6338): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6338): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 6338): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@c9e10e8 that was originally bound here
E/ActivityThread( 6338): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@c9e10e8 that was originally bound here
E/ActivityThread( 6338): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6338): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6338): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6338): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6338): 	at android.content.ContextWrapp,er.bindService(ContextWrapper.java:538)
E/ActivityThread( 6338): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6338): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6338): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6338): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6338): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6338): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6338): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6338): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6338): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6338): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6338): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6338): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6338): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6338): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6338): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6338): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6338): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  962): Unbind failed: could not find connection for android.os.BinderProxy@30253814
,I/Babel   ( 6609): deleted: false for 0
,I/art     ( 6609): CheckpointMarkThreadRoots callback created = 0xaaf36590
I/art     ( 6609): CheckpointMarkThreadRoots callback created = 0xaaf36570
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6641 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6609): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6609): Unsupported mime audio/adpcm
W/AudioCapabilities( 6609): Unsupported mime audio/g726
W/AudioCapabilities( 6609): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6609): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6609): Unsupported mime video/mjpg
W/VideoCapabilities( 6609): Unsupported mime video/theora
,W/AudioCapabilities( 6609): Unsupported mime audio/evrc
W/AudioCapabilities( 6609): Unsupported mime audio/qcelp
W/VideoCapabilities( 6609): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6609): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6609): Unsupported mime audio/qcelp
W/AudioCapabilities( 6609): Unsupported mime audio/evrc
W/VideoCapabilities( 6609): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6609): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6609): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6609): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6609): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6609): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6609): onServiceConnected
,W/Babel   ( 6609): Attempted to change video mute state without an active call.
I/NotificationManager( 6609): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6609): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6609): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6609): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6609): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6609): propertyValue:false
I/Babel   ( 6609): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  962): Killing 6338:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10006/pid_6338/cgroup.procs: No such file or directory
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6641): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6641): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6641): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6641): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6641): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6641):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6641):   adb logcat -s GAv4
,W/GAv4    ( 6641): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6641): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6641): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6641): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/LibraryLoader( 6641): Time to load native libraries: 2 ms (timestamps 1041-1043)
I/LibraryLoader( 6641): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6641): Binding Chromium to main looper Looper (main, tid 1) {3fe4f5da}
,I/LibraryLoader( 6641): Expected native library version number "",actual native library version number ""
I/chromium( 6641): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6641): Initializing chromium process, singleProcess=true
,W/art     ( 6641): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6641): ApplicationContext is null in ApplicationStatus
W/chromium( 6641): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6641): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6641): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6641): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6641): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6641): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6641): Remote Branch: 
I/Adreno-EGL( 6641): Local Patches: 
I/Adreno-EGL( 6641): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb4027040, uid 10079
,W/AudioManagerAndroid( 6641): Requires BLUETOOTH permission
I/NSApplication( 6641): Starting up...
,I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6710 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  962): Killing 6007:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10036/pid_6007/cgroup.procs: No such file or directory
,I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6732 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  962): Killing 6441:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10081/pid_6441/cgroup.procs: No such file or directory
,W/ResourcesManager( 6732): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  962): Explicit concurrent mark sweep GC freed 18705(905KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.920ms total 140.632ms
,I/iu.SyncManager( 5605): SYNC; picasa accounts
,D/NetworkLogImpl( 5605): Loaded NetworkSpeedPredictor
I/iu.Environment( 5605): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager(  962): Killing 6478:com.lge.email/u0a21 (adj 15): empty #11
,I/iu.UploadsManager( 5605): num queued entries: 0
I/iu.UploadsManager( 5605): num updated entries: 0
I/iu.SyncManager( 5605): NEXT; no task
,W/libprocessgroup(  962): failed to open /acct/uid_10021/pid_6478/cgroup.procs: No such file or directory
,I/ActivityManager(  962): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6759 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/MusicStore( 6759): Database version: 120
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6759): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6759): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6759): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6759): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6759): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6759): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/ActivityThread( 6759): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6759): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@407d0ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6759): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6759): GMSCore installation verified
,I/ConfigStore( 6759): Config Database version: 1
,I/MediaRouter( 6759): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6759): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6759): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6759): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  962): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6788 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6759): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6759): Using platform SSLCertificateSocketFactory
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
W/ResourcesManager( 6788): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6788): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6788): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  962): Killing 6501:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_1000/pid_6501/cgroup.procs: No such file or directory
,I/NotificationManager( 6759): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6788): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6788): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6788): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  962): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6818 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6788): JNI_OnLoad()
I/HubEmail( 6788): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6788): registerNatives()
I/HubEmail( 6788): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6788): registerNativeMethods()
I/HubEmail( 6788): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6788): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6788): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  962): Killing 6530:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10011/pid_6530/cgroup.procs: No such file or directory
,D/LGDMClient( 6818): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6818): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6818): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6818): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6818): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6818): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6818): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6818): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  962): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6842 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6818): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.510ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.737ms
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/LGDMClient( 6818): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6818): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6818): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6818): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 24.752ms
,D/LGDMClient( 6818): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  962): Killing 6555:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10038/pid_6555/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6842): onCreate
W/AppUp4:DB( 6842):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6842):  setFingerPrint start
I/AppUp4:DB( 6842):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6842):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6842):  SDK version = 0
I/AppUp4:DB( 6842):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6842): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6842): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6842): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6842): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6842): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6842): onReceive
I/AppUp4:CustModeStarterReceiver( 6842): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6842): Context : android.app.ReceiverRestrictedContext@290ebd41
D/AppUp4:CustFacade( 6842): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6842): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6842): begin check event
I/AppUp4:CustModeStarterReceiver( 6842): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6842): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6842): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6842): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6842): handleAsyncCustNotification do not startCustService
I/ActivityManager(  962): Killing 6584:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10051/pid_6584/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3184): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3184): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3184): networkInfo.isConnected() = false
,I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6861 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6861): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6861): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6861): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  962): Killing 6609:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 6861): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6861): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6861): [parse] Load xml
V/TelephonyAutoProfiling( 6861): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6861): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6861): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 5605): Done disabling old GoogleServicesFramework version
,W/libprocessgroup(  962): failed to open /acct/uid_10061/pid_6609/cgroup.procs: No such file or directory
,V/DownloadManager( 3262): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/CheckinService( 5605): Checkin interval check for package: unspecified last checkin: 1455027659817 min interval config: 0 actual interval: 26903
,V/DownloadManager( 3262): DownloadService onCreate
I/DownloadManager( 3262): in removeSpuriousFiles
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3262): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@14dcc964 on behalf of 3262
I/DownloadManager( 3262): in trimDatabase
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6887 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3262): DownloadService onStartCommand
V/DownloadManager( 3262): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@20d7fb93 on behalf of 3262
,V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@314f17d0 on behalf of 3262
I/CheckinService( 5605): Checking schedule, now: 1455027686793 next: 1455027689780
I/CheckinService( 5605): active receiver: disabled
,V/DownloadManager( 3262): DownloadService onDestroy
,I/ActivityManager(  962): Killing 6641:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/WeatherAncestor( 2677): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:27
,W/libprocessgroup(  962): failed to open /acct/uid_10079/pid_6641/cgroup.procs: No such file or directory
D/UpdateThreadPoolManager( 2677): 2 : This is isUpdating : false
D/WeatherAncestor( 2677): connectivity changed - connection : true
D/Weather_cast( 2677): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2677): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:27
D/WeatherService( 2677): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6918 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  962): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2677): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2677): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2677): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6918): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6918): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6918): MmsConfig.loadMmsSettings
I/Babel_SMS( 6918): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6918): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6918): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6918): MmsConfig.loadFromResources
,E/Babel_SMS( 6918): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6918): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6918): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6918): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6918): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6918): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6918): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6918): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6918): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6918): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6918): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6918): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6918): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6918): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6918): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6918): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6918): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6918): found sensor: Motion Accel, handle=46
,W/Settings( 6918): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6918): startup - clean
,I/Babel   ( 6918): deleted: false for 0
,I/art     ( 6918): CheckpointMarkThreadRoots callback created = 0xb042d560
I/art     ( 6918): CheckpointMarkThreadRoots callback created = 0xb042d530
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6958 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 6918): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6918): Unsupported mime audio/adpcm
W/AudioCapabilities( 6918): Unsupported mime audio/g726
,W/AudioCapabilities( 6918): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6918): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6918): Unsupported mime video/mjpg
W/VideoCapabilities( 6918): Unsupported mime video/theora
,W/AudioCapabilities( 6918): Unsupported mime audio/evrc
W/AudioCapabilities( 6918): Unsupported mime audio/qcelp
W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6918): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6918): Unsupported mime audio/qcelp
W/AudioCapabilities( 6918): Unsupported mime audio/evrc
,W/VideoCapabilities( 6918): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6918): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6918): onServiceConnected
W/Babel   ( 6918): Attempted to change video mute state without an active call.
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6958): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6958): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6958): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6958):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6958):   adb logcat -s GAv4
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6958): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/NotificationManager( 6918): com.google.android.talk: cancel(10436) by com.google.android.talk
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/GAv4    ( 6958): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ContextImpl( 6958): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/libc-netbsd( 6918): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6918): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6918): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6918): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6918): propertyValue:false
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
W/GAv4    ( 6958): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6958): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 6918): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  962): Killing 6710:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10048/pid_6710/cgroup.procs: No such file or directory
,I/WebViewFactory( 6958): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6958): Time to load native libraries: 2 ms (timestamps 6359-6361)
I/LibraryLoader( 6958): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6958): Binding Chromium to main looper Looper (main, tid 1) {3fe4f5da}
I/LibraryLoader( 6958): Expected native library version number "",actual native library version number ""
I/chromium( 6958): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6958): Initializing chromium process, singleProcess=true
W/art     ( 6958): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6958): ApplicationContext is null in ApplicationStatus
,W/chromium( 6958): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 6958): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6958): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6958): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6958): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6958): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6958): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6958): Remote Branch: 
I/Adreno-EGL( 6958): Local Patches: 
I/Adreno-EGL( 6958): Reconstruct Branch: 
,V/AudioPolicyService(  282): registerClient() client 0xb4027060, uid 10079
,W/AudioManagerAndroid( 6958): Requires BLUETOOTH permission
I/NSApplication( 6958): Starting up...
,I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7022 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  962): Killing 6732:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10086/pid_6732/cgroup.procs: No such file or directory
I/jxcore-log( 5631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5631): 
I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7041 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  962): Killing 6759:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/jxcore-log( 5631): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5631): 
,W/libprocessgroup(  962): failed to open /acct/uid_10081/pid_6759/cgroup.procs: No such file or directory
,W/ResourcesManager( 7041): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  962): Killing 6788:com.lge.email/u0a21 (adj 15): empty #11
,I/art     (  962): Explicit concurrent mark sweep GC freed 19993(1002KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.234ms total 146.387ms
,W/libprocessgroup(  962): failed to open /acct/uid_10021/pid_6788/cgroup.procs: No such file or directory
,I/ActivityManager(  962): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7069 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7069): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7069): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7069): Error finding the version of the Email provider.....
E/Gmail   ( 7069): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7069): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7069): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7069): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7069): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7069): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7069): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7069): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7069): We do not support migrating this version of the Email provider.
I/Gmail   ( 7069): getAccountsCursor
,I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7106 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ActivityManager(  962): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  962): Killing 6818:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/Gmail   ( 7069): Observing account changes for notifications
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup(  962): failed to open /acct/uid_1000/pid_6818/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 7106): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/jxcore-log( 5631): Test app app.js loaded
I/jxcore-log( 5631): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c947b1b added. We now have 1 listener(s)
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
I/jxcore-log( 5631): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5631): 
,I/chromium( 5631): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/BluetoothManagerService(  962): Message: 20
D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@131ffdfd:true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
I/Gmail   ( 7069): getAccountsCursor
,I/AudioManager( 7106): getMode name:com.lge.qremote
,I/Gmail   ( 7069): notifyAccountChanged
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7069): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7069): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/AudioManager( 7106): getMode name:com.lge.qremote
,I/Gmail   ( 7069): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7069): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  962): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7138 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 7069): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicStore( 7138): Database version: 120
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7138): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7138): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7138): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7138): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7138): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7138): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7138): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7138): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@407d0ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7138): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7138): GMSCore installation verified
,I/ConfigStore( 7138): Config Database version: 1
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/MediaRouter( 7138): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 7138): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7138): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7138): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  962): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7172 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7138): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7138): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 7172): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7172): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7172): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  962): Killing 6842:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10011/pid_6842/cgroup.procs: No such file or directory
,I/NotificationManager( 7138): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7172): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7172): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7172): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  962): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7203 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.484ms
,I/HubEmail( 7172): JNI_OnLoad()
I/HubEmail( 7172): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7172): registerNatives()
I/HubEmail( 7172): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7172): registerNativeMethods()
I/HubEmail( 7172): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7172): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7172): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  962): Killing 6861:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 25.492ms
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.940ms
,W/libprocessgroup(  962): failed to open /acct/uid_10038/pid_6861/cgroup.procs: No such file or directory
D/LGDMClient( 7203): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7203): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7203): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7203): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7203): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7203): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  962): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7234 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7203): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7203): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7203): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7203): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7203): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7203): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  962): Killing 6887:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10051/pid_6887/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7234): onCreate
W/AppUp4:DB( 7234):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7234):  setFingerPrint start
I/AppUp4:DB( 7234):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7234):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7234):  SDK version = 0
I/AppUp4:DB( 7234):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7234): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7234): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7234): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7234): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7234): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7234): onReceive
I/AppUp4:CustModeStarterReceiver( 7234): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7234): Context : android.app.ReceiverRestrictedContext@290ebd41
D/AppUp4:CustFacade( 7234): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7234): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7234): begin check event
I/AppUp4:CustModeStarterReceiver( 7234): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7234): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7234): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7234): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7234): handleAsyncCustNotification do not startCustService
I/ActivityManager(  962): Killing 6958:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10079/pid_6958/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3184): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3184): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3184): networkInfo.isConnected() = true
D/PhoneState( 3184): setPdpRejectCasuse : false
I/ActivityManager(  962): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7253 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7253): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7253): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7253): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  962): Killing 7022:com.android.chrome/u0a48 (adj 15): empty #11
,D/PhoneMonitor( 7253): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7253): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7253): [parse] Load xml
V/TelephonyAutoProfiling( 7253): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7253): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7253): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  962): failed to open /acct/uid_10048/pid_7022/cgroup.procs: No such file or directory
,V/DownloadManager( 3262): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3262): DownloadService onCreate
I/DownloadManager( 3262): in removeSpuriousFiles
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 3262): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/ActivityManager(  962): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7274 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3262): DownloadService onStartCommand
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@855e0fc on behalf of 3262
V/DownloadManager( 3262): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/DownloadManager( 3262): in trimDatabase
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@3605c385 on behalf of 3262
V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@3fe4f5da on behalf of 3262
V/DownloadManager( 3262): DownloadService onDestroy
,D/WeatherAncestor( 2677): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:32
,D/UpdateThreadPoolManager( 2677): 2 : This is isUpdating : false
D/WeatherAncestor( 2677): connectivity changed - connection : true
D/Weather_cast( 2677): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2677): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:21:32
D/WeatherService( 2677): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/art     (  962): Explicit concurrent mark sweep GC freed 14814(692KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.526ms total 198.726ms
,V/AlarmManager(  962): RTC_WAKEUP set : Alarm{20999912 type 0 when 1455027689780 com.google.android.gms} when 1455027689780
I/CheckinService( 5605): Checkin interval check for package: unspecified last checkin: 1455027659817 min interval config: 0 actual interval: 32497
I/ActivityManager(  962): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7297 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  962): RTC_WAKEUP set : Alarm{1a54b2e0 type 0 when 1455027692208 com.android.vending} when 1455027692208
,W/ActivityManager(  962): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2677): 2 : Utils getTopActivity com.lge.launcher2 / true
I/CheckinService( 5605): Checking schedule, now: 1455027692345 next: 1455027689780
I/CheckinService( 5605): active receiver: enabled
,D/WeatherService( 2677): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2677): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/CheckinService( 5605): Preparing to send checkin request
,I/EventLogService( 5605): Accumulating logs since 1455027651322
,I/ActivityManager(  962): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7318 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GAv4    ( 7318): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7318):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7318):   adb logcat -s GAv4
I/CheckinRequestBuilder( 5605): Checkin reason type: 8 attempt count: 1
,W/GAv4    ( 7318): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/ActivityThread( 5605): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 6026): Explicit concurrent mark sweep GC freed 2349(101KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 749us total 35.153ms
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7318): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7318): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7318): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7318): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/Finsky  ( 7297): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/GAv4    ( 7318): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7318): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/Finsky  ( 7297): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7297): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7297): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7297): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  962): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7387 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@c9e10e8 on behalf of 7297
D/Ads     ( 7297): Skipping gmscore version check
,D/Finsky  ( 7297): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7297): [1] Libraries$2.run: Finished loading 1 libraries.
,I/WebViewFactory( 7318): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/Finsky  ( 7297): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7297): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 7387): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7387): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/LibraryLoader( 7318): Time to load native libraries: 4 ms (timestamps 1090-1094)
I/LibraryLoader( 7318): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7318): Binding Chromium to main looper Looper (main, tid 1) {3fe4f5da}
,I/LibraryLoader( 7318): Expected native library version number "",actual native library version number ""
I/chromium( 7318): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7318): Initializing chromium process, singleProcess=true
W/art     ( 7318): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7318): ApplicationContext is null in ApplicationStatus
,W/chromium( 7318): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7318): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7318): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7318): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7318): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7318): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7318): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7318): Remote Branch: 
I/Adreno-EGL( 7318): Local Patches: 
I/Adreno-EGL( 7318): Reconstruct Branch: 
I/MultiDex( 7387): VM with version 2.1.0 has multidex support
I/MultiDex( 7387): install
I/MultiDex( 7387): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 7387): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7387): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7387): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1e2cae2a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7387): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7387): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7387): com.google.android.gms: cancel(39789) by com.google.android.gms
I/NSApplication( 7318): Starting up...
,D/Finsky  ( 7297): [920] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
V/AudioPolicyService(  282): registerClient() client 0xb57e9460, uid 10079
W/AudioManagerAndroid( 7318): Requires BLUETOOTH permission
D/Finsky  ( 7297): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     ( 7387): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7387): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/ActivityManager(  962): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7429 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 7041:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,D/NativeLibraryUtils( 7387): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  962): Killing 7069:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10086/pid_7041/cgroup.procs: No such file or directory
,W/libprocessgroup(  962): failed to open /acct/uid_10053/pid_7069/cgroup.procs: No such file or directory
D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): CdmEngine::OpenSession
I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
,I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7452 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  962): Killing 7138:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=3381194866
W/libprocessgroup(  962): failed to open /acct/uid_10081/pid_7138/cgroup.procs: No such file or directory
,W/ResourcesManager( 7452): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 7387): CheckpointMarkThreadRoots callback created = 0xaaf0c960
,I/art     ( 7387): CheckpointMarkThreadRoots callback created = 0xaaf0c940
,I/ActivityManager(  962): Killing 7172:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  962): failed to open /acct/uid_10021/pid_7172/cgroup.procs: No such file or directory
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
,D/LocationInitializer( 5605): Restart initialization of location
E/MDM     ( 1733): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,D/Finsky  ( 7297): [925] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/WVCdm   (  282): CdmEngine::OpenSession
,I/ActivityManager(  962): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7489 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager(  962): android: cancelAsUser(2) by android
,D/libc-netbsd( 7297): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7297): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 7297): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7297): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 7297): propertyValue:false
W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7489): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7489): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7489): Error finding the version of the Email provider.....
E/Gmail   ( 7489): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7489): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7489): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7489): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7489): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7489): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7489): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7489): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7489): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7489): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  962): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  962): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7537 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  962): Explicit concurrent mark sweep GC freed 22931(1082KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.133ms total 169.052ms
,I/Gmail   ( 7489): Observing account changes for notifications
W/ActivityManager(  962): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  962): Killing 7203:com.lge.lgdmsclient/1000 (adj 15): empty #11
V/LGMDMManager( 7106): Create singleton instance
,I/Gmail   ( 7489): notifyAccountChanged
I/Gmail   ( 7489): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7489): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7489): getAccountsCursor
W/art     ( 7106): Suspending all threads took: 15.219ms
I/Gmail   ( 7489): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7489): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/UEI.SmartControl( 7537): Quickset Services start...
,I/UEI.SmartControl( 7537): Manufacture = LGE
D/UEI.SmartControl( 7537): File observer start...
E/UEI.SmartControl( 7537): IR Port is disabled: false
D/UEI.SmartControl( 7537): Starting file observer...
D/UEI.SmartControl( 7537): Extracting JNI libs...
D/UEI.SmartControl( 7537): --- this system supports 32-bit or 64-bit only
W/libprocessgroup(  962): failed to open /acct/uid_1000/pid_7203/cgroup.procs: No such file or directory
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 7106): getMode name:com.lge.qremote
,I/CheckinService( 5605): Checkin interval check for package: unspecified last checkin: 1455027659817 min interval config: 0 actual interval: 35424
,E/MDM     ( 1733): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5605): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,D/UEI.SmartControl( 7537): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7537): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7537): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/ContextImpl( 3650): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/UEI.SmartControl( 7537): --- Selecting new region: 2
I/UEI.SmartControl( 7537): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7537): Platform has CIR...
D/UEI.SmartControl( 7537): NO CIR support, need to check package...
I/UEI.SmartControl( 7537): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7537): QS Service created
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,E/UEI.SmartControl( 7537): QS start get config
,I/Gmail   ( 7489): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7537): Loading JNI Libs...
D/UEI.SmartControl( 7537):  configuring local db...
D/UEI.SmartControl( 7537):  ---- Has DB8: true
,D/UEI.SmartControl( 7537): QS start statue = true Error code = 0
D/UEI.SmartControl( 7537): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7537): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7537): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7537): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7537): IrrcClient ++ 
D/irrcClient( 7537): getIrrcService ++ 
,D/irrcClient( 7537): getIrrcService -- 
D/irrcClient( 7537): IrrcClient -- 
W/irrc_jni( 7537): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7537): Services init done
I/UEI.SmartControl( 7537): Device manager: loading config....
D/UEI.SmartControl( 7537): QS Service init finished
,D/UEI.SmartControl( 7537): QS Service version name: 0.1.73
D/UEI.SmartControl( 7537): QS Service version code: 1073
D/UEI.SmartControl( 7537): Config is loaded...
D/UEI.SmartControl( 7537): Service requested: Control
D/UEI.SmartControl( 7537): Internal service binding...
D/UEI.SmartControl( 7537): -----IControl: 11
D/UEI.SmartControl( 7537): Caller: com.lge.qremote
D/UEI.SmartControl( 7537): ------------ IControl registerCallback...
I/UEI.SmartControl( 7537): Registering callback...
D/UEI.SmartControl( 7537): -----IControl: 19
D/UEI.SmartControl( 7537): Caller: com.lge.qremote
I/UEI.SmartControl( 7537): Registering Services Ready callback...
I/UEI.SmartControl( 7537): Notify client services are ready...
,D/UEI.SmartControl( 7537): -----IControl: 8
D/UEI.SmartControl( 7537): Caller: com.lge.qremote
I/AudioManager( 7106): getMode name:com.lge.qremote
I/ActivityManager(  962): Killing 7274:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/UEI.SmartControl( 7537):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7537): Notify AllClients services are ready: 0
I/ActivityManager(  962): Killing 7234:com.lge.appbox.client/u0a11 (adj 15): empty #12
,I/WVCdm   (  282): CdmEngine::CloseSession
,W/libprocessgroup(  962): failed to open /acct/uid_10051/pid_7274/cgroup.procs: No such file or directory
,W/libprocessgroup(  962): failed to open /acct/uid_10011/pid_7234/cgroup.procs: No such file or directory
,I/AudioManager( 7106): getMode name:com.lge.qremote
I/AudioManager( 7106): getMode name:com.lge.qremote
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=1521844070
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 114769992720; DSPS: 3859298; Offset : -3014780968
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/WVCdm   (  282): CdmEngine::CloseSession
,I/WVCdm   (  282): L3 Terminate.
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MusicWidget( 2599): mDelayedStopHandler : unbind
,I/dex2oat ( 7587): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=38 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/MusicBrowser( 2691): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2691): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2691): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2691): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2691): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2691): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  962):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@240a1117com.lge.music.MediaPlaybackService$6@38487904
,D/MusicBrowser( 2691): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2691): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3dc8ec7d
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
,I/MusicBrowser( 2691): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2691): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2691): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2691): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2691): reset
V/MediaPlayer[Native]( 2691): setListener
V/MediaPlayer[Native]( 2691): disconnect
,V/MediaPlayer[Native]( 2691): destructor
V/AudioFlinger(  282): releasing 19 from 2691 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/MediaPlayer[Native]( 2691): disconnect
D/MusicBrowser( 2691): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2691): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2691): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2691): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2691): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2691): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2691): [SmartShareManagerClient] unregisterListener: 684912365
W/SmartShareClient( 2691): [SmartShareManagerClient] unregisterListener invalid listener: 684912365
I/dex2oat ( 7587): dex2oat took 138.079ms (threads: 4)
I/SmartShareClient( 2691): [SmartShareManagerClient] terminate service: 2691/MediaPlaybackService/558029387
E/HomeCloudIF( 2691): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2691): [SmartShareManagerClient] unbindService context:android.app.Application@1eea2122
V/CloudHub( 2691): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2691): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2691): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/Adreno-EGL( 7387): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7387): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7387): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7387): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7387): Remote Branch: 
I/Adreno-EGL( 7387): Local Patches: 
I/Adreno-EGL( 7387): Reconstruct Branch: 
I/MusicBrowser( 2691): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2691): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  962): Killing 6918:com.google.android.talk/u0a61 (adj 15): empty #11
I/CloudHub( 2691): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29990
,W/libprocessgroup(  962): failed to open /acct/uid_10061/pid_6918/cgroup.procs: No such file or directory
,I/Adreno-EGL( 7387): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7387): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7387): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7387): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7387): Remote Branch: 
I/Adreno-EGL( 7387): Local Patches: 
I/Adreno-EGL( 7387): Reconstruct Branch: 
,I/Adreno-EGL( 7387): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7387): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7387): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7387): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7387): Remote Branch: 
I/Adreno-EGL( 7387): Local Patches: 
I/Adreno-EGL( 7387): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5605): Classify the device as Phone.
,D/libc-netbsd( 5605): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5605): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5605): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5605): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 5605): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd( 5605): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5605): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5605): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5605): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5605): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5605): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5605): Sending checkin request (9854 bytes)
,I/CheckinRequestBuilder( 5605): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5605): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5605): Classify the device as Phone.
,I/GAV2    ( 7489): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 5605): Google Analytics 8.4.89 is starting up.
,I/CheckinTask( 5605): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5605): Checking schedule, now: 1455027699931 next: 1455554948927
I/CheckinService( 5605): active receiver: disabled
,I/CheckinService( 5605): Checking schedule, now: 1455027699968 next: 1455554948927
I/CheckinService( 5605): active receiver: disabled
,D/CheckinService( 5605): Recording last checkin time for package unspecified as 1455027699976
V/SetupWizard( 7253): Connected to Gservices successfully
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  962): Killing 7429:com.android.chrome/u0a48 (adj 15): empty #11
,I/ActivityManager(  962): Killing 7318:com.google.android.apps.magazines/u0a79 (adj 15): empty #12
,W/libprocessgroup(  962): failed to open /acct/uid_10048/pid_7429/cgroup.procs: No such file or directory
,W/libprocessgroup(  962): failed to open /acct/uid_10079/pid_7318/cgroup.procs: No such file or directory
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 7537): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1368): onReceive = android.intent.action.PACKAGE_CHANGED
I/ActivityManager(  962): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7626 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 22.584ms
,I/[SystemUI]QSlideListController( 1368): onReceive = android.intent.action.PACKAGE_CHANGED
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.558ms
W/[SystemUI]QSlideLoader( 1368): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
D/administrator(  962): Handling package changes for user 0
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1368): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1368): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 22.351ms
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7626): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  962): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  962): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  962): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  962): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  962): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  962): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@343650fa
,W/ResourcesManager(  962): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Babel_SMS( 7626): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7626): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7626): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7626): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7626): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7626): MmsConfig.loadFromResources
E/Babel_SMS( 7626): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7626): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7626): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7626): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7626): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7626): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7626): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7626): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7626): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7626): found sensor: LGE Step Detector Sensor, handle=43
,D/SensorManager( 7626): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7626): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7626): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7626): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7626): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7626): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7626): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7626): found sensor: Motion Accel, handle=46
W/ResourceType(  962): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,W/Settings( 7626): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7626): startup - clean
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  962): applying state to connected service
,I/Babel   ( 7626): deleted: false for 0
,I/art     ( 7626): CheckpointMarkThreadRoots callback created = 0xaaf3e640
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/art     ( 7626): CheckpointMarkThreadRoots callback created = 0xaaf3e620
,W/AudioCapabilities( 7626): Unsupported mime audio/x-lg-flac
,I/ActivityManager(  962): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7663 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 28980(1986KB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 13MB/22MB, paused 2.658ms total 138.950ms
,W/AudioCapabilities( 7626): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7626): Unsupported mime audio/g726
W/AudioCapabilities( 7626): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7626): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7626): Unsupported mime video/mjpg
W/VideoCapabilities( 7626): Unsupported mime video/theora
,W/AudioCapabilities( 7626): Unsupported mime audio/evrc
,W/AudioCapabilities( 7626): Unsupported mime audio/qcelp
W/VideoCapabilities( 7626): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7626): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7626): Unsupported mime audio/qcelp
W/AudioCapabilities( 7626): Unsupported mime audio/evrc
I/AppUp4:AppBoxCP( 7663): onCreate
,W/AppUp4:DB( 7663):  [AppBoxDatabaseHelper] construct
W/VideoCapabilities( 7626): Unsupported mime video/mp4v-esdp
,I/AppUp4:DB( 7663):  setFingerPrint start
I/AppUp4:DB( 7663):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7663):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7663):  SDK version = 0
I/AppUp4:DB( 7663):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7663): AppBoxApplication onCreate()
I/VideoCapabilities( 7626): Unsupported profile 4 for video/mp4v-es
I/AppUp4:CustModeStarterReceiver( 7663): onReceive
I/AppUp4:CustModeStarterReceiver( 7663): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7663): Context : android.app.ReceiverRestrictedContext@346d9f1a
D/AppUp4:CustFacade( 7663): isCustomizationCompleted : false
,W/VideoCapabilities( 7626): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7626): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7626): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7626): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  962): Process com.android.vending (pid 7297) has died
,D/AppUp4:CustFacade( 7663): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7663): begin check event
I/AppUp4:CustModeStarterReceiver( 7663): Event For Nothing, skip.
I/ActivityManager(  962): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7687 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 7626): onServiceConnected
,W/Babel   ( 7626): Attempted to change video mute state without an active call.
,I/NotificationManager( 7626): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7626): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7626): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7687): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7687): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7687): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 7626): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7626): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7626): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7626): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 7687): Total System Memory = 906309632
,I/GalleryUtils( 7687): Application Heap = 96 MB
I/AppConfig( 7687): App Tier : NOT_DEF
D/SystemHelper( 7687): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  962): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7712 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 7452:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10086/pid_7452/cgroup.procs: No such file or directory
,W/ResourcesManager( 7712): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7712): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7712): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7712): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7712): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7712): BUILD Country: EU
I/SystemConfig( 7712): BUILD Operator: OPEN
,I/ActivityManager(  962): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7734 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  962): Killing 7489:com.google.android.gm/u0a53 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  962): failed to open /acct/uid_10053/pid_7489/cgroup.procs: No such file or directory
,I/SystemConfig( 7712): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7712): existFile = false
I/SystemConfig( 7712): canReadFile = false
I/SystemConfig( 7712): systemFeature RCS result false
D/SystemConfig( 7712): refreshRcsSupport() :false
,I/LockScreenSettings( 7734): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/art     (  962): Explicit concurrent mark sweep GC freed 24102(1242KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.140ms total 145.370ms
,D/LockScreenSettings( 7734): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7734): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7734): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7734): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7734): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7751 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  962): Killing 2691:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  282): 2691 died, releasing its sessions
V/AudioFlinger(  282):  pid 1751 @ 0
V/AudioFlinger(  282):  pid 3184 @ 1
,V/AudioFlinger(  282):  pid 3184 @ 2
W/libprocessgroup(  962): failed to open /acct/uid_10028/pid_2691/cgroup.procs: No such file or directory
,W/ResourcesManager( 7751): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  962): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7776 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 76 ms] updated apps [took 75 ms] 
,I/ActivityManager(  962): Killing 7253:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10038/pid_7253/cgroup.procs: No such file or directory
,I/art     ( 6026): Explicit concurrent mark sweep GC freed 3253(133KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 422us total 33.871ms
,D/Finsky  ( 7776): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/Finsky  ( 7776): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7776): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7776): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7776): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3262): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3262): created cursor android.database.sqlite.SQLiteCursor@3e41301 on behalf of 7776
D/Finsky  ( 7776): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7776): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7776): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 7776): Skipping gmscore version check
D/PackageBroadcastService( 5605): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5605): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7776): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5605): updateResources: need to parse f{com.google.android.gms}
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/Icing   ( 5605): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5605): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  962): Killing 7387:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  962): failed to open /acct/uid_10006/pid_7387/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  962): Killing 7537:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7106): android.os.DeadObjectException
,W/System.err( 7106): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7106): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7106): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7106): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7106): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7106): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7106): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7106): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7106): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7106): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7106): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7106): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7106): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7106): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7106): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7106): android.os.DeadObjectException
W/System.err( 7106): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7106): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7106): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7106): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7106): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7106): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7106): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7106): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 7106): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7106): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7106): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7106): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7106): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7106): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7106): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  962): failed to open /acct/uid_10089/pid_7537/cgroup.procs: No such file or directory
W/ActivityManager(  962): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  962): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7836 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7836): Quickset Services start...
,I/UEI.SmartControl( 7836): Manufacture = LGE
D/UEI.SmartControl( 7836): File observer start...
E/UEI.SmartControl( 7836): IR Port is disabled: false
D/UEI.SmartControl( 7836): Starting file observer...
D/UEI.SmartControl( 7836): Extracting JNI libs...
D/UEI.SmartControl( 7836): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7836): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7836): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7836): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7836): --- Selecting new region: 2
,I/UEI.SmartControl( 7836): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7836): Platform has CIR...
D/UEI.SmartControl( 7836): NO CIR support, need to check package...
I/UEI.SmartControl( 7836): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7836): QS Service created
E/UEI.SmartControl( 7836): QS start get config
,D/UEI.SmartControl( 7836): Loading JNI Libs...
,D/UEI.SmartControl( 7836):  configuring local db...
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7836):  ---- Has DB8: true
,D/UEI.SmartControl( 7836): QS start statue = true Error code = 0
D/UEI.SmartControl( 7836): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7836): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/charger_monitor(  484): init target 500000
D/UEI.SmartControl( 7836): IRRCDataComm has AudioManager!!!!.
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
W/irrc_jni( 7836): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7836): IrrcClient ++ 
D/irrcClient( 7836): getIrrcService ++ 
D/irrcClient( 7836): getIrrcService -- 
D/irrcClient( 7836): IrrcClient -- 
W/irrc_jni( 7836): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7836): Services init done
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
,I/UEI.SmartControl( 7836): Device manager: loading config....
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/UEI.SmartControl( 7836): QS Service init finished
D/UEI.SmartControl( 7836): QS Service version name: 0.1.73
D/UEI.SmartControl( 7836): QS Service version code: 1073
D/UEI.SmartControl( 7836): Service requested: Control
D/charger_monitor(  484): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/UEI.SmartControl( 7836): Config is loaded...
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/UEI.SmartControl( 7836):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 7836): Request IControl service: devices are loaded...
I/UEI.SmartControl( 7836): Notify AllClients services are ready: 0
,I/ActivityManager(  962): Killing 7106:com.lge.qremote/u0a106 (adj 15): empty #11
D/WifiController(  962): battery changed pluggedType: 2
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
W/libprocessgroup(  962): failed to open /acct/uid_10106/pid_7106/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7836): Internal service binding...
,D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7836): Internal timer expired: 1
,D/UEI.SmartControl( 7836): Service.onUnbind: IControl
D/UEI.SmartControl( 7836): Service.onDestroy
W/System.err( 7836): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@2a28b2d4
W/System.err( 7836): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7836): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7836): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7836): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7836): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7836): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7836): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7836): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7836): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7836): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7836): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7836): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7836): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7836): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7836): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7836): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@2a28b2d4
D/UEI.SmartControl( 7836): Shutdown IRRCPlayer... 
,W/irrc_jni( 7836): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7836): ~IrrcClient ++ 
D/irrcClient( 7836): ~IrrcClient -- 
W/irrc_jni( 7836): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7836): Blaster closed
D/UEI.SmartControl( 7836): Blaster closed
D/UEI.SmartControl( 7836): Shut down QS...
D/UEI.SmartControl( 7836): Stopped file observer...
I/UEI.SmartControl( 7836): QS lib stop result = true
D/UEI.SmartControl( 7836): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 134770888651; DSPS: 4514687; Offset : -3014769864
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/PowerManagerServiceEx(  962): acquireWakeLockInternal: lock=591329745, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=962
,D/WeatherService( 2677): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:22:0
,D/WeatherService( 2677): 2 : TimeTick Intent And Screen On
D/WeatherService( 2677): 2 : SDK version : 21
W/ActivityManager(  962): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2677): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2677): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2677): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2677): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2677): 2 : This is isUpdating : false
D/WeatherService( 2677): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2677): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2677): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2677): 2 : Fixed theme : optimus
D/WeatherReflect( 2677): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
,D/lim     ( 2677): 2 : time = 15:22
I/WeatherReflect( 2677): Model Name : LG-D722
D/WeatherTheme( 2677): 2 : Different view - status_min_formatted : 21 != 22
D/WeatherTheme( 2677): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2677): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/[SystemUI]Clock( 1368): called onTimeUpdated()
I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
,I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/Theme   ( 2677): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2677): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/Weather4x2_optimus( 2677): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2677): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2677): forecast size is 0
D/Theme   ( 2677): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2677): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2677): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2677): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2677): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2677): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2677): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2677): url is : null
D/Theme   ( 2677): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2677): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2677): 2 : update view, appWidgetId: 2
D/WeatherService( 2677): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:22:0
D/PowerManagerServiceEx(  962): releaseWakeLockInternal: lock=591329745 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{3a943c36 type 2 when 144480 com.google.android.gms} when 144480
,I/VacuumService( 1733): Vacuum at: now=1455027726756 tag=VacuumService
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  962): ALS enabled for SRE
,D/PowerManagerServiceEx(  962): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (30998 ms ago)
D/qdlights(  962): set_light_backlight: 252
,D/qdlights(  962): set_light_backlight: 248
D/qdlights(  962): set_light_backlight: 245
,D/qdlights(  962): set_light_backlight: 242
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/qdlights(  962): set_light_backlight: 238
,D/qdlights(  962): set_light_backlight: 235
,D/qdlights(  962): set_light_backlight: 232
,D/qdlights(  962): set_light_backlight: 228
,D/qdlights(  962): set_light_backlight: 225
,D/qdlights(  962): set_light_backlight: 222
,D/qdlights(  962): set_light_backlight: 218
,D/qdlights(  962): set_light_backlight: 215
,D/qdlights(  962): set_light_backlight: 212
,D/qdlights(  962): set_light_backlight: 208
,D/qdlights(  962): set_light_backlight: 205
,D/qdlights(  962): set_light_backlight: 202
,D/qdlights(  962): set_light_backlight: 198
,D/qdlights(  962): set_light_backlight: 195
,D/qdlights(  962): set_light_backlight: 192
,D/qdlights(  962): set_light_backlight: 188
,D/qdlights(  962): set_light_backlight: 185
,D/qdlights(  962): set_light_backlight: 182
,D/qdlights(  962): set_light_backlight: 178
,D/qdlights(  962): set_light_backlight: 175
,D/qdlights(  962): set_light_backlight: 172
,D/qdlights(  962): set_light_backlight: 168
,D/qdlights(  962): set_light_backlight: 165
,D/qdlights(  962): set_light_backlight: 162
,D/qdlights(  962): set_light_backlight: 158
,D/qdlights(  962): set_light_backlight: 155
,D/qdlights(  962): set_light_backlight: 152
,D/qdlights(  962): set_light_backlight: 148
,D/qdlights(  962): set_light_backlight: 145
,D/qdlights(  962): set_light_backlight: 142
,D/qdlights(  962): set_light_backlight: 138
,D/qdlights(  962): set_light_backlight: 135
,D/qdlights(  962): set_light_backlight: 132
,D/qdlights(  962): set_light_backlight: 128
,D/qdlights(  962): set_light_backlight: 125
,D/qdlights(  962): set_light_backlight: 122
,D/qdlights(  962): set_light_backlight: 118
,D/qdlights(  962): set_light_backlight: 115
,D/qdlights(  962): set_light_backlight: 112
,D/qdlights(  962): set_light_backlight: 108
,D/qdlights(  962): set_light_backlight: 105
,D/qdlights(  962): set_light_backlight: 102
,D/qdlights(  962): set_light_backlight: 98
,D/qdlights(  962): set_light_backlight: 95
,D/qdlights(  962): set_light_backlight: 92
,D/qdlights(  962): set_light_backlight: 88
,D/qdlights(  962): set_light_backlight: 85
,D/qdlights(  962): set_light_backlight: 82
,D/qdlights(  962): set_light_backlight: 78
,D/qdlights(  962): set_light_backlight: 75
,D/qdlights(  962): set_light_backlight: 72
,D/qdlights(  962): set_light_backlight: 68
,D/qdlights(  962): set_light_backlight: 65
,D/qdlights(  962): set_light_backlight: 62
,D/qdlights(  962): set_light_backlight: 58
,D/qdlights(  962): set_light_backlight: 55
,D/qdlights(  962): set_light_backlight: 52
,D/qdlights(  962): set_light_backlight: 48
,D/qdlights(  962): set_light_backlight: 45
,D/qdlights(  962): set_light_backlight: 42
,D/qdlights(  962): set_light_backlight: 38
,D/qdlights(  962): set_light_backlight: 35
,D/qdlights(  962): set_light_backlight: 32
,D/qdlights(  962): set_light_backlight: 28
,D/qdlights(  962): set_light_backlight: 25
,D/qdlights(  962): set_light_backlight: 22
,D/qdlights(  962): set_light_backlight: 18
,D/qdlights(  962): set_light_backlight: 15
,D/qdlights(  962): set_light_backlight: 12
,D/qdlights(  962): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 154771640102; DSPS: 5170072; Offset : -3014781587
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  962): ALS enabled for SRE
D/PowerManagerServiceEx(  962): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (37990 ms ago)
I/PowerManagerService(  962): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  962): ALS enabled for SRE
D/PowerManagerServiceEx(  962): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (38003 ms ago)
,W/ContextImpl(  962): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  962): Sleeping (uid 1000)...
D/LPWGController(  962): [updateScreenState] screen on = false
D/LPWGController(  962): disable proximity sensor
,D/LPWGController(  962): enable proximity sensor
I/SensorManager(  962): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@f24e62f] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  962): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  962): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  962): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  962): activate: handle is 48, enable
V/sensors_hal_Ctx(  962): activate sensors is 1400000000000
D/sensors_hal_Thresh(  962): enable: handle=48
I/sensors_hal_SAM(  962): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  962): waitForResponse: timeout=1000
V/sensors_hal_SAM(  962): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  962): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  962): enable: Received response: 0
D/PowerManagerServiceEx(  962): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (38040 ms ago)
I/Adreno-EGL(  962): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  962): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  962): Build Date: 03/02/15 Mon
I/Adreno-EGL(  962): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  962): Remote Branch: 
I/Adreno-EGL(  962): Local Patches: 
I/Adreno-EGL(  962): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (2700 us)
,I/Sensors (  422): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  962): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  962): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  962): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  962): processInd: handle 48, count=1
V/sensors_hal_Thresh(  962): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  962): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  962): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  962): poll: count: 256
I/sensors_hal_Ctx(  962): poll: released wakelock sensor_ind
D/sensors_hal_Util(  962): waitForResponse: timeout=0
D/LPWGController(  962): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
,I/LPWGController(  962): current mode = 1  value = 1 1
I/LPWGController(  962): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  962): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/qdlights(  962): set_light_backlight: 0
,I/SensorManager(  962): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  962): activate: handle is 46, disable
V/sensors_hal_Ctx(  962): activate sensors is 1000000000000
D/sensors_hal_LP2(  962): enable: handle=46
D/sensors_hal_LP2(  962): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  962): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  962): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  962): Display changed displayId=0
,V/sensors_hal_SAM(  962): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
,D/sensors_hal_LP2(  962): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1751): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
D/SurfaceControl(  962): Excessive delay in setPowerMode(): 196ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  962): Got set_interactive hint
D/KeyguardViewMediator( 1368): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1368): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1368): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1368): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1368): unregisterProximitySensor
,D/StatusBarWindowView( 1368): onScreenTurnedOff why = 3
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/WifiServerServiceExt(  962): sendKtScanInterval  mRtspPlay : false
V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 962
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
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/WifiServerServiceExt(  962): set CMD_KT_SCAN_INTERVAL
,D/GpsLocationProvider(  962): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDHandler( 1803): RESTART MSG
D/Cliptray Service( 1803): lockStatus = 0
I/Sensors (  422): sns_pwr.c(301):releasing wakelock
D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
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
D/Ulp_jni (  962): JNI:system_update. Event-0
,D/SplitWindow(  962): check instance of lgWin Window{1a186b1a u0 SearchPanel}
,D/InputDispatcher(  962): Window went away: Window{133125ca u0 SearchPanel}
,I/[SystemUI]Clock( 1368): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1368): time changed, timezoneChanged : false
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2677): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:22:22
,D/WeatherService( 2677): 2 : ACTION screen on
,D/WeatherService( 2677): 2 : shouldTimeTickRegistered : false
,D/Weather_cast( 2677): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2677): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:22:22
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_ON
D/AppCleanupService( 4108): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 962
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
,V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
,V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
D/WifiController(  962): CMD_SCREEN_OFF 
D/WifiController(  962): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  962): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
I/LEDService( 1803): updateLightsLocked : turn on led
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2677): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:22:22
D/WeatherService( 2677): 2 : ACTION screen off
D/WeatherService( 2677): 2 : TimeTick Receiver Unregister
D/WeatherService( 2677): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:22:22
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  962): ACTION_SCREEN_OFF
D/AppCleanupService( 4108): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4108): AppUsageStatsSaveTask
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
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{3d23b64b type 2 when 163975 com.android.systemui} when 163975
,D/KeyguardViewMediator( 1368): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1751): getCallState : 0
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1368): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1368): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 174772323167; DSPS: 5825454; Offset : -3014769570
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{32c1a828 type 2 when 183785 android} when 183785
,D/charger_monitor(  484): init target 500000
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{14a0f941 type 2 when 190086 com.google.android.gms} when 190086
,I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 13434 seconds from now (1455027772403)
,D/GetConfigurationSnapshotOperation( 1733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  962): android: cancelAsUser(2) by android
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 194773065764; DSPS: 6480839; Offset : -3014790694
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 214773816120; DSPS: 7136223; Offset : -3014772238
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 234774494081; DSPS: 7791606; Offset : -3014796574
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  484): init target 500000
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 254775215011; DSPS: 8446989; Offset : -3014776896
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 274775888649; DSPS: 9102371; Offset : -3014774593
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5631): TAP version 13
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # multiplex can send data
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 1 String should be length:200
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # enqueue and run in order
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 2 firstPromise setTimeout
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 3 firstPromise result
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 4 firstPromise testValue
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 5 secondPromise setTimeout
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 6 secondPromise result
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 7 secondPromise testValue
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 8 thirdPromise in promise
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 9 thirdPromise result
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 10 thirdPromise testValue
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # basic
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 11 sane
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # another
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 12 sane
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 13 should be equal
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 14 null
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 15 (unnamed assert)
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 16 should be equal
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 17 should not throw
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 18 (unnamed assert)
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 19 (unnamed assert)
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 20 should not throw
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 21 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 22 should be equal
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 23 should be equal
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # failed to get mobile documents path
I/jxcore-log( 5631): 
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 24 should be equal
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 25 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 26 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 27 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # #init should register the networkChanged event
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 28 should be equal
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # #startBroadcasting should throw on null device name
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 29 should throw
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 30 should throw
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 31 should throw
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 32 should throw
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # #startBroadcasting should throw on negative port
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 33 should throw
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # #startBroadcasting should throw on too large port
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 34 should throw
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 35 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 36 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 37 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 38 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 39 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 40 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 41 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 42 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 43 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 44 should be equal
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 45 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 46 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 47 should be equal
I/jxcore-log( 5631): 
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 294779056974; DSPS: 9757835; Offset : -3014782153
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 48 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 49 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 50 should be equal
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 51 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 52 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 53 should be equal
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # #start should fail if called twice in a row
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 54 specific error should be received
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 55 specific error should be returned
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 56 error should be null
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 57 error should be null
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 58 error should be null
I/jxcore-log( 5631): 
I/jxcore-log( 5631): ok 59 error should be null
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 60 error should be null
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 61 error should be null
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): ok 62 specific error should be returned
I/jxcore-log( 5631): 
I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5631): 
,I/jxcore-log( 5631): # teardown
I/jxcore-log( 5631): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a9cd4b8 added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027877975.5631
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027877975.5631","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027877975.5631, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027877975.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: {"pi":"F8:95:C7:87:85:54","pn":"1455027877975.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455027877975.5631","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5631): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1964): BTA_JvCreateRecordByUser
,D/LGBluetoothServiceAdapter( 1964): [BTUI] createSocketChannel FD=87 mFd=85
I/bt-btif ( 1964): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Waiting for incoming connections...
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a48d760e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a48d760e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState add service
,D/LGWifiP2pService(  962): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): start: Starting P2P device discovery...
,D/LGWifiP2pService(  962): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027877975.5631, mode: WIFI
D/LGWifiP2pService(  962): discovery change broadcast true
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 2809): p2p0: CTRL-EVENT-SCAN-STARTED 
I/io.jxcore.node.ConnectionHelper( 5631): start: OK
D/WfdsMonitor( 1803): Event [CTRL-EVENT-SCAN-STARTED ]
I/jxcore-log( 5631): ok 63 Should be able to call startBroadcasting without error
I/jxcore-log( 5631): 
I/io.jxcore.node.ConnectionHelper( 5631): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): onServerStopped
I/bt-btif ( 1964): BTA_JvDeleteRecord
I/bt-btif ( 1964): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): stop: Stopping services
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5631): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: NOT_STARTED
I/jxcore-log( 5631): ok 64 Should be able to call stopBroadcasting without error
I/jxcore-log( 5631): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a68464 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  962): remove client information from framework
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local services cleared successfully
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
I/wpa_supplicant( 2809): P2P-FIND-STOPPED 
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/LGWifiP2pService(  962): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5631): Service requests cleared successfully
D/LGWifiP2pService(  962): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): discovery change broadcast false
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878186.5631
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878186.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5631): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1964): BTA_JvCreateRecordByUser
I/bt-btif ( 1964): BTA_JvRfcommStartServer
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878186.5631, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878186.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: {"pi":"F8:95:C7:87:85:54","pn":"1455027878186.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455027878186.5631","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3400c1d8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3400c1d8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState add service
D/LGWifiP2pService(  962): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878186.5631, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5631): start: OK
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5631): ok 65 Should be able to call startBroadcasting without error
I/jxcore-log( 5631): 
I/io.jxcore.node.ConnectionHelper( 5631): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): shutdown
I/bt-btif ( 1964): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: NOT_STARTED
I/bt-btif ( 1964): BTA_JvRfcommStopServer
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): stop: Stopping services
D/LGWifiP2pService(  962): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): onServerStopped
D/LGWifiP2pService(  962): InactiveState{ when=-3ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): stop: Stopping P2P device discovery...
I/wpa_supplicant( 2809): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: NOT_INITIALIZED
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
D/LGWifiP2pService(  962): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: No more listeners, de-initializing...
D/LGWifiP2pService(  962): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5631): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  962): remove client information from framework
D/LGWifiP2pService( , 962): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local services cleared successfully
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5631): Service requests cleared successfully
I/jxcore-log( 5631): ok 66 Should be able to call stopBroadcasting without error
I/jxcore-log( 5631): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37982d0 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878244.5631
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878244.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5631): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878244.5631, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
W/BluetoothAdapter( 5631): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878244.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: {"pi":"F8:95:C7:87:85:54","pn":"1455027878244.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455027878244.5631","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): start: Starting P2P device discovery...
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4275e2a2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4275e2a2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: RUNNING_WIFI
,D/LGWifiP2pService(  962): P2pEnabledState add service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
D/LGWifiP2pService(  962): add a new client
I/io.jxcore.node.ConnectionHelper( 5631): start: OK
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 5631): ok 67 Should be able to call startBroadcasting without error
I/jxcore-log( 5631): 
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5631): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stop: Stopping peer discovery...
D/LGWifiP2pService(  962): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): stop: Stopping services
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): release: No more listeners, de-initializing...
I/bt-btif ( 1964): BTA_JvCreateRecordByUser
I/bt-btif ( 1964): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Waiting for incoming connections...
D/LGWifiP2pService(  962): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5631): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878244.5631, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
,D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  962): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): initialize: My bluetooth address is F8:95:C7:87:85:54
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): bind: Binding a new listener
I/jxcore-log( 5631): ok 68 Should be able to call stopBroadcasting without error
I/jxcore-log( 5631): 
D/LGWifiP2pService(  962): InactiveState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-4ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service request
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-4ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): discovery change broadcast false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Maximum number of connection attempt retries: 0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@98408da added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: {"pi":"F8:95:C7:87:85:54","pn":"1455027878244.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455027878244.5631","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI,, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4275e2a2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4275e2a2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState add service
D/LGWifiP2pService(  962): add a new client
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5631): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878244.5631, mode: BLE_AND_WIFI
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): constructBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  962): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5631): setAdvertiseSettings: Mode: 1, Tx power level: 1, timeout: 0, is connectable: true
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878297.5631
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5631): setScanSettings: Mode: 1, report delay in milliseconds: 0, scan result type: 0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5631): start
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory( 5631): createAdvertiseData: From: 1455027878244.5631 b6a44ad1-d319-4b3a-815d-8b805a47fb51 F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878297.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): startListeningForIncomingConnections: Starting...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5631): setAdvertiseData: AdvertiseData [mServiceUuids=[], mManufacturerSpecificData={76=[2, 21, -74, -92, 74, -47, -45, 25, 75, 58, -127, 93, -117, -128, 90, 71, -5, 81, -8, -107, -57, -121, -123, 84]}, mServiceData={}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: Using peer discovery mode: WIFI
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5631): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878297.5631, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): bind: Binding a new listener
I/bt-btif ( 1964): BTA_JvCreateRecordByUser
I/bt-btif ( 1964): BTA_JvRfcommStartServer
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGBluetoothServiceAdapter( 1964): [BTUI] createSocketChannel FD=88 mFd=87
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Waiting for incoming connections...
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878297.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: {"pi":"F8:95:C7:87:85:54","pn":"1455027878297.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455027878297.5631","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  962): InactiveState{ when=0 what=139292 arg2=3 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@26357712 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139292 arg2=3 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@26357712 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: OK
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139265 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2809): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 5631): ok 69 Should be able to call startBroadcasting without error
I/jxcore-log( 5631): 
I/io.jxcore.node.ConnectionHelper( 5631): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 2 listener(s) left
I/bt-btif ( 1964): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: NOT_STARTED
I/bt-btif ( 1964): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stop: Stopping peer discovery...
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): onServerStopped
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5631): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: NOT_STARTED
I/jxcore-log( 5631): ok 70 Should be able to call stopBroadcasting without error
I/jxcore-log( 5631): 
D/LGWifiP2pService(  962): remove client information from framework
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Maximum number of connection attempt retries: 0
I/wpa_supplicant( 2809): P2P-FIND-STOPPED 
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23b802e7 added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/LGWifiP2pService(  962): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service request
D/LGWifiP2pService(  962): InactiveState{ ,when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
D/LGWifiP2pService(  962): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BtGatt.GattService( 1964): registerClient() - UUID=5d3ea44c-b999-42e4-a5a8-1b4aabd12883
,I/bt-btif ( 1964): HAL bt_gatt_callbacks->client->register_client_cb
,D/BtGatt.GattService( 1964): onClientRegistered() - UUID=5d3ea44c-b999-42e4-a5a8-1b4aabd12883, clientIf=6
,D/BluetoothLeScanner( 5631): onClientRegistered() - status=0 clientIf=6
D/BtGatt.GattService( 1964): start scan with filters
D/BtGatt.ScanManager( 1964): handling starting scan
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5631): setState: State changed from NOT_STARTED to STARTING
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser( 5631): start: No BLE advertiser instance
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
I/bt-btif ( 1964): BTA_DmBleObserve:start = 1 
D/BtGatt.ScanManager( 1964): configureRegularScanParams() - queue=1
D/BtGatt.ScanManager( 1964): configureRegularScanParams() - ScanSetting Scan mode=1 mLastConfiguredScanSetting=-2147483648
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5631): stop
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: RESTARTING
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery started successfully
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139268 arg2=8 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: RUNNING
,D/BtGatt.GattService( 1964): stopScan() - queue size =1
I/bt-btif ( 1964): BTA_DmBleObserve:start = 0 
D/BtGatt.GattService( 1964): unregisterClient() - clientIf=6
I/bt-btif ( 1964): BTA_DmBleObserve:start = 1 
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5631): stop: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner( 5631): setState: State changed from STARTING to NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer( 5631): onIsScannerStartedChanged: false
D/WifiP2pManager( 5631): Ignored { when=-66ms what=139313 target=android.net.wifi.p2p.WifiP2pManager$Channel$P2pHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopBlePeerDiscoverer: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5631): Service requests cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopWifiPeerDiscovery: Stopped
D/BtGatt.ScanManager( 1964): stop scan
I/bt-btif ( 1964): BTA_DmBleObserve:start = 0 
D/BtGatt.ScanManager( 1964): configureRegularScanParams() - queue=0
D/BtGatt.ScanManager( 1964): configureRegularScanParams() - ScanSetting Scan mode=-2147483648 mLastConfiguredScanSetting=1
D/BtGatt.ScanManager( 1964): configureRegularScanParams() - queue emtpy, scan stopped
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139298 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139298 arg2=9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139268 arg2=10 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local services cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=139307 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/LGWifiP2pService(  962): P2pEnabledState{ when=-3ms what=139307 arg2=11 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/LGWifiP2pService(  962): P2pEnabledState clear service request
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5631): Service requests cleared successfully
,D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878357.5631
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878357.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: RUNNING
,D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5631): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878357.5631, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/bt-btif ( 1964): BTA_JvCreateRecordByUser
I/bt-btif ( 1964): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878357.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: {"pi":"F8:95:C7:87:85:54","pn":"1455027878357.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455027878357.5631","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139292 arg2=12 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@46032a58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139292 arg2=12 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@46032a58 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState add service
D/LGWifiP2pService(  962): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local service added successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): start: Starting P2P device discovery...
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139265 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=139265 arg2=13 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: true
D/LGWifiP2pService(  962): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 5631): ok 71 Should be able to call startBroadcasting without error
I/jxcore-log( 5631): 
I/io.jxcore.node.ConnectionHelper( 5631): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 2 listener(s) left
I/bt-btif ( 1964): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: NOT_STARTED
I/bt-btif ( 1964): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): onServerStopped
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139298 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139298 arg2=14 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.Discover,yManager( 5631): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5631): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  962): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local services cleared successfully
I/jxcore-log( 5631): ok 72 Should be able to call stopBroadcasting without error
I/jxcore-log( 5631): 
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139268 arg2=15 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): P2P-FIND-STOPPED 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Maximum number of connection attempt retries: 0
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10423d3d added. We now have 7 listener(s)
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=139307 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/LGWifiP2pService(  962): P2pEnabledState{ when=-2ms what=139307 arg2=16 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service request
,D/LGWifiP2pService(  962): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5631): Service requests cleared successfully
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
D/LGWifiP2pService(  962): discovery change broadcast false
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878458.5631
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878458.5631","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5631): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5631): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1964): BTA_JvCreateRecordByUser
I/bt-btif ( 1964): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878458.5631, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878458.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: {"pi":"F8:95:C7:87:85:54","pn":"1455027878458.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455027878458.5631","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139292 arg2=17 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2978edd4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139292 arg2=17 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2978edd4 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  962): P2pEnabledState add service
D/LGWifiP2pService(  962): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): start: Starting P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: RESTARTING
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local service added successfully
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139265 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139265 arg2=18 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: STARTED
D/LGWifiP2pService(  962): discovery change broadcast true
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=139268 arg2=19 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): P2P-FIND-STOPPED 
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
I/jxcore-log( 5631): ok 73 Should be able to call startBroadcasting without error
I/jxcore-log( 5631): 
D/LGWifiP2pService(  962): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: RESTARTING
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139268 arg2=20 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5631): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bl,uetoothServerThread( 5631): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): onServerStopped
I/bt-btif ( 1964): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 2 listener(s) left
I/bt-btif ( 1964): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): stop: Stopping services
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139298 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139298 arg2=21 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5631): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  962): remove client information from framework
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139268 arg2=22 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5631): ok 74 Should be able to call stopBroadcasting without error
I/jxcore-log( 5631): 
D/LGWifiP2pService(  962): P2pEnabledState{ when=-2ms what=139307 arg2=23 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5631): Service requests cleared successfully
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): load: ,
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Peer expiration time in milliseconds: 60000, ,
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1277e683 added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878504.5631
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
,D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878504.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5631): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 1964): BTA_JvCreateRecordByUser
I/bt-btif ( 1964): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878504.5631, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878504.5631","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: {"pi":"F8:95:C7:87:85:54","pn":"1455027878504.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455027878504.5631","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  962): InactiveState{ when=0 what=139292 arg2=24 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@17d68a64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=139292 arg2=24 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@17d68a64 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState add service
D/LGWifiP2pService(  962): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): start: Starting P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local service added successfully
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139265 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 5631): ok 75 Should be able to call startBroadcasting without error
I/jxcore-log( 5631): 
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139265 arg2=25 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5631): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery started successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Exiting thread
,D/LGWifiP2pService(  962): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: STARTED
I/bt-btif ( 1964): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 2 listener(s) left
I/bt-btif ( 1964): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: NOT_STARTED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): stop: Stopping services
D/LGWifiP2pService(  962): InactiveState{ when=-3ms what=139268 arg2=26 target=com.android.internal.util.StateMachine$SmHandler }
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 2809): P2P-FIND-STOPPED 
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: false
D/LGWifiP2pService(  962): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): release: 1 listener(s) left
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 1 listener(s) left
,D/LGWifiP2pService(  962): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5631): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139298 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139298 arg2=27 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  962): P2pEnabledState clear service
I/jxcore-log( 5631): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 5631): 
D/LGWifiP2pService(  962): remove client information from framework
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=139268 arg2=28 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local services cleared successfully
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Maximum number of connection attempt retries: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise mode: 1, 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c9a7039 added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=139307 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
,D/LGWifiP2pService(  962): P2pEnabledState{ when=-3ms what=139307 arg2=29 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service request
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5631): Service requests cleared successfully
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca,
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878549.5631,
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878549.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: Using peer discovery mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5631): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878549.5631, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): bind: Binding a new listener
I/bt-btif ( 1964): BTA_JvCreateRecordByUser
I/bt-btif ( 1964): BTA_JvRfcommStartServer
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878549.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: {"pi":"F8:95:C7:87:85:54","pn":"1455027878549.5631","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455027878549.5631","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139292 arg2=30 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fe2fbf92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139292 arg2=30 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fe2fbf92 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState add service
D/LGWifiP2pService(  962): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: RESTARTING
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139265 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139265 arg2=31 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 5631): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 5631): 
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  962): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5631): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 2 listener(s) left
I/bt-btif ( 1964): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: NOT_STARTED
I/bt-btif ( 1964): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): onServerStopped
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139268 arg2=32 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): P2P-FIND-STOPPED 
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): discovery change broadcast false
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139298 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 wha,t=139298 arg2=33 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  962): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5631): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139268 arg2=34 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): InactiveState{ when=-1ms what=139307 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=139307 arg2=35 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5631): Service requests cleared successfully
I/jxcore-log( 5631): ok 78 Should be able to call stopBroadcasting without error
I/jxcore-log( 5631): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): ,	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3cc867df added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca,
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca,
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878598.5631,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878598.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: OK
,I/io.jxcore.node.ConnectionHelper( 5631): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5631): getBluetoothService() called with no BluetoothManagerCallback,
I/bt-btif ( 1964): BTA_JvCreateRecordByUser
,I/bt-btif ( 1964): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878598.5631, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Waiting for incoming connections...
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878598.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: {"pi":"F8:95:C7:87:85:54","pn":"1455027878598.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455027878598.5631","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139292 arg2=36 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@bf3e2f0a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139292 arg2=36 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@bf3e2f0a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState add service
D/LGWifiP2pService(  962): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): start: Starting P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local service added successfully
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139265 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139265 arg2=37 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: RUNNING_WIFI
I/wpa_supplicant( 2809): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
,I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: OK
D/LGWifiP2pService(  962): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: STARTED
I/jxcore-log( 5631): ok 79 Should be able to call startBroadcasting without error
I/jxcore-log( 5631): 
I/io.jxcore.node.ConnectionHelper( 5631): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): onServerStopped
D/LGWifiP2pService(  962): InactiveState{ when=-4ms what=139268 arg2=38 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): P2P-FIND-STOPPED 
I/bt-btif ( 1964): BTA_JvDeleteRecord
I/bt-btif ( 1964): BTA_JvRfcommStopServer
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 2 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5631): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: NOT_STARTED
D/LGWifiP2pService(  962): InactiveState{ when=-1ms what=139298 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=139298 arg2=39 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChang,ed: NOT_STARTED
D/LGWifiP2pService(  962): remove client information from framework
D/LGWifiP2pService(  962): InactiveState{ when=-2ms what=139268 arg2=40 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
D/LGWifiP2pService(  962): InactiveState{ when=-3ms what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-3ms what=139307 arg2=41 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service request
I/jxcore-log( 5631): ok 80 Should be able to call stopBroadcasting without error
I/jxcore-log( 5631): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5631): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5631): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9a8d6f5 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(707310292)( 1964): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1d7c02ca
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5631): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878650.5631
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878650.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5631): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455027878650.5631, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): bind: Binding a new listener
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5631): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455027878650.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: {"pi":"F8:95:C7:87:85:54","pn":"1455027878650.5631","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455027878650.5631","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  962): InactiveState{ when=0 what=139292 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@99a99860 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139292 arg2=42 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@99a99860 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState add service
D/LGWifiP2pService(  962): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): start: Starting P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): start: OK
I/io.jxcore.node.ConnectionHelper( 5631): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139265 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139265 arg2=43 target=com.android.internal.util.StateMachine$SmHandler }
W/BluetoothAdapter( 5631): getBluetoothService() called with no BluetoothManagerCallback
I/wpa_supplicant( 2809): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 5631): ok 81 Should be able to call startBroadcasting without error
I/jxcore-log( 5631): 
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5631): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5631): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5631): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 2 listener(s) left
I/bt-btif ( 1964): BTA_JvCreateRecordByUser
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5631): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopForRestart
I/io.jxcore.node.ConnectionHelper( 5631): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5631): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5631): stop: Stopping services
I/bt-btif ( 1964): BTA_JvRfcommStartServer
D/LGWifiP2pService(  962): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.blue,tooth.BluetoothServerThread( 5631): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  962): InactiveState{ when=-4ms what=139268 arg2=44 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2809): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): stop: Stopping P2P device discovery...
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
D/LGWifiP2pService(  962): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): stopWifiPeerDiscovery: Stopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5631): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5631): release: 1 listener(s) left
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5631): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5631): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5631): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  962): InactiveState{ when=-1ms what=139298 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=-1ms what=139298 arg2=45 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service
I/jxcore-log( 5631): ok 82 Should be able to call stopBroadcasting without error
I/jxcore-log( 5631): 
D/LGWifiP2pService(  962): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5631): Local services cleared successfully
D/LGWifiP2pService(  962): InactiveState{ when=-3ms what=139268 arg2=46 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): InactiveState{ when=0 what=139307 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState{ when=0 what=139307 arg2=47 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  962): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5631): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5631): Service requests cleared successfully
,I/jxcore-log( 5631): # setup
I/jxcore-log( 5631): 
I/Netd    (  278): M: Get netlink event, ifname: p2p0 action: 4
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 314779818009; DSPS: 10413220; Offset : -3014782287
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 334780585293; DSPS: 11068605; Offset : -3014777865
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  962): remove 52994e
,D/LocationManagerService(  962): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  962): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  962): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  962): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  962): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  962): acquireWakeLockInternal: lock=591329745, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=962
,D/PowerManagerServiceEx(  962): releaseWakeLockInternal: lock=591329745 [*alarm*], flags=0x0
,I/ActivityManager(  962): Process com.google.android.talk (pid 7626) has died
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 354781339191; DSPS: 11723990; Offset : -3014786983
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 374782037726; DSPS: 12379373; Offset : -3014790484
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 394782769541; DSPS: 13034757; Offset : -3014790777
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 414783437815; DSPS: 13690139; Offset : -3014794359
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 434784104942; DSPS: 14345521; Offset : -3014798280
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 454784834257; DSPS: 15000904; Offset : -3014770948
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 474785476854; DSPS: 15656285; Offset : -3014769324
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  962): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 494786150023; DSPS: 16311668; Offset : -3014797669
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 514786876057; DSPS: 16967051; Offset : -3014773748
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 534787534540; DSPS: 17622433; Offset : -3014786860
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 554788295365; DSPS: 18277818; Offset : -3014788453
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 574788968431; DSPS: 18933200; Offset : -3014787321
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 594789707121; DSPS: 19588584; Offset : -3014780922
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 614790684145; DSPS: 20243976; Offset : -3014780565
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 634791412835; DSPS: 20899360; Offset : -3014784375
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  962): acquireWakeLockInternal: lock=591329745, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=962
,V/AlarmManager(  962): RTC_WAKEUP set : Alarm{1c08a7fb type 0 when 1455028033302 com.google.android.gms} when 1455028033302
I/ActivityManager(  962): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8110 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/EventLogService( 5605): Aggregate from 1455027692554 (log), 1455026233171 (data)
,I/DigitalAppWidgetProvider( 8110): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8110): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@346d9f1a
D/PowerManagerServiceEx(  962): releaseWakeLockInternal: lock=591329745 [*alarm*], flags=0x0
,I/art     (  962): Explicit concurrent mark sweep GC freed 73394(3MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.504ms total 232.714ms
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 654792144494; DSPS: 21554744; Offset : -3014786258
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 674792830528; DSPS: 22210126; Offset : -3014769632
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 694793522552; DSPS: 22865509; Offset : -3014780345
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 714794164002; DSPS: 23520890; Offset : -3014779400
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 734794885974; DSPS: 24176274; Offset : -3014790005
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 754795541174; DSPS: 24831655; Offset : -3014775571
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 774796270021; DSPS: 25487039; Offset : -3014778989
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 794797025378; DSPS: 26142424; Offset : -3014786753
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 814797677662; DSPS: 26797805; Offset : -3014775391
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 834798408383; DSPS: 27453189; Offset : -3014777065
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 854799167074; DSPS: 28108574; Offset : -3014781054
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 874799831024; DSPS: 28763956; Offset : -3014788413
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 894800764506; DSPS: 29419346; Offset : -3014770745
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 914801596999; DSPS: 30074734; Offset : -3014792770
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 934802248241; DSPS: 30730115; Offset : -3014782657
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 954802984953; DSPS: 31385499; Offset : -3014778341
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 974803736820; DSPS: 32040884; Offset : -3014788919
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  962): acquireWakeLockInternal: lock=591329745, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=962
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{38d435c4 type 2 when 990551 com.google.android.gms} when 990551
D/PowerManagerServiceEx(  962): releaseWakeLockInternal: lock=591329745 [*alarm*], flags=0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 994804402593; DSPS: 32696266; Offset : -3014794610
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1014805144200; DSPS: 33351650; Offset : -3014785790
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1034805807526; DSPS: 34007032; Offset : -3014793590
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1054806470799; DSPS: 34662413; Offset : -3014771421
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1074807220167; DSPS: 35317798; Offset : -3014784706
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1094807970471; DSPS: 35973183; Offset : -3014797341
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1114808683745; DSPS: 36628566; Offset : -3014785945
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1134809346967; DSPS: 37283948; Offset : -3014794006
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1154810332897; DSPS: 37939340; Offset : -3014784873
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1174811005807; DSPS: 38594722; Offset : -3014783584
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  962): acquireWakeLockInternal: lock=591329745, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=962
,V/AlarmManager(  962): ELAPSED_WAKEUP set : Alarm{3454ccad type 2 when 1191355 com.android.bluetooth} when 1191355
D/PowerManagerServiceEx(  962): releaseWakeLockInternal: lock=591329745 [*alarm*], flags=0x0
,W/bt-smp  ( 1964): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
,W/bt-smp  ( 1964): Plain text(LSB ~ MSB) = 39 5b 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1964): Encrypted text(LSB ~ MSB) = 33 61 53 99 1b d2 67 fd 49 07 d1 ee 48 14 30 d2 
W/bt-btm  ( 1964): Stopping oneshot timer
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1194811759861; DSPS: 39250107; Offset : -3014792209
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1214812429488; DSPS: 39905489; Offset : -3014794307
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  962): User[0] Flushing usage stats to disk
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1234813163127; DSPS: 40560873; Offset : -3014792830
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1254813971557; DSPS: 41216259; Offset : -3014777909
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/HeadsetStateMachine( 1964): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  962): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1274814642539; DSPS: 41871641; Offset : -3014778105
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 8240): 
D/AndroidRuntime( 8240): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8240): CheckJNI is OFF
D/AndroidRuntime( 8240): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  962): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  962): Killing 5631:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  962): Skipping PackageSetting{1249eafa com.example.hello/10317} due to missing metadata
I/WindowState(  962): WIN DEATH: Window{1dddef29 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  962): Focus left window: Window{1dddef29 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  962): Window went away: Window{1dddef29 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/bt-btif ( 1964): BTA_JvDeleteRecord
I/bt-btif ( 1964): BTA_JvRfcommStopServer
I/bt-btif ( 1964): BTA_JvDeleteRecord
I/bt-btif ( 1964): BTA_JvRfcommStopServer
I/ActivityManager(  962):   Force finishing activity ActivityRecord{8e056c6 u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  962): Display changed displayId=0
D/DSDPConnection( 1751): Display #0 changed.
W/ActivityManager(  962): Spurious death for ProcessRecord{19460be2 5631:com.test.thalitest/u0a316}, curProc for 5631: null
I/ActivityManager(  962): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  962):   Force finishing activity ActivityRecord{8e056c6 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  962): Duplicate finish request for ActivityRecord{8e056c6 u0 com.test.thalitest/.MainActivity t222 f}
I/art     ( 1935): Explicit concurrent mark sweep GC freed 21855(1364KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/20MB, paused 1.578ms total 73.991ms
I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1368): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3650): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
W/System.err( 3650): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3650): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3650): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3650): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3650): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3650): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3650): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3650): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3650): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3650): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3650): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
I/art     ( 5605): Explicit concurrent mark sweep GC freed 19602(1119KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 13MB/18MB, paused 816us total 94.472ms
W/SQLiteConnectionPool( 5605): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/ActivityManager(  962): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8271 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1368): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
I/Activity( 1878): Activity.onPostResume() called 
D/KeyguardModel( 1368): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1368): createShortcutInfo...
D/KeyguardModel( 1368): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1368): createShortcutInfo...
W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
W/PackageManager( 1368): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1368): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1368): createShortcutInfo...
W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1368): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1368): createShortcutInfo...
I/art     (  962): Explicit concurrent mark sweep GC freed 19809(1433KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 4.632ms total 204.225ms
I/art     (  962): WaitForGcToComplete blocked for 188.879ms for cause Explicit
W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1368): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1368): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/SystemUI[Framework](  962): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1368): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1368): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/InputDispatcher(  962): Focus entered window: Window{3066b5a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  962): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  962): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  962): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  962): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2e0affb0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  962): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  962): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  962): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  962): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  962): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  962): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2e0affb0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  962): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1368): handleShortcutListChanged...
W/ResourcesManager( 8271): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8271): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/KeyguardModel( 1368): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1368): createShortcutInfo...
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourcesManager( 8271): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1368): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1368): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1368): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1368): createShortcutInfo...
W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1368): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1368): createShortcutInfo...
W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/KeyguardModel( 1368): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1368): createShortcutInfo...
I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  962): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  962): Got RemoteException sending setActive(false) notification to pid 5631 uid 10316
D/KeyguardModel( 1368): handleShortcutListChanged...
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
D/administrator(  962): Handling package changes for user 0
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/LGEmail ( 8271): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  962): Timeline: Activity_windows_visible id: ActivityRecord{37b61563 u0 com.lge.launcher2/.Launcher t221} time:1294542
D/LGEmail ( 8271): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1610): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/art     (  962): Explicit concurrent mark sweep GC freed 3735(197KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 12.057ms total 319.875ms
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/NotificationService(  962): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  962): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  962): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1368): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1368): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
D/TaskPersister(  962): removeObsoleteFile: deleting file=222_task.xml
I/[SystemUI]NavigationThemeResource( 1368): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1368):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1368): , Keyguard show=false, IME shown=false, Panel expanded=false
D/AndroidRuntime( 8240): Shutting down VM
I/PackageChangeReceiver( 8271): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/sensors_hal_Time(  962): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  962): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  962): tsOffsetIs: Apps: 1294815393624; DSPS: 42527025; Offset : -3014761370
D/AppUp4:PreloadHelper( 7663): added Exclude : com.test.thalitest
I/ActivityManager(  962): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8299 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  962): Killing 7687:com.android.gallery3d/u0a23 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/libprocessgroup(  962): failed to open /acct/uid_10023/pid_7687/cgroup.procs: No such file or directory
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1878): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/SharedPreferencesImpl( 1878): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
I/Timeline( 1878): Timeline: Activity_idle id: android.os.BinderProxy@38422cd7 time:1295236
W/ResourcesManager(  962): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     ( 1878): Explicit concurrent mark sweep GC freed 27910(1515KB) AllocSpace objects, 20(2MB) LOS objects, 39% free, 15MB/25MB, paused 970us total 57.277ms
W/ResourcesManager( 8299): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
