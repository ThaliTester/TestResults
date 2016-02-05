#### Test 5753124374916c2_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/art     ( 1752): Explicit concurrent mark sweep GC freed 27110(1693KB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 13MB/22MB, paused 1.480ms total 100.939ms
,I/art     ( 2085): Explicit concurrent mark sweep GC freed 8934(442KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.363ms total 32.231ms
--------- beginning of system
I/ActivityManager(  843): Killing 5276:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  843): failed to open /acct/uid_10023/pid_5276/cgroup.procs: No such file or directory
I/ActivityManager(  843): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5501 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 2026): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 2026): UpdateCorporaTask done [took 172 ms] updated apps [took 172 ms] 
D/AndroidRuntime( 5497): 
D/AndroidRuntime( 5497): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5497): CheckJNI is OFF
D/Finsky  ( 5501): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/Finsky  ( 5501): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
D/AndroidRuntime( 5497): Calling main entry com.android.commands.am.Am
W/Settings( 5501): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5501): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5501): com.android.vending: cancel(-1050172287) by com.android.vending
I/ActivityManager(  843): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  843): setTaskToReturnTo : TaskRecord{152b5d60 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  843): setTaskToReturnTo : TaskRecord{152b5d60 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  843): AppWindowTokenEx init.. 
I/[LGHome]EVENT( 1951): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  843): Focus left window: Window{3962ba8c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5497): Shutting down VM
D/ContextHelper(  843): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
V/DownloadManager( 3175): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@15727002 on behalf of 5501
D/SplitWindow(  843): check instance of lgWin Window{34888eea u0 Starting com.test.thalitest}
I/ActivityManager(  843): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5562 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1951): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/NotificationManager( 5501): com.android.vending: cancel(1003285959) by com.android.vending
I/[LGHome]EVENT( 1951): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  843): Starting window displayed
I/SystemUI[Framework](  843): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  843): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  843): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  843): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  843): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1fbeaff9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  843): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1372): draw background and invalidate : color = 15000000
D/BarTransitions( 1372): draw background and invalidate : color = 18171717
I/HotwordDetector( 2026): Closing mic
D/Ads     ( 5501): Skipping gmscore version check
I/MicrophoneInputStream( 2026): mic_close com.google.android.apps.gsa.speech.audio.u@2abef622
V/AudioRecord( 2026): stop()
D/AudioRecord( 2026): AudioRecord->stop()
V/AudioFlinger(  277): RecordHandle::stop()
V/AudioFlinger(  277): RecordThread::stop
V/AudioFlinger(  277): Record stopped OK
V/AudioPolicyManager(  277): stopInput() input 16
V/AudioPolicyService(  277): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  277): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  277): AudioCommandThread() waking up
V/AudioPolicyService(  277): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  277): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  277): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  277): ThreadBase::setParameters() routing=0
V/AudioFlinger(  277): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  277): processConfigEvents_l() remaining events 1
V/AudioFlinger(  277): processConfigEvents_l() DONE thread 0xb3c48000
D/Finsky  ( 5501): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5501): [1] Libraries$2.run: Finished loading 1 libraries.
D/audio_hw_primary(  277): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
D/ChimeraCfgMgr( 2268): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2268): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 2268): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
V/audio_hw_primary(  277): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  277): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  277): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  277): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  277): disable_audio_route: exit
E/audio_hw_primary(  277): disable_snd_device: enter 144
D/hardware_info(  277): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  277): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  277): stop_input_stream: exit: status(0)
V/audio_hw_primary(  277): in_standby: exit:  status(0)
D/Finsky  ( 5501): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/AudioFlinger(  277): RecordThread: loop stopping
V/AudioPolicyService(  277): AudioCommandThread() going to sleep
V/AudioPolicyManager(  277): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  277): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  277): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  277): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  277): AudioCommandThread() waking up
V/AudioPolicyService(  277): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  277): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  277): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  277): AudioCommandThread() waking up
V/AudioPolicyService(  277): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  277): setParameters(): io 16, keyvalue hotword_active=0, calling pid 277
V/AudioFlinger(  277): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  277): sendConfigEvent_l() num events 1 event 2
V/AudioPolicyService(  277): AudioCommandThread() going to sleep
V/AudioFlinger(  277): RecordThread: loop starting
V/AudioFlinger(  277): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  277): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  277): in_set_parameters: exit: status(0)
V/AudioFlinger(  277): processConfigEvents_l() DONE thread 0xb3c48000
V/AudioFlinger(  277): RecordThread: loop stopping
V/AudioPolicyService(  277): AudioCommandThread() going to sleep
V/AudioRecord( 2026): stop()
V/AudioRecord( 2026): stop()
V/AudioRecord( 2026): stop()
V/AudioFlinger(  277): releasing 15 from 2026 for -1
V/AudioFlinger(  277): RecordHandle::stop()
V/AudioFlinger(  277): RecordThread::stop
V/AudioFlinger(  277):  decremented refcount to 0
V/AudioFlinger(  277): purging stale effects
V/AudioPolicyManager(  277): releaseInput() 16
V/AudioPolicyManager(  277): closeInput(16)
V/AudioFlinger(  277): closeInput() 16
V/AudioSystem(  277): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  277): ThreadBase::exit
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  277): RecordThread: loop starting
V/AudioSystem( 1780): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  277): RecordThread 0xb3c48000 exiting
D/audio_hw_primary(  277): adev_close_input_stream: enter:stream_handle(0xb546e240)
V/AudioSystem(  843): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  277): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  277): in_standby: exit:  status(0)
V/AudioSystem( 2062): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2026): ioConfigChanged() event 4, ioHandle 16
V/AudioPolicyService(  277): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  277): inserting command: 9 at index 0, num commands 0
V/AudioSystem( 2661): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 3152): ioConfigChanged() event 4, ioHandle 16
V/AudioPolicyManager(  277): releaseInput() exit
V/AudioPolicyService(  277): AudioCommandThread() waking up
V/AudioPolicyService(  277): AudioCommandThread() processing update audio port list
V/AudioFlinger(  277): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  277): removeClient_l() pid 2026, calling pid 277
V/AudioPolicyService(  277): AudioCommandThread() going to sleep
D/Finsky  ( 5501): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/HotwordRecognitionRnr( 2026): Stopping hotword detection.
I/HotwordRecognitionRnr( 2026): Hotword detection finished
D/Finsky  ( 5501): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/ContextHelper( 5562): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/WebViewFactory( 5562): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/charger_monitor(  458): init target 500000
I/LibraryLoader( 5562): Time to load native libraries: 3 ms (timestamps 2252-2255)
I/LibraryLoader( 5562): Expected native library version number "",actual native library version number ""
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
D/WifiController(  843): battery changed pluggedType: 2
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/MainApplication( 5354): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/charger_monitor(  458): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  843): battery changed pluggedType: 2
W/MainApplication( 5354): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
V/WebViewChromiumFactoryProvider( 5562): Binding Chromium to main looper Looper (main, tid 1) {16c383b5}
I/LibraryLoader( 5562): Expected native library version number "",actual native library version number ""
I/chromium( 5562): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5562): Initializing chromium process, singleProcess=true
W/art     ( 5562): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5562): ApplicationContext is null in ApplicationStatus
D/ChimeraCfgMgr( 2268): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2268): Module APK com.google.android.play.games already loaded
W/chromium( 5562): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5562): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5562): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5562): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5562): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5562): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5562): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5562): Remote Branch: 
I/Adreno-EGL( 5562): Local Patches: 
I/Adreno-EGL( 5562): Reconstruct Branch: 
D/ChimeraCfgMgr( 2268): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/Icing   ( 2268): Storage manager: low false usage 1.71MB avail 2.37GB capacity 4.06GB
D/AsyncTaskServiceImpl( 2268): Submit a task: k
D/ChimeraCfgMgr( 2268): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/k       ( 2268): Processing package: com.test.thalitest
D/ChimeraCfgMgr( 2268): Loading module com.google.android.gms.vision from APK com.google.android.gms
V/AudioPolicyService(  277): registerClient() client 0xb3c2e480, uid 10316
D/GassUtils( 2268): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 2268): Found info for package com.test.thalitest in db.
D/BluetoothManagerService(  843): Message: 20
D/BluetoothManagerService(  843): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@144863b5:true
D/BluetoothAdapterService(871736881)( 2062): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@eb2658f
W/BaseAppContext( 2268): Using Auth Proxy for data requests.
W/BaseAppContext( 2268): Using Auth Proxy for data requests.
,I/ActivityManager(  843): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5626 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BaseAppContext( 2268): Using Auth Proxy for data requests.
,W/BaseAppContext( 2268): Using Auth Proxy for data requests.
,W/BaseAppContext( 2268): Using Auth Proxy for data requests.
W/BaseAppContext( 2268): Using Auth Proxy for data requests.
W/BaseAppContext( 2268): Using Auth Proxy for data requests.
,W/art     ( 5562): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5562): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5562): CordovaWebView is running on device made by: LGE
,W/art     ( 5562): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5562): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5562): Activity.onPostResume() called 
,D/OpenGLRenderer( 5562): Render dirty regions requested: true
I/OpenGLRenderer( 5562): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5562): Enabling debug mode 0
D/Atlas   ( 5562): Validating map...
,D/SplitWindow(  843): check instance of lgWin Window{3766208 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5562): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  843): Focus entered window: Window{3766208 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/Icing   ( 2268): updateResources: need to parse f{com.google.android.gms}
,W/ActivityManager(  843): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/InputMethodManagerService(  843): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  843): Displayed com.test.thalitest/.MainActivity: +1s298ms
I/Timeline(  843): Timeline: Activity_windows_visible id: ActivityRecord{122a3219 u0 com.test.thalitest/.MainActivity t222} time:83086
I/Timeline( 5562): Timeline: Activity_idle id: android.os.BinderProxy@1eac0208 time:83123
,I/Gmail   ( 5626): getAccountsCursor
,W/BindingManager( 5562): Cannot call determinedVisibility() - never saw a connection for the pid: 5562
V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5626): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  843): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5626): Error finding the version of the Email provider.....
E/Gmail   ( 5626): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5626): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5626): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5626): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5626): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5626): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5626): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5626): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Gmail   ( 5626): getAccountsCursor
W/EmailMigration( 5626): We do not support migrating this version of the Email provider.
W/ActivityManager(  843): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/JsMessageQueue( 5562): Set native->JS mode to OnlineEventsBridgeMode
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  843): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5626): Observing account changes for notifications
,I/Icing   ( 2268): Internal init done: storage state 0
,I/ActivityManager(  843): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5677 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
I/ActivityManager(  843): Killing 5297:com.android.contacts/u0a18 (adj 15): empty #11
,I/Icing   ( 2268): Post-init done
,W/libprocessgroup(  843): failed to open /acct/uid_10018/pid_5297/cgroup.procs: No such file or directory
,I/Gmail   ( 5626): notifyAccountChanged
,I/Gmail   ( 5626): getAccountsCursor
V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5626): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/PhoneMonitor( 5677): Register our PhoneStateListener
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5626): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  843): Killing 5319:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/Gmail   ( 5626): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5626): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/libprocessgroup(  843): failed to open /acct/uid_10069/pid_5319/cgroup.procs: No such file or directory
,D/GCM     ( 1752): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PhoneMonitor( 5677): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 5677): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5677): [parse] Load xml
,I/CheckinService( 2268): Checkin interval check for package: unspecified last checkin: 1454681660554 min interval config: 0 actual interval: 5893
V/TelephonyAutoProfiling( 5677): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5677): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/CheckinService( 2268): Checking schedule, now: 1454681666479 next: 1454681690504
I/CheckinService( 2268): active receiver: disabled
,D/PhoneMonitor( 5677): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/GCoreFlp( 1752): No location to return for getLastLocation()
W/FusedLocationProvider( 1752): location=null
,D/jxcore_app_log( 5562): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622895104
,I/Gmail   ( 5626): getAccountsCursor
V/DownloadManager( 3175): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@23667d13 on behalf of 2268
I/ActivityManager(  843): Process com.google.android.apps.docs (pid 5371) has died
,I/chromium( 5562): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/art     ( 2085): Explicit concurrent mark sweep GC freed 3272(126KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.710ms total 49.171ms
,I/art     ( 5562): CheckpointMarkThreadRoots callback created = 0x99e3a4e0
,I/CheckinService( 2268): Done disabling old GoogleServicesFramework version
,V/DownloadManager( 3175): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@1c713b50 on behalf of 2268
V/DownloadManager( 3175): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@c28d149 on behalf of 2268
,I/art     ( 5562): CheckpointMarkThreadRoots callback created = 0x99e3a4b0
,I/ActivityManager(  843): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5713 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 330us total 22.747ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 21.253ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 21.015ms
,W/ResourcesManager( 5713): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Icing   ( 2268): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/art     (  843): Explicit concurrent mark sweep GC freed 32469(1523KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.623ms total 185.014ms
,D/Icing   ( 2268): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2268): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/Babel_SMS( 5713): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5713): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5713): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5713): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5713): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5713): MmsConfig.loadFromResources
E/Babel_SMS( 5713): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5713): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5713): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5713): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5713): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5713): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5713): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5713): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5713): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5713): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5713): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5713): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5713): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5713): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5713): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5713): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5713): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5713): found sensor: Motion Accel, handle=46
,I/ActivityManager(  843): Process com.lge.bnr (pid 5354) has died
,I/art     ( 5713): CheckpointMarkThreadRoots callback created = 0xb002d820
,W/Settings( 5713): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5713): startup - clean
I/Babel   ( 5713): deleted: false for 0
I/art     ( 5713): CheckpointMarkThreadRoots callback created = 0xb002d800
,D/InitAlarmsService( 3787): Clearing and rescheduling alarms.
,W/AudioCapabilities( 5713): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5713): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5713): Unsupported mime audio/g726
D/CalendarProvider2( 5431): Scheduling check of next Alarm
W/AudioCapabilities( 5713): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5713): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 5713): Unsupported mime video/mjpg
,W/VideoCapabilities( 5713): Unsupported mime video/theora
W/AudioCapabilities( 5713): Unsupported mime audio/evrc
W/AudioCapabilities( 5713): Unsupported mime audio/qcelp
W/VideoCapabilities( 5713): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5713): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5713): Unsupported mime audio/qcelp
W/AudioCapabilities( 5713): Unsupported mime audio/evrc
W/VideoCapabilities( 5713): Unsupported mime video/mp4v-esdp
,I/ActivityManager(  843): Process com.google.android.gms.unstable (pid 5388) has died
D/CalendarProvider2( 5431): SCHEDULE_ALARM_REMOVE
I/VideoCapabilities( 5713): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5713): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5713): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5713): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5713): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5713): onServiceConnected
W/Babel   ( 5713): Attempted to change video mute state without an active call.
,I/NotificationManager( 5713): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5713): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5713): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5713): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  843): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5747 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5086): getMode name:com.lge.qremote
,I/AudioManager( 5086): getMode name:com.lge.qremote
,I/AudioManager( 5086): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5747): Quickset Services start...
W/System  ( 5713): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5713): Installed default security provider GmsCore_OpenSSL
I/UEI.SmartControl( 5747): Manufacture = LGE
I/AudioManager( 5086): getMode name:com.lge.qremote
D/UEI.SmartControl( 5747): File observer start...
E/UEI.SmartControl( 5747): IR Port is disabled: false
,D/UEI.SmartControl( 5747): Starting file observer...
D/UEI.SmartControl( 5747): Extracting JNI libs...
D/UEI.SmartControl( 5747): --- this system supports 32-bit or 64-bit only
,D/WearableService( 1752): callingUid 10006, callindPid: 1752
D/LocationInitializer( 2268): Restart initialization of location
D/AuthorizationBluetoothService( 1752): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1752): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1752): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1752): No location to return for getLastLocation()
W/FusedLocationProvider( 1752): location=null
,I/NotificationManager( 5713): com.google.android.talk: cancel(8) by com.google.android.talk
,W/jxcore-log( 5562): Initializing JXcore engine
,W/jxcore-log( 5562): JXcore engine is ready
I/ActivityManager(  843): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5774 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/UEI.SmartControl( 5747): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5747): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5747): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5747): --- Selecting new region: 2
,I/UEI.SmartControl( 5747): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5747): Platform has CIR...
D/UEI.SmartControl( 5747): NO CIR support, need to check package...
I/UEI.SmartControl( 5747): Model: LG-D722 uses JNI
I/AppUp4:AppBoxCP( 5774): onCreate
W/AppUp4:DB( 5774):  [AppBoxDatabaseHelper] construct
,D/UEI.SmartControl( 5747): QS Service created
W/Thread-667( 5711): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[4941]" dev="sockfs" ino=4941 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-667( 5711): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-667( 5711): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6456]" dev="sockfs" ino=6456 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-667( 5711): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-667( 5711): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-667( 5711): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[27117]" dev="sockfs" ino=27117 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/AppUp4:DB( 5774):  setFingerPrint start
I/AppUp4:DB( 5774):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5774):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5774):  SDK version = 0
I/AppUp4:DB( 5774):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5774): AppBoxApplication onCreate()
E/UEI.SmartControl( 5747): QS start get config
W/jxcore-log( 5562): Starting JXcore engine
,I/AppUp4:CustModeStarterReceiver( 5774): onReceive
I/AppUp4:CustModeStarterReceiver( 5774): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5774): Context : android.app.ReceiverRestrictedContext@3ff0969f
D/AppUp4:CustFacade( 5774): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5774): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5774): begin check event
I/AppUp4:CustModeStarterReceiver( 5774): Event For Nothing, skip.
D/UEI.SmartControl( 5747): Loading JNI Libs...
,D/UEI.SmartControl( 5747):  configuring local db...
,I/ActivityManager(  843): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5793 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
W/jxcore-log( 5562): Platform android
W/jxcore-log( 5562): 
W/jxcore-log( 5562): Process ARCH arm
W/jxcore-log( 5562): 
,I/ActivityManager(  843): Process com.google.android.apps.plus (pid 5455) has died
,W/ResourcesManager( 5793): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5793): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5793): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/CalendarProvider2( 5431): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5431): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/UEI.SmartControl( 5747):  ---- Has DB8: true
,D/UEI.SmartControl( 5747): QS start statue = true Error code = 0
D/UEI.SmartControl( 5747): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5747): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5747): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5747): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5747): IrrcClient ++ 
D/irrcClient( 5747): getIrrcService ++ 
D/irrcClient( 5747): getIrrcService -- 
D/irrcClient( 5747): IrrcClient -- 
W/irrc_jni( 5747): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 5747): Services init done
D/UEI.SmartControl( 5747): QS Service init finished
D/UEI.SmartControl( 5747): QS Service version name: 0.1.73
D/UEI.SmartControl( 5747): QS Service version code: 1073
,D/UEI.SmartControl( 5747): Service requested: Control
I/UEI.SmartControl( 5747): Device manager: loading config....
D/UEI.SmartControl( 5747): Config is loaded...
D/UEI.SmartControl( 5747):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5747): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5747): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5747): Internal service binding...
D/UEI.SmartControl( 5747): -----IControl: 11
D/UEI.SmartControl( 5747): Caller: com.lge.qremote
D/UEI.SmartControl( 5747): ------------ IControl registerCallback...
I/UEI.SmartControl( 5747): Registering callback...
,D/UEI.SmartControl( 5747): -----IControl: 19
D/UEI.SmartControl( 5747): Caller: com.lge.qremote
I/UEI.SmartControl( 5747): Registering Services Ready callback...
I/UEI.SmartControl( 5747): Notify client services are ready...
D/UEI.SmartControl( 5747): -----IControl: 8
D/UEI.SmartControl( 5747): Caller: com.lge.qremote
I/AppConfig( 5793): Total System Memory = 906309632
,I/GalleryUtils( 5793): Application Heap = 96 MB
I/AppConfig( 5793): App Tier : NOT_DEF
D/SystemHelper( 5793): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  843): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5815 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  843): Killing 3787:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  843): failed to open /acct/uid_10013/pid_3787/cgroup.procs: No such file or directory
,W/ResourcesManager( 5815): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5815): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5815): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 5815): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5815): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/AlarmManager(  843): RTC_WAKEUP set : Alarm{241a1127 type 0 when 1454681669336 com.google.android.googlequicksearchbox} when 1454681669336
,I/jxcore-log( 5562): JXcore Cordova bridge is ready!
I/jxcore-log( 5562): 
,W/jxcore-log( 5562): JXcore engine is started
I/SystemConfig( 5815): BUILD Country: EU
I/SystemConfig( 5815): BUILD Operator: OPEN
,I/ActivityManager(  843): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5838 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  843): Killing 5337:com.lge.eula/1000 (adj 15): empty #11
I/jxcore-log( 5562): Toggling radios to true
I/jxcore-log( 5562): 
,D/BluetoothAdapter( 5562): enable(): BT is already enabled..!
W/libprocessgroup(  843): failed to open /acct/uid_1000/pid_5337/cgroup.procs: No such file or directory
,I/SystemConfig( 5815): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5815): existFile = false
I/SystemConfig( 5815): canReadFile = false
I/SystemConfig( 5815): systemFeature RCS result false
D/SystemConfig( 5815): refreshRcsSupport() :false
,D/WifiServiceImplEx(  843): setWifiEnabled: true pid=5562, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  843): setWifiEnabled: true pid=5562, uid=10316
,D/WifiServiceImplEx(  843): disconnect pid=5562, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  843): reconnect pid=5562, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5562): Radios toggled
I/jxcore-log( 5562): 
,I/jxcore-log( 5562): My device name is: LGE-LG-D722
I/jxcore-log( 5562): 
I/wpa_supplicant( 2707): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 2707): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  843): WifiStateMachine: Leaving Connected state
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
D/WfdsMonitor( 1875): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,E/WifiConfigStore(  843): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/LockScreenSettings( 5838): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LGWifiP2pService(  843): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  843): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  843): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  273): Clearing all IP addresses on wlan0
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1752): Read error: ssl=0xaaee2400: I/O error during system call, Connection timed out
,V/NativeCrypto( 1752): SSL shutdown failed: ssl=0xaaee2400: I/O error during system call, Broken pipe
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 7
D/ConnectivityService(  843): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,D/ConnectivityService(  843): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/ConnectivityService(  843): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
D/WifiHS20(  843): hidePasspointNotification off =false
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): ValidatedState{ when=-3ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): DefaultState{ when=-8ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): Forcing reevaluation
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:29.833 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,E/WifiStateMachine(  843): Start Disconnecting Watchdog 1
D/WifiHS20(  843): hidePasspointNotification off =false
I/wpa_supplicant( 2707): wlan0: CTRL-EVENT-SCAN-STARTED 
D/WifiServiceExtension( 1875): isInternetCheckAvailable return false
,I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:29.864 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LGWifiP2pService(  843): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  843): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LockScreenSettings( 5838): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 5838): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5838): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5838): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5838): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/CommandListener(  273): Clearing all IP addresses on wlan0
,D/ConnectivityService(  843): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  843): disableDataServiceNotify
D/DSQN    (  843): stop dsqn bin
I/ActivityManager(  843): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5878 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  843): Killing 5501:com.android.vending/u0a36 (adj 15): empty #11
D/ConnectivityService(  843): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  843):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  843):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  843): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  843):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  843): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  843): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): Disconnected - quitting
D/CSLegacyTypeTracker(  843): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  843): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  843): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524292
,D/DhcpStateMachine(  843): StoppedState
D/DhcpStateMachine(  843): StoppedState{ when=-119ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 2268): CM callback handler got msg 524292
D/WifiHS20(  843): hidePasspointNotification off =false
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:30.015 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/libprocessgroup(  843): failed to open /acct/uid_10036/pid_5501/cgroup.procs: No such file or directory
,W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiServiceExtension( 1875): isInternetCheckAvailable return false
D/WifiNetworkAgent(  843): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/Tethering(  843): MasterInitialState.processMessage what=3
D/ConnectivityService(  843): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/QCNEJ   ( 1913): |CORE| No family connected
V/NetworkPolicy(  843): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  843): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  843): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  843): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  843): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  843): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  843): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1913): |CORE| No family connected
,I/QCNEJ   ( 1913): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  843): Removing idletimer
D/TelephonyNetworkFactory-1( 1780): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1780):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/Settings(  843): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1913): |CORE| sendDefaultNwMsg: default = -1
E/ConnectivityService(  843): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:30.047 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiHS20(  843): hidePasspointNotification off =false
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [SCANNING]
,I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:30.054 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  843): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  843): setSupplicantStateDISCONNECTED
D/WIFI    (  843): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
D/WIFI    (  843):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
D/WifiServerServiceExt(  843): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  843): setSupplicantStateSCANNING
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
W/ResourcesManager( 5878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 2026): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  843): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5903 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  843): Killing 5626:com.google.android.gm/u0a53 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 2026): UpdateCorporaTask done [took 112 ms] updated apps [took 112 ms] 
,W/libprocessgroup(  843): failed to open /acct/uid_10053/pid_5626/cgroup.procs: No such file or directory
,I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1913): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1951): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/InputReader(  843): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]LGPlusHomeDBManager( 1951): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1951): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1951): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  843): Handling package changes for user 0
,I/ActivityManager(  843): Process com.lge.qremote (pid 5086) has died
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2707): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/NotificationService(  843): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  843): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  843): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  843): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  843): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:31.034 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
V/BackupManagerService(  843): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@75a118
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:31.046 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/LocSvc_java(  843): onReceive
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  843): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  843): setSupplicantStateASSOCIATING
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2707): wlan0: Associated with c0:ff:d4:d3:aa:48
W/ResourcesManager(  843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/WifiServerServiceExt(  843): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  843): setSupplicantStateASSOCIATED
I/wpa_supplicant( 2707): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2707): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/ActivityManager(  843): Process com.android.providers.calendar (pid 5431) has died
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:31.132 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/LCardEmulationManager( 1852): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1852): getDefaultRoute
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
,I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/WifiServiceExtension(  843): setVHTCapabilityType  : false
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:31.138 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/WifiServerServiceExt(  843): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  843): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  843): setSecurityType  : 2
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:31.177 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:31.178 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/ConnectivityService(  843): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transpo,rts: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  843): Got NetworkAgent Messenger
D/ConnectivityService(  843): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  843): NetworkAgent connected
D/WifiServiceExtension( 1875): isInternetCheckAvailable return false
E/WifiConfigStore(  843): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Finsky  ( 5903): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/WifiConfigStore(  843): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  273): Setting iface cfg
E/WifiStateMachine(  843): Start Dhcp Watchdog 2
D/DhcpStateMachine(  843): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  843): WaitBeforeStartState
D/WifiServerServiceExt(  843): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  843): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  843): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  843): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  843): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
W/ResourceType(  843): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1951): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,E/WifiStateMachine(  843): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  843): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  843): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2422c29c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  843): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2422c29c target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  843): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  843): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  843): DHCP Start wake lock is acquired.
D/CommandListener(  273): Setting iface cfg
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  273): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  843): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  843): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  843): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  843): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  843): setSupplicantStateCOMPLETED
D/ConnectivityService(  843): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LGWifiP2pService(  843): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  843): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/GCoreNlp( 1752): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
E/WifiStateMachine(  843): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  843): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService(  843): ignoring duplicate network state non-change
D/WifiServiceExtension( 1875): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:31.375 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/ConnectivityService(  843): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService(  843): Adding iface wlan0 to network 101
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1875): isInternetCheckAvailable return false
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:31.387 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
E/WifiStateMachine(  843): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
D/WifiHS20(  843): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  843): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService(  843): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  843): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:31.418 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  843): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1913): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  273): netlink response contains error (File exists)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  843): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/ConnectivityService(  843): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  843): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  843): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState,: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:31.423 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1913): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
D/Nat464Xlat(  843): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  843): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  843): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  843): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): Connected
D/ConnectivityService(  843):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  843):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  843):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  843):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  843):     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
D/ConnectivityService(  843):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  843):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  843): currentScore = 0, newScore = 20
D/ConnectivityService(  843):    accepting network in place of null
D/ConnectivityService(  843): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1780): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  843): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  843):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
D/TelephonyNetworkFactory-1( 1780):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): [LWD] wait 500ms before dns check
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
E/ConnectivityService(  843): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  843): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  843): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  843): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  843): [e] list.add(nai) empty : false size: 1
D/Tethering(  843): MasterInitialState.processMessage what=3
D/ConnectivityService(  843): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1913): |CORE| No family connected
I/QCNEJ   ( 1913): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1913): |CORE| sendDefaultNwMsg: default = 1
,D/ConnectivityService(  843): validation of new default Network = false
D/ConnectivityService(  843): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  843): enableDataServiceNotify 
D/DSQN    (  843): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  843): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  843):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  843):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  843): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  843):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  843): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 2268): CM callback handler got msg 524290
D/LocationProviderProxy(  843): applying state to connected service
V/NetworkPolicy(  843): [LG_RESTRICTED] checkMobilePolicy_type()
I/DSQN    ( 5936): DSQN samuel.seo ver 141203
E/DSQN    ( 5936): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5936): created command queue thread
I/DSQN    ( 5936): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5936): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/CheckinService( 2268): Checkin interval check for package: unspecified last checkin: 1454681660554 min interval config: 0 actual interval: 10923
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/CheckinService( 2268): Checking schedule, now: 1454681671521 next: 1454681690504
I/CheckinService( 2268): active receiver: disabled
,D/DhcpStateMachine(  843): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  843): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  843): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/Finsky  ( 5903): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/dhcpcd  ( 5948): version 5.5.6 starting
E/dhcpcd  ( 5948): get_duid: Read-only file system
,W/Settings( 5903): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5903): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5903): com.android.vending: cancel(-1050172287) by com.android.vending
,I/dhcpcd  ( 5948): wlan0: rebinding lease of 192.168.1.134
,V/DownloadManager( 3175): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@49b8a4e on behalf of 5903
D/Ads     ( 5903): Skipping gmscore version check
D/Finsky  ( 5903): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5903): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 5903): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 2268): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5903): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  843): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5961 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/PackageBroadcastService( 2268): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2268): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 5961): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/dhcpcd  ( 5948): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,D/BluetoothManagerService(  843): Message: 20
D/BluetoothManagerService(  843): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f4d8c16:true
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): [LWD] DNSResolver start dns
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/dhcpcd  ( 5948): wlan0: leased 192.168.1.134 for 86400 seconds
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/BluetoothAdapterService(871736881)( 2062): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@eb2658f
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/BluetoothAdapterService(871736881)( 2062): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@eb2658f
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out(  843): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 5936): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5936): restart monitoring
,D/LGDataListener(  273): argv[0]=dsqncommand
D/LGDataListener(  273): argv[1]=wlan0
D/LGDataListener(  273): argv[2]=1
D/LGDataListener(  273): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5936): dsqn report finish
D/DSQN    (  843): DSQM DsqnNotification wlan0  1
D/DSQN    (  843): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Feb 2016 14:14:32 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454681672019], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454681672003]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1875): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  843): Validated
D/ConnectivityService(  843): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  843): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  843):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  843):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  843):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  843):   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  843):     satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:false
D/ConnectivityService(  843): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  843): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  843):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  843):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiDataContinuityService(  843): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
,D/ConnectivityService(  843): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  843):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  843): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiServerServiceExt(  843): set CMD_CAPTIVE_CHECK_COMPLETED
D/ConnectivityManager.CallbackHandler( 2268): CM callback handler got msg 524290
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
D/ConnectivityService(  843): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  843): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  843): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  843):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1780): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1780):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
V/LGMDMManager( 5961): Create singleton instance
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/AudioManager( 5961): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5747): -----IControl: 11
,D/UEI.SmartControl( 5747): Caller: com.lge.qremote
D/UEI.SmartControl( 5747): ------------ IControl registerCallback...
I/UEI.SmartControl( 5747): Registering callback...
D/UEI.SmartControl( 5747): -----IControl: 19
D/UEI.SmartControl( 5747): Caller: com.lge.qremote
I/UEI.SmartControl( 5747): Registering Services Ready callback...
I/UEI.SmartControl( 5747): Notify client services are ready...
I/AudioManager( 5961): getMode name:com.lge.qremote
D/UEI.SmartControl( 5747): -----IControl: 8
,D/UEI.SmartControl( 5747): Caller: com.lge.qremote
I/ActivityManager(  843): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6007 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  843): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  843): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  843): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  843): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  843): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  843): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  843): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  843): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  843): RunningState
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  843): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  843): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  843): identical MTU - not setting
D/Nat464Xlat(  843): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  843): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  843):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  843):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  843): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  843):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524295
D/ConnectivityService(  843): sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  843): Wi-Fi IP changed. Lp difference / No Route difference
D/ConnectivityManager.CallbackHandler( 2268): CM callback handler got msg 524295
D/DSQN    (  843): enableDataServiceNotify 
D/DSQN    (  843): start dsqn bin
I/QCNEJ   ( 1913): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:32.559 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  843): dsqn is running restart
,I/DSQN    ( 6024): DSQN samuel.seo ver 141203
,E/DSQN    ( 6024): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6024): created command queue thread
I/DSQN    ( 6024): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6024): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/art     (  843): Explicit concurrent mark sweep GC freed 75300(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.934ms total 239.740ms
,I/ActivityManager(  843): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6036 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
V/AlarmManager(  843): ELAPSED_WAKEUP set : Alarm{3aaf6aab type 2 when 90483 com.android.providers.calendar} when 90483
,I/Icing   ( 2268): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  843): Killing 5677:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/Icing   ( 2268): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/ConnectivityService(  843): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  843): failed to open /acct/uid_10038/pid_5677/cgroup.procs: No such file or directory
,D/ConnectivityService(  843): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  843): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  843): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
E/UpdateRequestReceiver( 6036): Received malformed URL while handling Gservices.CHANGED_ACTION
D/LocSvc_java(  843): onReceive
D/LocSvc_java(  843): got connectivity action
,D/LocSvc_java(  843): broadcast - no network connections
D/LocSvc_java(  843): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  843): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  843): onReceive
D/LocSvc_java(  843): got connectivity action
D/LocSvc_java(  843): broadcast - no network connections
D/LocSvc_java(  843): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  843): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  843): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  843): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  843): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  843): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  843): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  843): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  843): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  843): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/UpdateRequestReceiver( 6036): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6036): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6036): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  843): Killing 5774:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  843): failed to open /acct/uid_10011/pid_5774/cgroup.procs: No such file or directory
,I/CheckinService( 2268): Checkin interval check for package: unspecified last checkin: 1454681660554 min interval config: 0 actual interval: 12774
I/GservicesUpdateTask( 2026): Updating Gservices keys
,I/CheckinService( 2268): Checking schedule, now: 1454681673335 next: 1454681690504
I/CheckinService( 2268): active receiver: disabled
I/SystemUpdateService( 2268): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 2268): onCreate
D/SystemUpdateService( 2268): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 2268): cancelUpdate (empty URL)
I/SystemUpdateService( 2268): active receiver: disabled
I/NotificationManager( 2268): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 2268): com.google.android.gms: cancel(2130838166) by com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,I/art     ( 2085): Explicit concurrent mark sweep GC freed 4032(173KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 421us total 27.279ms
,I/art     ( 2268): Explicit concurrent mark sweep GC freed 39973(2MB) AllocSpace objects, 12(192KB) LOS objects, 24% free, 15MB/20MB, paused 1.111ms total 104.743ms
,W/SQLiteConnectionPool( 2268): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager(  843): Killing 5713:com.google.android.talk/u0a61 (adj 15): empty #11
,D/SystemUpdateService( 2268): onDestroy
W/libprocessgroup(  843): failed to open /acct/uid_10061/pid_5713/cgroup.procs: No such file or directory
,E/DynamiteModule( 2268): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 2268): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 2268): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 2268): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 2268): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 2268): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 2268): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 2268): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 2268): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 2268): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 2268): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 2268): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 2268): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 2268): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 2268): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 2268): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 2268): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 2268): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 2268): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 2268): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 2268): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 2268): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 2268): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 2268): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 2268): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 2268): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 2268): 		... 17 more
E/DynamiteModule( 2268): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 2268): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 2268): Selected local version of com.google.android.gms.flags
D/UEI.SmartControl( 5747): Internal timer expired: 1
,D/SystemEventReceiver( 2268): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 2268): Updating ocr activity enabled=false
,I/art     ( 2085): Explicit concurrent mark sweep GC freed 2656(103KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 412us total 27.082ms
,I/QCNEJ   ( 1913): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1913): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-05 15:14:34.262 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
W/ActivityManager(  843): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 2268): Updating downloaded model state (gservices changed)
,V/WifiInternetCheck(  843): Single check msg out of sync, ignoring.
,I/art     ( 1752): Explicit concurrent mark sweep GC freed 19304(1130KB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 13MB/22MB, paused 2.581ms total 93.612ms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  843): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  843): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  843): onReceive
D/LocSvc_java(  843): got connectivity action
D/LocSvc_java(  843): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  843): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  843): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  843): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  843): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  843): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NotificationManager(  843): android: cancelAsUser(-591465577) by android
,D/GCM     ( 1752): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
I/ActivityManager(  843): Killing 5793:com.android.gallery3d/u0a23 (adj 15): empty #11
D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
,I/System.out( 1752): propertyValue:false
I/DSQN    ( 6024): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6024): restart monitoring
I/DSQN    ( 6024): dsqn report finish
D/LGDataListener(  273): argv[0]=dsqncommand
D/LGDataListener(  273): argv[1]=wlan0
D/LGDataListener(  273): argv[2]=1
D/LGDataListener(  273): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  843): DSQM DsqnNotification wlan0  1
D/DSQN    (  843): start to monitor internet connection
,W/libprocessgroup(  843): failed to open /acct/uid_10023/pid_5793/cgroup.procs: No such file or directory
,D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 2085): Explicit concurrent mark sweep GC freed 2741(108KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 738us total 25.313ms
,I/GCoreUlr( 1752): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1752): DispatchingService.onCreate()
I/ActivityManager(  843): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6104 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  304): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 22.676ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 545us total 25.212ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 23.733ms
,W/GeofencerStateMachine( 1752): Ignoring removeGeofence because network location is disabled.
,I/GCoreUlr( 1752): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
E/ctxmgr  ( 1752): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,D/PhoneMonitor( 6104): Register our PhoneStateListener
,I/GCoreUlr( 1752): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,V/SetupWizard( 6104): Connected to Gservices successfully
,D/PhoneMonitor( 6104): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6104): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6104): [parse] Load xml
V/TelephonyAutoProfiling( 6104): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6104): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6104): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/art     ( 1752): Explicit concurrent mark sweep GC freed 18819(1348KB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 14MB/23MB, paused 2.364ms total 117.439ms
,I/GCoreUlr( 1752): Unbound from all location providers
,I/GCoreUlr( 1752): Place inference reporting - stopped
,W/ctxmgr  ( 1752): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
D/GCM     ( 1752): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/ctxmgr  ( 1752): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
I/GCoreUlr( 1752): DispatchingService.onDestroy()
I/GCoreUlr( 1752): Stopping handler for UlrDispSvcFast
I/ActivityManager(  843): Killing 5815:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  843): failed to open /acct/uid_10018/pid_5815/cgroup.procs: No such file or directory
,I/GCoreUlr( 1752): Unbound from all location providers
I/GCoreUlr( 1752): Place inference reporting - stopped
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/WearableService( 1752): callingUid 10006, callindPid: 1752
D/AuthorizationBluetoothService( 1752): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1752): [127] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 2268): Restart initialization of location
V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1752): com.google.android.gms: cancel(0) by com.google.android.gms
,D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out(  843): propertyValue:false
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out(  843): propertyValue:false
V/WifiInternetCheck(  843): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager(  843): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6134 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1752): No location to return for getLastLocation()
,W/FusedLocationProvider( 1752): location=null
,V/AlarmManager(  843): RTC_WAKEUP set : Alarm{a0684f type 0 when 1454681675923 com.android.vending} when 1454681675923
,D/Finsky  ( 5903): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/NotificationManager(  843): android: cancelAsUser(2) by android
,I/art     (  843): Explicit concurrent mark sweep GC freed 46140(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 1.973ms total 145.474ms
,W/ActivityManager(  843): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6134): getAccountsCursor
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 5903): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5903): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5903): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5903): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
,W/GAV2    ( 6134): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  843): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 5903): propertyValue:false
D/libc-netbsd( 5903): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5903): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Gmail   ( 6134): Error finding the version of the Email provider.....
E/Gmail   ( 6134): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6134): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6134): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6134): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6134): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6134): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6134): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6134): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6134): We do not support migrating this version of the Email provider.
I/Gmail   ( 6134): getAccountsCursor
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1752): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ActivityManager(  843): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 6134): Observing account changes for notifications
,W/ActivityManager(  843): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  843): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6183 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Gmail   ( 6134): notifyAccountChanged
,I/Gmail   ( 6134): getAccountsCursor
I/Gmail   ( 6134): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/libc-netbsd( 5903): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5903): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6134): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6134): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6134): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ResourcesManager( 6183): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/CalendarApplication( 6183): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6183): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6183): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3b8e083e, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3ff0969f, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@254ec3ec, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@16c383b5, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@165e6a4a, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@9d1fdbb, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@235a32d8, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@33f5a631, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@3320e116, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3698ba97, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2faba484, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1a4d746d, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@5c1f8a2, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3ca46933, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3a8084f0, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@12d9ea69, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@226afcee, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@eb2658f, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3881001c, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@e9dc425, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@248df9fa, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@23f9cbab, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1eac0208, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@120b7da1, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3ab1bbc6, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@26077787, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@310336b4, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@1c4152dd, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@22fdce52, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@205a0523, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@ff70a20, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@6053fd9, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@24867d9e, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@dbdd07f, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3092a84c, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@14810095, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1158d5aa, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1f68f59b, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2b67fd38, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3bbe1111, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1d46a276, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@19d75
D/GeneralP,referenceUtils( 6183): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6183): [init]
,I/Config  ( 6183): LGCalendar ver.4.40.17
I/Config  ( 6183): start check model
I/Config  ( 6183): start check native_ca
I/Config  ( 6183): Config Operator=OPEN, Country=EU
D/Config  ( 6183): [setDefaultValuesToPref]
D/Config  ( 6183): [parseProfiles]
D/ProfilesParser( 6183): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6183): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6183): [updateProfiletoCountryInfo]
D/GeneralPreference( 6183): [checkAndMigrateOldPreference]
D/AlertReceiver( 6183): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6183): Start InitializeAlertRingtoneService.onHandleIntent
I/Gmail   ( 6134): getAccountsCursor
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AlertUtils( 6183): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6183): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6183): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6183): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6183): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6183): End InitializeAlertRingtoneService.onHandleIntent
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  843): android: cancelAsUser(2) by android
,I/qtaguid ( 5903): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5903): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5903): untagSocket(41) failed with errno -22
,W/HolidayIntentService( 6183): onHandleIntent
D/HolidayDataLoader( 6183): readJsonAsset : holiday.json
D/Finsky  ( 5903): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/AlertService( 6183): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6183): [updateWidgets] 
D/MonthWidgetProvider( 6183): [onReceive]
D/CalendarWidgetProvider( 6183): [onReceive]
D/CalendarWidgetProvider( 6183): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,D/CalendarTypeController( 6183): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6183): [onReceive]
D/CalendarWidgetProvider( 6183): [onReceive]
D/CalendarWidgetProvider( 6183): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6183): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5961): getMode name:com.lge.qremote
,E/HolidayIntentService( 6183): onHandleIntent:holiday data empty
I/ActivityManager(  843): Process com.google.android.apps.plus (pid 5878) has died
,I/ActivityManager(  843): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6213 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  843): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6219 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/NotificationManager(  843): android: cancelAsUser(2) by android
,W/ResourcesManager( 6213): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6213): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6219): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6219): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6219): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6219): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6219): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/MultiDex( 6213): VM with version 2.1.0 has multidex support
I/MultiDex( 6213): install
I/MultiDex( 6213): VM has multidex support, MultiDex support library is disabled.
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 95225925906; DSPS: 3219052; Offset : -3021271448
,I/qtaguid ( 5903): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5903): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5903): untagSocket(41) failed with errno -22
,I/ActivityManager(  843): Process com.lge.lockscreensettings (pid 5838) has died
I/IndexDatabaseHelper( 6219): Using schema version: 115
I/IndexDatabaseHelper( 6219): Index is fine
V/JNIHelp ( 6213): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6213): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6213): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@20b1d76f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6213): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6213): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6213): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6213): Reading stored module config
,D/ChimeraCfgMgr( 6213): Loading module com.google.android.gms.car from APK com.google.android.gms
,V/WiFiOffLoadBroadcast( 6219): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6219): MCCMNC not supported: null
D/NativeLibraryUtils( 6213): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  843): Process com.google.android.partnersetup (pid 6007) has died
,I/BackgroundMemoryTrimmer( 2026): Trimming objects from memory, since app is in the background.
D/UEI.SmartControl( 5747): Service.onTrimMemory: 80
E/UEI.SmartControl( 5747): Setup service releasing memory...
,I/PhoneApp( 1780): onTrimMemory: 10
I/PhoneApp( 1780): trim memory
D/CAR.SERVICE( 6213): Connecting to CarCallService...
,I/art     ( 5747): Explicit concurrent mark sweep GC freed 158(17KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/9MB, paused 340us total 31.198ms
I/art     ( 6213): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6213): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5903): CheckpointMarkThreadRoots callback created = 0xb017c300
I/ActivityManager(  843): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6265 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     ( 5903): CheckpointMarkThreadRoots callback created = 0xb017c2c0
,D/CAR.SERVICE( 6213): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6213): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6213): Creating a new PhoneAdapter instance
W/ActivityManager(  843): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6213): setListener: com.google.android.gms.car.dn@52c710a
,W/ActivityManager(  843): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6213): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6213): Starting CarCallService with initial phone null
I/NotificationManager( 6213): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/PCSuite ( 6265): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6265): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6265): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/CAR.SERVICE( 6213): Package validated; name: com.android.vending
,V/WiFiOffLoadBroadcast( 6219): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6219): MCCMNC not supported: null
I/PCSuite ( 6265): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6265): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6265): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/NotificationManager( 5903): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5903): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/ActivityManager(  843): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6291 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6291): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  843): Process com.google.android.gm (pid 6134) has died
,I/jxcore-log( 5562): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5562): 
I/art     (  843): Explicit concurrent mark sweep GC freed 13411(675KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.100ms total 157.782ms
,I/ActivityManager(  843): Process com.google.android.configupdater (pid 6036) has died
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  843): android: cancelAsUser(2) by android
,I/Babel_SMS( 6291): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6291): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6291): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6291): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6291): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6291): MmsConfig.loadFromResources
E/Babel_SMS( 6291): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6291): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/qtaguid ( 5903): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5903): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5903): untagSocket(41) failed with errno -22
,I/ActivityManager(  843): Process com.android.settings (pid 6219) has died
,I/BackgroundMemoryTrimmer( 2026): Trimming objects from memory, since app is in the background.
D/UEI.SmartControl( 5747): Service.onTrimMemory: 60
E/UEI.SmartControl( 5747): Setup service releasing memory...
I/PhoneApp( 1780): onTrimMemory: 10
I/PhoneApp( 1780): trim memory
W/art     ( 6291): Suspending all threads took: 7.449ms
,D/SensorManager( 6291): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6291): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6291): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6291): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6291): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6291): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6291): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6291): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6291): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6291): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6291): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6291): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6291): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6291): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6291): found sensor: LGE Relative Motion Detector Sensor, handle=34
,D/SensorManager( 6291): found sensor: Motion Accel, handle=46
I/art     ( 6291): CheckpointMarkThreadRoots callback created = 0xb002d820
W/Settings( 6291): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6291): startup - clean
I/art     ( 6291): CheckpointMarkThreadRoots callback created = 0xb002d800
I/Babel   ( 6291): deleted: false for 0
,W/ResourcesManager( 5903): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5903): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  843): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6328 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
W/ResourcesManager( 5903): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/AudioCapabilities( 6291): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6291): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6291): Unsupported mime audio/g726
W/AudioCapabilities( 6291): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6291): Unsupported mime audio/wma-voice
W/ResourcesManager( 6328): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6328): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/VideoCapabilities( 6291): Unsupported mime video/mjpg
W/ResourcesManager( 6328): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
V/AlarmManager(  843): RTC_WAKEUP set : Alarm{53a25da type 0 when 1454681679478 com.google.android.googlequicksearchbox} when 1454681679478
,W/ResourcesManager( 6328): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6328): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/VideoCapabilities( 6291): Unsupported mime video/theora
D/Finsky  ( 5903): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  843): RTC_WAKEUP set : Alarm{1724c5a6 type 0 when 1454681679529 com.android.vending} when 1454681679529
,W/AudioCapabilities( 6291): Unsupported mime audio/evrc
W/AudioCapabilities( 6291): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6291): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6291): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6291): Unsupported mime audio/qcelp
W/AudioCapabilities( 6291): Unsupported mime audio/evrc
,W/VideoCapabilities( 6291): Unsupported mime video/mp4v-esdp
I/IndexDatabaseHelper( 6328): Using schema version: 115
I/IndexDatabaseHelper( 6328): Index is fine
,I/VideoCapabilities( 6291): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6291): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6291): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6291): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6291): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  843): Process com.google.android.setupwizard (pid 6104) has died
,I/BackgroundMemoryTrimmer( 2026): Trimming objects from memory, since app is in the background.
I/vclib   ( 6291): onServiceConnected
W/Babel   ( 6291): Attempted to change video mute state without an active call.
,I/NotificationManager( 6291): com.google.android.talk: cancel(10436) by com.google.android.talk
E/lowmemorykiller(  242): Error writing /proc/5961/oom_score_adj; errno=22
D/DeviceConnectionService( 1752): client connected with version: 8296000
,V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
I/ActivityManager(  843): Process com.lge.qremote (pid 5961) has died
,D/UEI.SmartControl( 5747): Service.onUnbind: IControl
D/UEI.SmartControl( 5747): Service.onDestroy
I/PhoneApp( 1780): onTrimMemory: 15
I/PhoneApp( 1780): trim memory
,D/UEI.SmartControl( 5747): Shutdown IRRCPlayer... 
,I/PCSuite ( 6265): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6265): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6265): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/Finsky  ( 5903): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5903): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
W/irrc_jni( 5747): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5747): ~IrrcClient ++ 
D/irrcClient( 5747): ~IrrcClient -- 
W/irrc_jni( 5747): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5747): Blaster closed
D/UEI.SmartControl( 5747): Blaster closed
D/UEI.SmartControl( 5747): Shut down QS...
D/UEI.SmartControl( 5747): Stopped file observer...
I/UEI.SmartControl( 5747): QS lib stop result = true
D/UEI.SmartControl( 5747): QS shutdown complete
I/ActivityManager(  843): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6353 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/jxcore-log( 5562): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5562): 
,W/ResourcesManager( 6353): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  843): Message: 20
D/BluetoothManagerService(  843): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c43312c:true
,D/BluetoothAdapterService(871736881)( 2062): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@eb2658f
D/BluetoothAdapterService(871736881)( 2062): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@eb2658f
V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
I/PCSuite ( 6265): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6265): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6265): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
I/jxcore-log( 5562): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5562): 
,I/jxcore-log( 5562): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5562): 
,I/jxcore-log( 5562): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5562): 
,I/ActivityManager(  843): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6375 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/NotificationManager( 6291): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6291): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6291): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6291): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 6375): onCreate
,W/AppUp4:DB( 6375):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6375):  setFingerPrint start
I/AppUp4:DB( 6375):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,W/System  ( 6291): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6291): Installed default security provider GmsCore_OpenSSL
I/AppUp4:DB( 6375):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6375):  SDK version = 0
I/AppUp4:DB( 6375):  beforefinger == newfinger no write in DB
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  843): Process com.uei.lg.quicksetsdk.lite (pid 5747) has died
,I/BackgroundMemoryTrimmer( 2026): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1780): onTrimMemory: 10
I/PhoneApp( 1780): trim memory
D/AppUp4:AppBoxApplication( 6375): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6375): onReceive
I/AppUp4:CustModeStarterReceiver( 6375): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6375): Context : android.app.ReceiverRestrictedContext@3ff0969f
D/AppUp4:CustFacade( 6375): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6375): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6375): begin check event
I/AppUp4:CustModeStarterReceiver( 6375): Event For Nothing, skip.
,I/ActivityManager(  843): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6396 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6396): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6396): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6396): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 6396): Total System Memory = 906309632
,I/GalleryUtils( 6396): Application Heap = 96 MB
I/AppConfig( 6396): App Tier : NOT_DEF
,D/SystemHelper( 6396): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  843): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6418 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/art     (  304): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.112ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 29.854ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.654ms
,W/ResourcesManager( 6418): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6418): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6418): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6418): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6418): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
I/ActivityManager(  843): Process com.android.vending (pid 5903) has died
,D/CAR.SERVICE( 6213): mConnectedToCar = false, abort
E/ActivityThread( 6213): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@32eaddb2 that was originally bound here
E/ActivityThread( 6213): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@32eaddb2 that was originally bound here
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
,E/ActivityThread( 6213): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@efe6d75 that was originally bound here
E/ActivityThread( 6213): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@efe6d75 that was originally bound here
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
W/ActivityManager(  843): Unbind failed: could not find connection for android.os.BinderProxy@f22f73
I/SystemConfig( 6418): BUILD Country: EU
I/SystemConfig( 6418): BUILD Operator: OPEN
,I/SystemConfig( 6418): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6418): existFile = false
I/SystemConfig( 6418): canReadFile = false
I/SystemConfig( 6418): systemFeature RCS result false
D/SystemConfig( 6418): refreshRcsSupport() :false
,I/ActivityManager(  843): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6437 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/LockScreenSettings( 6437): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6437): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6437): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6437): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6437): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6437): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  843): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6454 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ResourcesManager( 6454): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 2026): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/art     ( 2085): Explicit concurrent mark sweep GC freed 2746(109KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 448us total 25.629ms
,I/ActivityManager(  843): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6493 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 2026): UpdateCorporaTask done [took 56 ms] updated apps [took 56 ms] 
,D/AlertService( 6183): Beginning updateAlertNotification
,I/ActivityManager(  843): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6513 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6513): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6513): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@348aabc0
,D/Finsky  ( 6493): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/CalendarProvider2( 6513): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6513): Created com.android.providers.calendar.CalendarAlarmManager@16c383b5(com.android.providers.calendar.CalendarProvider2@348aabc0)
,D/AlertService( 6183): No fired or scheduled alerts
,I/NotificationManager( 6183): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 6183): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(8) by com.android.calendar
,I/NotificationManager( 6183): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(11) by com.android.calendar
,I/NotificationManager( 6183): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6183): com.android.calendar: cancel(20) by com.android.calendar
,D/AlertService( 6183): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6183): No events found starting within 1 week.
,I/ActivityManager(  843): Killing 6183:com.android.calendar/u0a13 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  843): failed to open /acct/uid_10013/pid_6183/cgroup.procs: No such file or directory
,D/Finsky  ( 6493): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6493): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6493): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6493): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3175): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@20b1d76f on behalf of 6493
D/Finsky  ( 6493): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6493): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6493): Skipping gmscore version check
,D/Finsky  ( 6493): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 2268): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,I/PackageBroadcastService( 2268): Null package name or gms related package.  Ignoreing.
D/WiFiOffLoadBroadcast( 6328): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/Finsky  ( 6493): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
I/Icing   ( 2268): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  843): Killing 6213:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  843): failed to open /acct/uid_10006/pid_6213/cgroup.procs: No such file or directory
,I/ActivityManager(  843): Killing 6375:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/PackageSettings(  843): Skipping PackageSetting{304396ff com.example.hello/10317} due to missing metadata
,W/libprocessgroup(  843): failed to open /acct/uid_10011/pid_6375/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
I/PCSuite ( 6265): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6265): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6328): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6328): MCCMNC not supported: null
,I/PCSuite ( 6265): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6265): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  843): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6565 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6565): Register our PhoneStateListener
,D/GCM     ( 1752): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 2268): Checkin interval check for package: unspecified last checkin: 1454681660554 min interval config: 0 actual interval: 22772
,D/PhoneMonitor( 6565): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6565): [loadFeatureFromXml] *** start feature loading from xml
I/CheckinService( 2268): Checking schedule, now: 1454681683349 next: 1454681690504
I/CheckinService( 2268): active receiver: disabled
D/TelephonyAutoProfiling( 6565): [parse] Load xml
V/TelephonyAutoProfiling( 6565): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6565): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6565): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  843): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6594 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6353): Create singleton instance
,D/UEI.SmartControl( 6594): Quickset Services start...
I/AudioManager( 6353): getMode name:com.lge.qremote
I/UEI.SmartControl( 6594): Manufacture = LGE
,D/UEI.SmartControl( 6594): File observer start...
I/AudioManager( 6353): getMode name:com.lge.qremote
E/UEI.SmartControl( 6594): IR Port is disabled: false
D/UEI.SmartControl( 6594): Starting file observer...
D/UEI.SmartControl( 6594): Extracting JNI libs...
D/UEI.SmartControl( 6594): --- this system supports 32-bit or 64-bit only
D/CalendarProviderBroadcastReceiver( 6513): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 6513): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6513): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6513): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6513): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  843): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6614 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6594): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6594): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6594): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6594): --- Selecting new region: 2
,I/UEI.SmartControl( 6594): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6594): Platform has CIR...
D/UEI.SmartControl( 6594): NO CIR support, need to check package...
I/UEI.SmartControl( 6594): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 6594): QS Service created
E/UEI.SmartControl( 6594): QS start get config
,I/art     (  843): Explicit concurrent mark sweep GC freed 27060(1490KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.806ms total 153.026ms
,D/UEI.SmartControl( 6594): Loading JNI Libs...
D/CalendarProvider2( 6513): [IntentService] Release Lock
D/UEI.SmartControl( 6594):  configuring local db...
D/CalendarProvider2( 6513): CalendarProviderIntentService.onDestroy()
,I/Icing   ( 2268): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/MusicStore( 6614): Database version: 120
D/Icing   ( 2268): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2268): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
D/UEI.SmartControl( 6594):  ---- Has DB8: true
,D/UEI.SmartControl( 6594): QS start statue = true Error code = 0
D/UEI.SmartControl( 6594): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6594): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6594): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6594): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6594): IrrcClient ++ 
D/irrcClient( 6594): getIrrcService ++ 
D/irrcClient( 6594): getIrrcService -- 
D/irrcClient( 6594): IrrcClient -- 
W/irrc_jni( 6594): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6594): Services init done
I/UEI.SmartControl( 6594): Device manager: loading config....
D/UEI.SmartControl( 6594): Config is loaded...
D/UEI.SmartControl( 6594):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6594): Notify AllClients services are ready: 0
I/ActivityManager(  843): Process com.google.android.apps.plus (pid 6454) has died
,D/UEI.SmartControl( 6594): QS Service init finished
D/UEI.SmartControl( 6594): QS Service version name: 0.1.73
D/UEI.SmartControl( 6594): QS Service version code: 1073
D/UEI.SmartControl( 6594): Service requested: Control
D/UEI.SmartControl( 6594): Internal service binding...
,D/UEI.SmartControl( 6594): -----IControl: 11
D/UEI.SmartControl( 6594): Caller: com.lge.qremote
D/UEI.SmartControl( 6594): ------------ IControl registerCallback...
I/UEI.SmartControl( 6594): Registering callback...
D/UEI.SmartControl( 6594): -----IControl: 19
D/UEI.SmartControl( 6594): Caller: com.lge.qremote
I/UEI.SmartControl( 6594): Registering Services Ready callback...
I/UEI.SmartControl( 6594): Notify client services are ready...
D/UEI.SmartControl( 6594): -----IControl: 8
,D/UEI.SmartControl( 6594): Caller: com.lge.qremote
I/ActivityManager(  843): Killing 6396:com.android.gallery3d/u0a23 (adj 15): empty #11
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6614): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/libprocessgroup(  843): failed to open /acct/uid_10023/pid_6396/cgroup.procs: No such file or directory
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6614): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6614): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6614): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6614): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6614): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6614): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6614): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3deb9e86: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6614): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6614): GMSCore installation verified
,I/ConfigStore( 6614): Config Database version: 1
,I/MediaRouter( 6614): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6614): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6614): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  843): Killing 6418:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  843): failed to open /acct/uid_10018/pid_6418/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6614): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  843): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6649 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6614): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6614): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  843): Killing 6437:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/ResourcesManager( 6649): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6649): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6649): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  843): failed to open /acct/uid_10069/pid_6437/cgroup.procs: No such file or directory
,I/NotificationManager( 6614): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6649): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6649): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/ActivityManager(  843): Process com.android.vending (pid 6493) has died
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,D/eas_req ( 6649): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  843): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6673 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6649): JNI_OnLoad()
I/HubEmail( 6649): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6649): registerNatives()
I/HubEmail( 6649): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6649): registerNativeMethods()
I/HubEmail( 6649): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6649): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  843): Killing 6291:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  843): failed to open /acct/uid_10061/pid_6291/cgroup.procs: No such file or directory
W/Settings( 6649): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6673): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6673): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6673): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6673): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6673): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6673): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6673): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6673): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  843): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6701 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6673): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,E/LGDMClient( 6673): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6673): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6673): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6673): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6673): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  843): Killing 6328:com.android.settings/1000 (adj 15): empty #11
,W/libprocessgroup(  843): failed to open /acct/uid_1000/pid_6328/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6701): onCreate
W/AppUp4:DB( 6701):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6701):  setFingerPrint start
I/AppUp4:DB( 6701):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6701):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6701):  SDK version = 0
I/AppUp4:DB( 6701):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6701): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6701): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6701): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6701): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6701): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6701): onReceive
I/AppUp4:CustModeStarterReceiver( 6701): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6701): Context : android.app.ReceiverRestrictedContext@165e6a4a
D/AppUp4:CustFacade( 6701): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6701): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6701): begin check event
I/AppUp4:CustModeStarterReceiver( 6701): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6701): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6701): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6701): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6701): handleAsyncCustNotification do not startCustService
I/ActivityManager(  843): Killing 6265:com.lge.sync/1000 (adj 15): empty #11
,W/libprocessgroup(  843): failed to open /acct/uid_1000/pid_6265/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3152): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3152): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3152): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 6565): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6565): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3175): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3175): DownloadService onCreate
I/ActivityManager(  843): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6730 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/DownloadManager( 3175): in removeSpuriousFiles
I/art     (  304): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 25.530ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.962ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 25.467ms
I/NotificationManager( 3175): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3175): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@2a36bc7c on behalf of 3175
I/DownloadManager( 3175): in trimDatabase
V/DownloadManager( 3175): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@2aa43905 on behalf of 3175
,V/DownloadManager( 3175): DownloadService onStartCommand
V/DownloadManager( 3175): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@3e712468 on behalf of 3175
I/ActivityManager(  843): Killing 6594:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6353): android.os.DeadObjectException
W/System.err( 6353): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6353): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6353): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6353): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
,W/System.err( 6353): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6353): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6353): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6353): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6353): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6353): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6353): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6353): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6353): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6353): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6353): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6353): android.os.DeadObjectException
W/System.err( 6353): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6353): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 6353): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6353): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6353): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6353): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6353): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6353): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6353): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6353): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6353): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6353): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6353): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6353): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6353): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,E/libprocessgroup(  843): failed to kill 1 processes for processgroup 6594
,D/WeatherAncestor( 2624): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:46
W/ActivityManager(  843): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,V/DownloadManager( 3175): DownloadService onDestroy
D/UpdateThreadPoolManager( 2624): 2 : This is isUpdating : false
D/WeatherAncestor( 2624): connectivity changed - connection : true
D/Weather_cast( 2624): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2624): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:46
,D/WeatherService( 2624): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  843): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6764 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  843): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6781 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  843): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2624): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2624): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2624): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6764): Quickset Services start...
I/UEI.SmartControl( 6764): Manufacture = LGE
W/ResourcesManager( 6781): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6764): File observer start...
E/UEI.SmartControl( 6764): IR Port is disabled: false
D/UEI.SmartControl( 6764): Starting file observer...
D/UEI.SmartControl( 6764): Extracting JNI libs...
,D/UEI.SmartControl( 6764): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6764): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6764): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6764): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6764): --- Selecting new region: 2
,I/UEI.SmartControl( 6764): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6764): Platform has CIR...
D/UEI.SmartControl( 6764): NO CIR support, need to check package...
I/UEI.SmartControl( 6764): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6764): QS Service created
,E/UEI.SmartControl( 6764): QS start get config
,D/UEI.SmartControl( 6764): Loading JNI Libs...
D/UEI.SmartControl( 6764):  configuring local db...
,I/Babel_SMS( 6781): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6781): MmsConfig.loadMmsSettings
I/Babel_SMS( 6781): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6781): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6781): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6781): MmsConfig.loadFromResources
E/Babel_SMS( 6781): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6781): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6781): CheckpointMarkThreadRoots callback created = 0xb002d4e0
,D/SensorManager( 6781): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6781): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6781): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6781): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6781): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6781): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6781): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6781): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6781): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6781): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6781): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6781): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6781): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6781): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6781): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6781): found sensor: Motion Accel, handle=46
I/art     ( 6781): CheckpointMarkThreadRoots callback created = 0xb002d4d0
,D/UEI.SmartControl( 6764):  ---- Has DB8: true
D/UEI.SmartControl( 6764): QS start statue = true Error code = 0
D/UEI.SmartControl( 6764): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6764): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
W/art     ( 6781): Suspending all threads took: 6.739ms
,D/UEI.SmartControl( 6764): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6764): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6764): IrrcClient ++ 
D/irrcClient( 6764): getIrrcService ++ 
,D/irrcClient( 6764): getIrrcService -- 
D/irrcClient( 6764): IrrcClient -- 
W/irrc_jni( 6764): IRRCPlayer_nativeInit -- 
W/Settings( 6781): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/UEI.SmartControl( 6764): Services init done
,I/UEI.SmartControl( 6764): Device manager: loading config....
I/Babel_Crash( 6781): startup - clean
D/UEI.SmartControl( 6764): QS Service init finished
D/UEI.SmartControl( 6764): QS Service version name: 0.1.73
D/UEI.SmartControl( 6764): QS Service version code: 1073
D/UEI.SmartControl( 6764): Service requested: Control
D/UEI.SmartControl( 6764): Config is loaded...
I/Babel   ( 6781): deleted: false for 0
,D/UEI.SmartControl( 6764):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6764): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6764): Request IControl service: devices are loaded...
I/ActivityManager(  843): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6823 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  843): Killing 6353:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6764): Internal service binding...
,W/libprocessgroup(  843): failed to open /acct/uid_10106/pid_6353/cgroup.procs: No such file or directory
,W/AudioCapabilities( 6781): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6781): Unsupported mime audio/adpcm
W/AudioCapabilities( 6781): Unsupported mime audio/g726
W/AudioCapabilities( 6781): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6781): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6781): Unsupported mime video/mjpg
W/VideoCapabilities( 6781): Unsupported mime video/theora
,W/AudioCapabilities( 6781): Unsupported mime audio/evrc
,W/AudioCapabilities( 6781): Unsupported mime audio/qcelp
W/VideoCapabilities( 6781): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6781): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6781): Unsupported mime audio/qcelp
W/AudioCapabilities( 6781): Unsupported mime audio/evrc
W/VideoCapabilities( 6781): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6781): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6781): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6781): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6781): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6781): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6781): onServiceConnected
W/Babel   ( 6781): Attempted to change video mute state without an active call.
,I/NotificationManager( 6781): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6781): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6781): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6781): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6781): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  273): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 6781): propertyValue:false
I/Babel   ( 6781): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  843): Killing 6513:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  843): failed to open /acct/uid_10014/pid_6513/cgroup.procs: No such file or directory
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6823): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6823): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6823): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6823): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6823): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6823):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6823):   adb logcat -s GAv4
,W/GAv4    ( 6823): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6823): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6823): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/WebViewFactory( 6823): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6823): Time to load native libraries: 4 ms (timestamps 6213-6217)
I/LibraryLoader( 6823): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6823): Binding Chromium to main looper Looper (main, tid 1) {10ed7a5f}
,I/LibraryLoader( 6823): Expected native library version number "",actual native library version number ""
I/chromium( 6823): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6823): Initializing chromium process, singleProcess=true
W/art     ( 6823): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6823): ApplicationContext is null in ApplicationStatus
W/chromium( 6823): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6823): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 6823): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6823): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6823): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6823): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6823): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6823): Remote Branch: 
I/Adreno-EGL( 6823): Local Patches: 
I/Adreno-EGL( 6823): Reconstruct Branch: 
V/AudioPolicyService(  277): registerClient() client 0xb551c8e0, uid 10079
,I/NSApplication( 6823): Starting up...
W/AudioManagerAndroid( 6823): Requires BLUETOOTH permission
I/ActivityManager(  843): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6892 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  843): Killing 6614:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  843): failed to open /acct/uid_10081/pid_6614/cgroup.procs: No such file or directory
,I/ActivityManager(  843): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6919 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  843): Killing 6649:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  843): failed to open /acct/uid_10021/pid_6649/cgroup.procs: No such file or directory
,W/ResourcesManager( 6919): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  843): Killing 6673:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/jxcore-log( 5562): Test app app.js loaded
I/jxcore-log( 5562): 
,W/libprocessgroup(  843): failed to open /acct/uid_1000/pid_6673/cgroup.procs: No such file or directory
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5562): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5562): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5562): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5562): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5562): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5562): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5562): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5562): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5562): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5562): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@353a1313 added. We now have 1 listener(s)
D/BluetoothAdapterService(871736881)( 2062): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@eb2658f
I/jxcore-log( 5562): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5562): 
I/ActivityManager(  843): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6950 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/chromium( 5562): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/MusicStore( 6950): Database version: 120
,I/art     (  843): Explicit concurrent mark sweep GC freed 19533(950KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.271ms total 144.890ms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6950): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6950): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6950): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6950): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6950): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6950): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6950): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6950): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3deb9e86: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6950): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6950): GMSCore installation verified
I/ConfigStore( 6950): Config Database version: 1
,I/MediaRouter( 6950): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6950): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6950): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/NetworkMonitor( 6950): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  843): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6981 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/GHttpClientFactory( 6950): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6950): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 6981): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6981): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6981): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  843): Killing 6701:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  843): failed to open /acct/uid_10011/pid_6701/cgroup.procs: No such file or directory
,I/NotificationManager( 6950): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6981): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6981): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6981): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  843): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7018 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 6981): JNI_OnLoad()
,I/HubEmail( 6981): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6981): registerNatives()
I/HubEmail( 6981): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6981): registerNativeMethods()
I/HubEmail( 6981): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6981): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6981): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  843): Killing 6565:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  843): failed to open /acct/uid_10038/pid_6565/cgroup.procs: No such file or directory
,D/LGDMClient( 7018): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7018): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7018): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7018): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
D/LGDMClient( 7018): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7018): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  843): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7042 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7018): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7018): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7018): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7018): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7018): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  843): Killing 6730:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  843): failed to open /acct/uid_10051/pid_6730/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7042): onCreate
W/AppUp4:DB( 7042):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7042):  setFingerPrint start
I/AppUp4:DB( 7042):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7042):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7042):  SDK version = 0
I/AppUp4:DB( 7042):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7042): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7042): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7042): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7042): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7042): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7042): onReceive
I/AppUp4:CustModeStarterReceiver( 7042): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7042): Context : android.app.ReceiverRestrictedContext@165e6a4a
D/AppUp4:CustFacade( 7042): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7042): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7042): begin check event
I/AppUp4:CustModeStarterReceiver( 7042): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7042): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7042): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7042): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7042): handleAsyncCustNotification do not startCustService
I/ActivityManager(  843): Killing 6764:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  843): failed to open /acct/uid_10089/pid_6764/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3152): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3152): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3152): networkInfo.isConnected() = false
,I/ActivityManager(  843): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7064 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7064): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7064): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7064): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  843): Killing 6781:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7064): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7064): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7064): [parse] Load xml
V/TelephonyAutoProfiling( 7064): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7064): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7064): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  843): failed to open /acct/uid_10061/pid_6781/cgroup.procs: No such file or directory
,V/DownloadManager( 3175): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3175): DownloadService onCreate
,I/DownloadManager( 3175): in removeSpuriousFiles
I/NotificationManager( 3175): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3175): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@19fa9526 on behalf of 3175
I/DownloadManager( 3175): in trimDatabase
V/DownloadManager( 3175): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@27681f14 on behalf of 3175
I/ActivityManager(  843): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7086 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3175): DownloadService onStartCommand
,I/art     (  304): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 291us total 24.850ms
I/CheckinService( 2268): Checkin interval check for package: unspecified last checkin: 1454681660554 min interval config: 0 actual interval: 30981
V/DownloadManager( 3175): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/art     (  304): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.640ms
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@32eaddb2 on behalf of 3175
I/CheckinService( 2268): Checking schedule, now: 1454681691567 next: 1454681690504
I/CheckinService( 2268): active receiver: enabled
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 25.937ms
V/DownloadManager( 3175): DownloadService onDestroy
,I/CheckinService( 2268): Preparing to send checkin request
I/EventLogService( 2268): Accumulating logs since 1454681652328
,D/WeatherAncestor( 2624): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:51
D/UpdateThreadPoolManager( 2624): 2 : This is isUpdating : false
D/WeatherAncestor( 2624): connectivity changed - connection : true
D/Weather_cast( 2624): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2624): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:51
D/WeatherService( 2624): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  843): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7115 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  843): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2624): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2624): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2624): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/CheckinRequestBuilder( 2268): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 2268): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 7115): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  843): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7137 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/Babel_SMS( 7115): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7115): MmsConfig.loadMmsSettings
I/Babel_SMS( 7115): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7115): MmsConfig.loadFromDatabase
W/ResourcesManager( 7137): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7137): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Babel_SMS( 7115): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7115): MmsConfig.loadFromResources
E/Babel_SMS( 7115): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7115): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7115): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7115): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7115): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7115): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7115): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7115): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7115): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7115): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7115): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7115): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7115): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7115): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7115): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7115): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7115): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7115): found sensor: Motion Accel, handle=46
,I/MultiDex( 7137): VM with version 2.1.0 has multidex support
I/MultiDex( 7137): install
,I/MultiDex( 7137): VM has multidex support, MultiDex support library is disabled.
W/Settings( 7115): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7115): startup - clean
I/Babel   ( 7115): deleted: false for 0
,I/art     ( 7115): CheckpointMarkThreadRoots callback created = 0xb002d530
V/JNIHelp ( 7137): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 7115): CheckpointMarkThreadRoots callback created = 0xb002d500
W/AudioCapabilities( 7115): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7115): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7115): Unsupported mime audio/g726
,W/AudioCapabilities( 7115): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7115): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7115): Unsupported mime video/mjpg
W/VideoCapabilities( 7115): Unsupported mime video/theora
,W/ActivityThread( 7137): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7137): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@20b1d76f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7137): Installed default security provider GmsCore_OpenSSL
D/GCM     ( 1752): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/NotificationManager( 7137): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7137): com.google.android.gms: cancel(39789) by com.google.android.gms
W/AudioCapabilities( 7115): Unsupported mime audio/evrc
,W/AudioCapabilities( 7115): Unsupported mime audio/qcelp
W/VideoCapabilities( 7115): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7115): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7115): Unsupported mime audio/qcelp
W/AudioCapabilities( 7115): Unsupported mime audio/evrc
W/VideoCapabilities( 7115): Unsupported mime video/mp4v-esdp
,V/MusicLeanback( 6950): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
D/LGDMClient( 7018): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7018): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/Settings( 6981): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ContextImpl( 7018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 7042): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7042): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7042): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7042): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7042): onReceive
I/AppUp4:CustModeStarterReceiver( 7042): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7042): Context : android.app.ReceiverRestrictedContext@165e6a4a
D/AppUp4:CustFacade( 7042): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7042): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7042): begin check event
I/AppUp4:CustModeStarterReceiver( 7042): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LgeMiscReceiver( 3152): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3152): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3152): networkInfo.isConnected() = true
,D/PhoneState( 3152): setPdpRejectCasuse : false
D/LGDMClient( 7018): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/MobileConnectivityChangeReceiver( 7064): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7064): onReceive CONNECTIVITY_CHANGE networkType=1
I/VideoCapabilities( 7115): Unsupported profile 4 for video/mp4v-es
I/art     ( 7137): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7137): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
V/DownloadManager( 3175): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 7018): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/DownloadManager( 3175): DownloadService onCreate
D/LGDMClient( 7018): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7018): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/DownloadManager( 3175): in removeSpuriousFiles
V/DownloadManager( 3175): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 3175): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@2e321880 on behalf of 3175
D/WeatherAncestor( 2624): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:52
D/UpdateThreadPoolManager( 2624): 2 : This is isUpdating : false
D/WeatherAncestor( 2624): connectivity changed - connection : true
D/Weather_cast( 2624): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2624): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:14:52
W/ContextImpl( 7018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
V/DownloadManager( 3175): DownloadService onStartCommand
,D/WeatherService( 2624): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 3175): in trimDatabase
V/DownloadManager( 3175): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3175): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
E/LGDMClient( 7018): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
W/ActivityManager(  843): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2624): 2 : Utils getTopActivity com.lge.launcher2 / true
D/LGDMClient( 7018): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7018): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/WeatherService( 2624): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2624): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
W/VideoCapabilities( 7115): Unrecognized profile 2130706433 for video/avc
D/LGDMClient( 7018): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@14e03cac on behalf of 3175
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@10ed7a5f on behalf of 3175
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/VideoCapabilities( 7115): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7115): Unrecognized profile 2130706433 for video/avc
D/LGDMClient( 7018): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,W/VideoCapabilities( 7115): Unrecognized profile 2130706433 for video/avc
D/NativeLibraryUtils( 7137): Install completed successfully. count=14 extracted=0
,I/art     (  843): Explicit concurrent mark sweep GC freed 18269(894KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.373ms total 149.275ms
V/DownloadManager( 3175): DownloadService onDestroy
,I/vclib   ( 7115): onServiceConnected
W/Babel   ( 7115): Attempted to change video mute state without an active call.
I/art     ( 6919): CheckpointMarkThreadRoots callback created = 0xaaf084f0
,I/NotificationManager( 7115): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7115): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7115): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7115): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7115): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  273): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 7115): propertyValue:false
I/art     ( 6919): CheckpointMarkThreadRoots callback created = 0xaaf084c0
,I/Babel   ( 7115): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  843): Process com.google.android.music:main (pid 6950) has died
,D/WVCdm   (  277): Instantiating CDM.
,I/WVCdm   (  277): CdmEngine::OpenSession
I/WVCdm   (  277): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  277): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  277): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  277): L1 library not specified. Falling Back to L3
,I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  277): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  277): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
D/WVCdm   (  277): PrepareKeyRequest: nonce=2185034706
,I/ActivityManager(  843): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7183 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  843): Process com.lge.email (pid 6981) has died
,W/ActivityManager(  843): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7183): getAccountsCursor
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7183): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/dex2oat ( 7204): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ActivityManager(  843): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7183): Error finding the version of the Email provider.....
E/Gmail   ( 7183): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7183): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7183): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7183): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7183): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7183): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7183): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7183): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7183): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7183): getAccountsCursor
V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  843): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7225 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ActivityManager(  843): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/dex2oat ( 7204): dex2oat took 114.054ms (threads: 4)
,I/art     ( 7137): CheckpointMarkThreadRoots callback created = 0xb00cae50
I/Adreno-EGL( 7137): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7137): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7137): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7137): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7137): Remote Branch: 
I/Adreno-EGL( 7137): Local Patches: 
I/Adreno-EGL( 7137): Reconstruct Branch: 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ActivityManager(  843): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 7183): Observing account changes for notifications
,I/art     ( 7137): CheckpointMarkThreadRoots callback created = 0xb00cae40
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 7225): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  843): Message: 20
,D/BluetoothManagerService(  843): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@78d6797:true
D/BluetoothAdapterService(871736881)( 2062): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@eb2658f
D/BluetoothAdapterService(871736881)( 2062): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@eb2658f
V/AlarmManager(  843): RTC_WAKEUP set : Alarm{cb6e633 type 0 when 1454681690504 com.google.android.gms} when 1454681690504
,I/ActivityManager(  843): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7248 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  843): RTC_WAKEUP set : Alarm{2275bdf0 type 0 when 1454681693667 com.android.vending} when 1454681693667
,I/AudioManager( 7225): getMode name:com.lge.qremote
,I/Gmail   ( 7183): notifyAccountChanged
I/Gmail   ( 7183): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7183): getAccountsCursor
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 7225): getMode name:com.lge.qremote
,I/Gmail   ( 7183): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/AuthorizationBluetoothService( 1752): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 2268): Restart initialization of location
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WearableService( 1752): callingUid 10006, callindPid: 1752
I/NotificationManager( 1752): com.google.android.gms: cancel(0) by com.google.android.gms
E/MDM     ( 1752): [106] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/Gmail   ( 7183): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7183): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/GCoreFlp( 1752): No location to return for getLastLocation()
W/FusedLocationProvider( 1752): location=null
I/Gmail   ( 7183): getAccountsCursor
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7248): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/WVCdm   (  277): CdmEngine::OpenSession
,D/Finsky  ( 7248): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7248): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7248): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7248): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  843): Process com.lge.appbox.client (pid 7042) has died
,V/DownloadManager( 3175): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@52c710a on behalf of 7248
D/Finsky  ( 7248): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7248): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7248): Skipping gmscore version check
D/Finsky  ( 7248): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 7248): [929] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7248): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  843): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7299 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7225): Create singleton instance
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  843): android: cancelAsUser(2) by android
,D/UEI.SmartControl( 7299): Quickset Services start...
,I/UEI.SmartControl( 7299): Manufacture = LGE
D/UEI.SmartControl( 7299): File observer start...
E/UEI.SmartControl( 7299): IR Port is disabled: false
D/UEI.SmartControl( 7299): Starting file observer...
D/UEI.SmartControl( 7299): Extracting JNI libs...
D/UEI.SmartControl( 7299): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7225): getMode name:com.lge.qremote
,D/libc-netbsd( 7248): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7248): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7248): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7248): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
I/AudioManager( 7225): getMode name:com.lge.qremote
D/GCM     ( 1752): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/UEI.SmartControl( 7299): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7299): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7299): --- Extracting JNI libs: libqs_armeabi-v7a.zip
E/MDM     ( 1752): [147] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1752): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
D/LocationInitializer( 2268): Restart initialization of location
V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1752): com.google.android.gms: cancel(0) by com.google.android.gms
,I/System.out( 7248): propertyValue:false
W/GCoreFlp( 1752): No location to return for getLastLocation()
W/FusedLocationProvider( 1752): location=null
,I/UEI.SmartControl( 7299): --- Selecting new region: 2
,I/UEI.SmartControl( 7299): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7299): Platform has CIR...
D/UEI.SmartControl( 7299): NO CIR support, need to check package...
I/UEI.SmartControl( 7299): Model: LG-D722 uses JNI
I/CheckinService( 2268): Checkin interval check for package: unspecified last checkin: 1454681660554 min interval config: 0 actual interval: 34197
I/AudioManager( 7225): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7299): QS Service created
E/UEI.SmartControl( 7299): QS start get config
,D/UEI.SmartControl( 7299): Loading JNI Libs...
D/UEI.SmartControl( 7299):  configuring local db...
,D/Finsky  ( 7248): [925] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7248): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/WVCdm   (  277): CdmEngine::CloseSession
,D/UEI.SmartControl( 7299):  ---- Has DB8: true
,D/UEI.SmartControl( 7299): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7299): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7299): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7299): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7299): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7299): IrrcClient ++ 
D/irrcClient( 7299): getIrrcService ++ 
D/irrcClient( 7299): getIrrcService -- 
D/irrcClient( 7299): IrrcClient -- 
W/irrc_jni( 7299): IRRCPlayer_nativeInit -- 
I/WVCdm   (  277): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  277): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  277): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  277): CdmEngine::GenerateKeyRequest
D/UEI.SmartControl( 7299): Services init done
I/UEI.SmartControl( 7299): Device manager: loading config....
D/UEI.SmartControl( 7299): QS Service init finished
D/WVCdm   (  277): PrepareKeyRequest: nonce=152295736
D/UEI.SmartControl( 7299): QS Service version name: 0.1.73
D/UEI.SmartControl( 7299): Config is loaded...
D/UEI.SmartControl( 7299): QS Service version code: 1073
D/UEI.SmartControl( 7299): Service requested: Control
D/UEI.SmartControl( 7299): Internal service binding...
D/UEI.SmartControl( 7299): -----IControl: 11
,D/UEI.SmartControl( 7299): Caller: com.lge.qremote
D/UEI.SmartControl( 7299): ------------ IControl registerCallback...
I/UEI.SmartControl( 7299): Registering callback...
D/UEI.SmartControl( 7299): -----IControl: 19
D/UEI.SmartControl( 7299): Caller: com.lge.qremote
I/UEI.SmartControl( 7299): Registering Services Ready callback...
I/UEI.SmartControl( 7299): Notify client services are ready...
D/UEI.SmartControl( 7299): -----IControl: 8
,D/UEI.SmartControl( 7299): Caller: com.lge.qremote
I/AudioManager( 7225): getMode name:com.lge.qremote
I/ActivityManager(  843): Killing 7018:com.lge.lgdmsclient/1000 (adj 15): empty #11
,D/UEI.SmartControl( 7299):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7299): Notify AllClients services are ready: 0
I/ActivityManager(  843): Killing 7086:com.lge.drmservice/u0a51 (adj 15): empty #12
,W/libprocessgroup(  843): failed to open /acct/uid_1000/pid_7018/cgroup.procs: No such file or directory
,W/libprocessgroup(  843): failed to open /acct/uid_10051/pid_7086/cgroup.procs: No such file or directory
I/AudioManager( 7225): getMode name:com.lge.qremote
,I/AudioManager( 7225): getMode name:com.lge.qremote
,W/ContextImpl( 3594): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/WVCdm   (  277): CdmEngine::CloseSession
,I/WVCdm   (  277): L3 Terminate.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 115226882824; DSPS: 3874443; Offset : -3021261435
,I/GAV2    ( 7183): Thread[GAThread,5,main]: No campaign data found.
,I/Adreno-EGL( 7137): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7137): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7137): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7137): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7137): Remote Branch: 
I/Adreno-EGL( 7137): Local Patches: 
I/Adreno-EGL( 7137): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Adreno-EGL( 7137): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7137): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7137): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7137): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7137): Remote Branch: 
I/Adreno-EGL( 7137): Local Patches: 
I/Adreno-EGL( 7137): Reconstruct Branch: 
,I/CheckinRequestBuilder( 2268): Classify the device as Phone.
,D/libc-netbsd( 2268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 2268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 2268): propertyValue:false
D/libc-netbsd( 2268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 2268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 2268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2268): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2268): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 2268): Sending checkin request (9973 bytes)
,I/MusicWidget( 2586): mDelayedStopHandler : unbind
,I/MusicBrowser( 2661): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2661): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2661): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2661): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2661): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2661): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2661): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2661): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  843):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@23f9cbabcom.lge.music.MediaPlaybackService$6@1eac0208
,D/MusicBrowser( 2661): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2661): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2661): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2661): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2661): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@3320e116
,I/MusicBrowser( 2661): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2661): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2661): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2661): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2661): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2661): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2661): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2661): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2661): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2661): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2661): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2661): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2661): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2661): reset
V/MediaPlayer[Native]( 2661): setListener
,V/MediaPlayer[Native]( 2661): disconnect
V/MediaPlayer[Native]( 2661): destructor
V/AudioFlinger(  277): releasing 18 from 2661 for -1
V/AudioFlinger(  277):  decremented refcount to 0
V/AudioFlinger(  277): purging stale effects
V/MediaPlayer[Native]( 2661): disconnect
D/MusicBrowser( 2661): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2661): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2661): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2661): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2661): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2661): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
,I/SmartShareClient( 2661): [SmartShareManagerClient] unregisterListener: 302742945
W/SmartShareClient( 2661): [SmartShareManagerClient] unregisterListener invalid listener: 302742945
I/SmartShareClient( 2661): [SmartShareManagerClient] terminate service: 2661/MediaPlaybackService/625918956
E/HomeCloudIF( 2661): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2661): [SmartShareManagerClient] unbindService context:android.app.Application@3ab1bbc6
V/CloudHub( 2661): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2661): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2661): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2661): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2661): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  843): Killing 6823:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/CloudHub( 2661): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29990
W/libprocessgroup(  843): failed to open /acct/uid_10079/pid_6823/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 2268): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 2268): Failed to find provider info for com.google.android.wearable.settings
I/art     ( 2085): Explicit concurrent mark sweep GC freed 2210(85KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.327ms total 38.204ms
,I/art     (  843): Explicit concurrent mark sweep GC freed 24789(1107KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.396ms total 157.598ms
,I/CheckinRequestBuilder( 2268): Classify the device as Phone.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinTask( 2268): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2268): Checking schedule, now: 1454681699494 next: 1455208948488
I/CheckinService( 2268): active receiver: disabled
,I/CheckinService( 2268): Checking schedule, now: 1454681699540 next: 1455208948488
,I/CheckinService( 2268): active receiver: disabled
,D/CheckinService( 2268): Recording last checkin time for package unspecified as 1454681699552
,V/SetupWizard( 7064): Connected to Gservices successfully
,D/GCM     ( 1752): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  843): Killing 6919:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/ActivityManager(  843): Killing 6892:com.android.chrome/u0a48 (adj 15): empty #12
,W/libprocessgroup(  843): failed to open /acct/uid_10086/pid_6919/cgroup.procs: No such file or directory
,W/libprocessgroup(  843): failed to open /acct/uid_10048/pid_6892/cgroup.procs: No such file or directory
D/PowerManagerServiceEx(  843): acquireWakeLockInternal: lock=977273687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=843
,D/WeatherService( 2624): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:15:0
,D/WeatherService( 2624): 2 : TimeTick Intent And Screen On
D/WeatherService( 2624): 2 : SDK version : 21
W/ActivityManager(  843): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2624): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2624): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2624): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2624): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2624): 2 : This is isUpdating : false
D/WeatherService( 2624): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2624): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2624): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2624): 2 : Fixed theme : optimus
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
D/WeatherReflect( 2624): 2 : Map key string is -2
,I/[SystemUI]Clock( 1372): called onTimeUpdated()
D/UEI.SmartControl( 7299): Internal timer expired: 1
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
,D/lim     ( 2624): 2 : time = 15:15
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/WeatherReflect( 2624): Model Name : LG-D722
D/WeatherTheme( 2624): 2 : Different view - status_min_formatted : 14 != 15
D/WeatherTheme( 2624): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2624): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2624): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2624): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2624): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2624): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2624): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2624): forecast size is 0
,D/Theme   ( 2624): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2624): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2624): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2624): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2624): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2624): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2624): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2624): url is : null
D/Theme   ( 2624): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2624): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2624): 2 : update view, appWidgetId: 2
D/WeatherService( 2624): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:15:0
D/PowerManagerServiceEx(  843): releaseWakeLockInternal: lock=977273687 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1951): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1951): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1913): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  843): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator(  843): Handling package changes for user 0
,I/[LGHome]EVENT( 1951): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1951): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1951): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1951): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  843): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7412 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 7115): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7115): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7115): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 7412): onCreate
,W/AppUp4:DB( 7412):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7412):  setFingerPrint start
I/AppUp4:DB( 7412):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,V/JNIHelp ( 7115): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:DB( 7412):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7412):  SDK version = 0
I/AppUp4:DB( 7412):  beforefinger == newfinger no write in DB
I/NotificationService(  843): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  843): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  843): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  843): Process com.android.vending (pid 7248) has died
,D/AppUp4:AppBoxApplication( 7412): AppBoxApplication onCreate()
I/BackupManagerService(  843): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  843): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/AppUp4:CustModeStarterReceiver( 7412): onReceive
I/AppUp4:CustModeStarterReceiver( 7412): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
V/BackupManagerService(  843): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@206ab36e
D/AppUp4:CustFacade( 7412): Context : android.app.ReceiverRestrictedContext@3ff0969f
D/AppUp4:CustFacade( 7412): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7412): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7412): begin check event
I/AppUp4:CustModeStarterReceiver( 7412): Event For Nothing, skip.
W/System  ( 7115): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7115): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager(  843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  843): Process com.google.android.gm (pid 7183) has died
,I/ActivityManager(  843): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7437 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/LCardEmulationManager( 1852): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1852): getDefaultRoute
W/ResourceType(  843): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  843): Process com.lge.music (pid 2661) has died
,V/AudioFlinger(  277): 2661 died, releasing its sessions
V/AudioFlinger(  277):  pid 1780 @ 0
V/AudioFlinger(  277):  pid 3152 @ 1
V/AudioFlinger(  277):  pid 3152 @ 2
W/ResourcesManager( 7437): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7437): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7437): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1951): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1752): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  843): applying state to connected service
,I/AppConfig( 7437): Total System Memory = 906309632
,I/GalleryUtils( 7437): Application Heap = 96 MB
I/AppConfig( 7437): App Tier : NOT_DEF
D/SystemHelper( 7437): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  843): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7457 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7457): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7457): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7457): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7457): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 7457): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7457): BUILD Country: EU
I/SystemConfig( 7457): BUILD Operator: OPEN
,I/ActivityManager(  843): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7482 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/SystemConfig( 7457): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7457): existFile = false
I/SystemConfig( 7457): canReadFile = false
I/SystemConfig( 7457): systemFeature RCS result false
D/SystemConfig( 7457): refreshRcsSupport() :false
,I/LockScreenSettings( 7482): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/ActivityManager(  843): Process com.google.android.setupwizard (pid 7064) has died
D/LockScreenSettings( 7482): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7482): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7482): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7482): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7482): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  843): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7499 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 23.500ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.066ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.090ms
,W/ResourcesManager( 7499): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 2026): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  843): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7533 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 2026): UpdateCorporaTask done [took 53 ms] updated apps [took 53 ms] 
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/Finsky  ( 7533): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7533): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7533): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7533): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7533): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3175): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3175): created cursor android.database.sqlite.SQLiteCursor@36195d7b on behalf of 7533
,D/Finsky  ( 7533): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7533): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7533): Skipping gmscore version check
D/Finsky  ( 7533): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 2268): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 7533): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  843): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7578 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/PackageBroadcastService( 2268): Null package name or gms related package.  Ignoreing.
I/Icing   ( 2268): updateResources: need to parse f{com.google.android.gms}
,I/DigitalAppWidgetProvider( 7578): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7578): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3ff0969f
I/ActivityManager(  843): Killing 7137:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  843): failed to open /acct/uid_10006/pid_7137/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 2268): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 2268): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  843): Killing 7299:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 7225): android.os.DeadObjectException
,W/System.err( 7225): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7225): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7225): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7225): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7225): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7225): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7225): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7225): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7225): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7225): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7225): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7225): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7225): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7225): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7225): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7225): android.os.DeadObjectException
W/System.err( 7225): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7225): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7225): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7225): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7225): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7225): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7225): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7225): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7225): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7225): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7225): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7225): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7225): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7225): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7225): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  843): failed to open /acct/uid_10089/pid_7299/cgroup.procs: No such file or directory
,W/ActivityManager(  843): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  843): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7610 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7610): Quickset Services start...
,I/UEI.SmartControl( 7610): Manufacture = LGE
D/UEI.SmartControl( 7610): File observer start...
E/UEI.SmartControl( 7610): IR Port is disabled: false
D/UEI.SmartControl( 7610): Starting file observer...
D/UEI.SmartControl( 7610): Extracting JNI libs...
D/UEI.SmartControl( 7610): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7610): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7610): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7610): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7610): --- Selecting new region: 2
,I/UEI.SmartControl( 7610): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7610): Platform has CIR...
D/UEI.SmartControl( 7610): NO CIR support, need to check package...
I/UEI.SmartControl( 7610): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7610): QS Service created
E/UEI.SmartControl( 7610): QS start get config
,D/UEI.SmartControl( 7610): Loading JNI Libs...
,D/UEI.SmartControl( 7610):  configuring local db...
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7610):  ---- Has DB8: true
,D/UEI.SmartControl( 7610): QS start statue = true Error code = 0
D/UEI.SmartControl( 7610): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7610): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7610): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7610): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7610): IrrcClient ++ 
D/irrcClient( 7610): getIrrcService ++ 
D/irrcClient( 7610): getIrrcService -- 
D/irrcClient( 7610): IrrcClient -- 
W/irrc_jni( 7610): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7610): Services init done
,I/UEI.SmartControl( 7610): Device manager: loading config....
D/UEI.SmartControl( 7610): QS Service init finished
D/UEI.SmartControl( 7610): QS Service version name: 0.1.73
D/UEI.SmartControl( 7610): Config is loaded...
D/UEI.SmartControl( 7610): QS Service version code: 1073
D/UEI.SmartControl( 7610): Service requested: Control
I/ActivityManager(  843): Killing 7225:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  843): failed to open /acct/uid_10106/pid_7225/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7610): Internal service binding...
D/UEI.SmartControl( 7610):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7610): Notify AllClients services are ready: 0
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  843): Killing 7115:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  843): failed to open /acct/uid_10061/pid_7115/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/charger_monitor(  458): init target 500000
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/charger_monitor(  458): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
D/WifiController(  843): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7610): Internal timer expired: 1
,D/UEI.SmartControl( 7610): Service.onUnbind: IControl
D/UEI.SmartControl( 7610): Service.onDestroy
D/UEI.SmartControl( 7610): Shutdown IRRCPlayer... 
,W/irrc_jni( 7610): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7610): ~IrrcClient ++ 
D/irrcClient( 7610): ~IrrcClient -- 
W/irrc_jni( 7610): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7610): Blaster closed
D/UEI.SmartControl( 7610): Blaster closed
D/UEI.SmartControl( 7610): Shut down QS...
,D/UEI.SmartControl( 7610): Stopped file observer...
I/UEI.SmartControl( 7610): QS lib stop result = true
D/UEI.SmartControl( 7610): QS shutdown complete
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 135231281359; DSPS: 4529947; Offset : -3021257430
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  843): ELAPSED_WAKEUP set : Alarm{1a11ed73 type 2 when 144418 com.google.android.gms} when 144418
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1752): Vacuum at: now=1454681726963 tag=VacuumService
,I/art     (  843): Explicit concurrent mark sweep GC freed 40257(1988KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.262ms total 196.745ms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  843): ALS enabled for SRE
,D/PowerManagerServiceEx(  843): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28582 ms ago)
D/qdlights(  843): set_light_backlight: 254
,D/qdlights(  843): set_light_backlight: 251
D/qdlights(  843): set_light_backlight: 248
,D/qdlights(  843): set_light_backlight: 244
,D/qdlights(  843): set_light_backlight: 241
,D/qdlights(  843): set_light_backlight: 238
,D/qdlights(  843): set_light_backlight: 234
,D/qdlights(  843): set_light_backlight: 231
,D/qdlights(  843): set_light_backlight: 228
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/qdlights(  843): set_light_backlight: 224
D/qdlights(  843): set_light_backlight: 221
,D/qdlights(  843): set_light_backlight: 218
,D/qdlights(  843): set_light_backlight: 214
,D/qdlights(  843): set_light_backlight: 211
,D/qdlights(  843): set_light_backlight: 208
,D/qdlights(  843): set_light_backlight: 204
,D/qdlights(  843): set_light_backlight: 201
,D/qdlights(  843): set_light_backlight: 198
,D/qdlights(  843): set_light_backlight: 194
,D/qdlights(  843): set_light_backlight: 191
,D/qdlights(  843): set_light_backlight: 188
,D/qdlights(  843): set_light_backlight: 184
,D/qdlights(  843): set_light_backlight: 181
,D/qdlights(  843): set_light_backlight: 178
,D/qdlights(  843): set_light_backlight: 174
,D/qdlights(  843): set_light_backlight: 171
,D/qdlights(  843): set_light_backlight: 168
,D/qdlights(  843): set_light_backlight: 164
,D/qdlights(  843): set_light_backlight: 161
,D/qdlights(  843): set_light_backlight: 158
,D/qdlights(  843): set_light_backlight: 154
,D/qdlights(  843): set_light_backlight: 151
,D/qdlights(  843): set_light_backlight: 148
,D/qdlights(  843): set_light_backlight: 144
,D/qdlights(  843): set_light_backlight: 141
,D/qdlights(  843): set_light_backlight: 138
,D/qdlights(  843): set_light_backlight: 134
,D/qdlights(  843): set_light_backlight: 131
,D/qdlights(  843): set_light_backlight: 128
,D/qdlights(  843): set_light_backlight: 124
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  843): set_light_backlight: 121
,D/qdlights(  843): set_light_backlight: 118
,D/qdlights(  843): set_light_backlight: 114
,D/qdlights(  843): set_light_backlight: 111
,D/qdlights(  843): set_light_backlight: 108
,D/qdlights(  843): set_light_backlight: 104
,D/qdlights(  843): set_light_backlight: 101
,D/qdlights(  843): set_light_backlight: 98
,D/qdlights(  843): set_light_backlight: 94
,D/qdlights(  843): set_light_backlight: 91
,D/qdlights(  843): set_light_backlight: 88
,D/qdlights(  843): set_light_backlight: 84
,D/qdlights(  843): set_light_backlight: 81
,D/qdlights(  843): set_light_backlight: 78
,D/qdlights(  843): set_light_backlight: 74
,D/qdlights(  843): set_light_backlight: 71
,D/qdlights(  843): set_light_backlight: 68
,D/qdlights(  843): set_light_backlight: 64
,D/qdlights(  843): set_light_backlight: 61
,D/qdlights(  843): set_light_backlight: 58
,D/qdlights(  843): set_light_backlight: 54
,D/qdlights(  843): set_light_backlight: 51
,D/qdlights(  843): set_light_backlight: 48
,D/qdlights(  843): set_light_backlight: 44
,D/qdlights(  843): set_light_backlight: 41
,D/qdlights(  843): set_light_backlight: 38
,D/qdlights(  843): set_light_backlight: 34
,D/qdlights(  843): set_light_backlight: 31
,D/qdlights(  843): set_light_backlight: 28
,D/qdlights(  843): set_light_backlight: 24
,D/qdlights(  843): set_light_backlight: 21
,D/qdlights(  843): set_light_backlight: 18
,D/qdlights(  843): set_light_backlight: 14
,D/qdlights(  843): set_light_backlight: 11
,D/qdlights(  843): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 155232058644; DSPS: 5185333; Offset : -3021273289
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  843): ALS enabled for SRE
D/PowerManagerServiceEx(  843): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35574 ms ago)
I/PowerManagerService(  843): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  843): ALS enabled for SRE
D/PowerManagerServiceEx(  843): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35586 ms ago)
,W/ContextImpl(  843): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  843): Sleeping (uid 1000)...
D/LPWGController(  843): [updateScreenState] screen on = false
D/LPWGController(  843): disable proximity sensor
,D/LPWGController(  843): enable proximity sensor
I/SensorManager(  843): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2e7b7948] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  843): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  843): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  843): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  843): activate: handle is 48, enable
V/sensors_hal_Ctx(  843): activate sensors is 1400000000000
D/sensors_hal_Thresh(  843): enable: handle=48
I/sensors_hal_SAM(  843): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  843): waitForResponse: timeout=1000
V/sensors_hal_SAM(  843): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  843): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  843): enable: Received response: 0
D/PowerManagerServiceEx(  843): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35627 ms ago)
I/Adreno-EGL(  843): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  843): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  843): Build Date: 03/02/15 Mon
I/Adreno-EGL(  843): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  843): Remote Branch: 
I/Adreno-EGL(  843): Local Patches: 
I/Adreno-EGL(  843): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (983 us)
,I/Sensors (  430): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  843): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  843): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  843): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
,D/sensors_hal_Thresh(  843): processInd: handle 48, count=1
V/sensors_hal_Thresh(  843): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  843): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  843): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  843): poll: count: 256
I/sensors_hal_Ctx(  843): poll: released wakelock sensor_ind
D/sensors_hal_Util(  843): waitForResponse: timeout=0
D/LPWGController(  843): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  843): current mode = 1  value = 1 1
I/LPWGController(  843): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  843): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  843): set_light_backlight: 0
,I/SensorManager(  843): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  843): activate: handle is 46, disable
V/sensors_hal_Ctx(  843): activate sensors is 1000000000000
D/sensors_hal_LP2(  843): enable: handle=46
D/sensors_hal_LP2(  843): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  843): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  843): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
,D/sensors_hal_LP2(  843): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  843): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/ActivityManager(  843): Display changed displayId=0
,D/DSDPConnection( 1780): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  843): Excessive delay in setPowerMode(): 230ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  843): Got set_interactive hint
,D/KeyguardViewMediator( 1372): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1372): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1372): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1372): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1372): unregisterProximitySensor
,D/StatusBarWindowView( 1372): onScreenTurnedOff why = 3
D/WifiServerServiceExt(  843): sendKtScanInterval  mRtspPlay : false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=on, calling pid 843
D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=on
I/WifiServerServiceExt(  843): set CMD_KT_SCAN_INTERVAL
V/voice   (  277): voice_set_parameters: enter: screen_state=on
V/compress_voip(  277): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  277): voice_extn_compress_voip_set_parameters: exit
V/voice   (  277): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  277): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  277): platform_set_parameters: exit with code(0)
,V/lge_audio_loopback(  277): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  277): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  277): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_ON
D/GpsLocationProvider(  843): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/SplitWindow(  843): check instance of lgWin Window{2989c7c7 u0 SearchPanel}
,I/QCNEJ   ( 1913): |CORE| sendScreenState: state:true
,D/InputDispatcher(  843): Window went away: Window{4e30249 u0 SearchPanel}
,I/[SystemUI]Clock( 1372): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
,I/LEDService( 1875): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1875): stopPatternFlashing()
,I/Cliptray Service( 1875): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1875): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1875): lockStatus = 0
I/LEDService( 1875): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1875): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1852): action : android.intent.action.SCREEN_ON
I/LEDService( 1875): updateLightsLocked : turn off led
D/qdlights( 1875): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1875): RESTART MSG
D/NfcServiceNXP( 1852): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1852): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1852): isRequireNfcCRouting() return true
D/LNfcService( 1852): isHCERoutingtoHost() return : true
D/NfcService( 1852): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1852): mEnableLPD: true
D/NfcService( 1852): mEnableReader: false
D/NfcService( 1852): mEnableHostRouting: true
D/NfcService( 1852): newParams.techmask= mTechMask: default
D/NfcService( 1852): mEnableLPD: true
D/NfcService( 1852): mEnableReader: false
D/NfcService( 1852): mEnableHostRouting: true
D/NfcService( 1852): screenState= 3
D/NfcService( 1852): Discovery configuration equal, not updating.
D/Ulp_jni (  843): JNI:system_update. Event-0
,I/Sensors (  430): sns_pwr.c(301):releasing wakelock
,I/art     ( 1752): Explicit concurrent mark sweep GC freed 44385(2MB) AllocSpace objects, 9(144KB) LOS objects, 39% free, 14MB/23MB, paused 1.405ms total 117.942ms
,V/PhoneApp( 1780): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2624): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:15:39
,D/WeatherService( 2624): 2 : ACTION screen on
D/WeatherService( 2624): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2624): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2624): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:15:39
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): ACTION_SCREEN_ON
D/AppCleanupService( 4052): android.intent.action.SCREEN_ON
,V/AudioFlinger(  277): setParameters(): io 0, keyvalue screen_state=off, calling pid 843
,D/audio_hw_primary(  277): adev_set_parameters: enter: screen_state=off
,V/voice   (  277): voice_set_parameters: enter: screen_state=off
V/compress_voip(  277): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  277): voice_extn_compress_voip_set_parameters: exit
V/voice   (  277): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  277): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  277): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  277): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  277): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  277): adev_set_parameters: exit with code(0)
D/WifiController(  843): CMD_SCREEN_OFF 
D/WifiController(  843): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_OFF
D/GpsLocationProvider(  843): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1913): |CORE| sendScreenState: state:false
I/LEDService( 1875): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1875): stopPatternFlashing()
D/qdlights( 1875): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1875): clear
I/LEDService( 1875): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1875): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1875): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1875): updateLightsLocked : turn on led
E/LEDService( 1875): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
D/LNfcService( 1852): action : android.intent.action.SCREEN_OFF
E/LEDService( 1875): Can't handle this request of patternId:0
D/LEDHandler( 1875): RESTART MSG
,D/NfcServiceNXP( 1852): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1951): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1780): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2624): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:15:39
D/WeatherService( 2624): 2 : ACTION screen off
,D/WeatherService( 2624): 2 : TimeTick Receiver Unregister
D/WeatherService( 2624): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:15:39
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  843): ACTION_SCREEN_OFF
D/AppCleanupService( 4052): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4052): AppUsageStatsSaveTask
E/NxpNfcJni( 1852): getReconnectState = 0x0
,D/LCardEmulationManager( 1852): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1852): getDefaultRoute
D/LNfcService( 1852): isRequireNfcCRouting() return true
D/LNfcService( 1852): isHCERoutingtoHost() return : true
D/NfcService( 1852): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1852): mEnableLPD: true
D/NfcService( 1852): mEnableReader: false
D/NfcService( 1852): mEnableHostRouting: true
D/NfcService( 1852): newParams.techmask= mTechMask: 0
D/NfcService( 1852): mEnableLPD: true
D/NfcService( 1852): mEnableReader: false
D/NfcService( 1852): mEnableHostRouting: true
D/NfcService( 1852): screenState= 1
E/NxpNfcJni( 1852): getReconnectState = 0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1372): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  843): ELAPSED_WAKEUP set : Alarm{3572e1f4 type 2 when 161516 com.android.systemui} when 161516
,D/PhoneUtils( 1780): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1780): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1780): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1780): getCallState : 0
,D/PhoneUtils( 1780): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1780): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1780): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1372): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1372): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 175232818271; DSPS: 5840718; Offset : -3021276603
,I/ClearcutLoggerApiImpl( 2268): disconnect managed GoogleApiClient
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  843): acquireWakeLockInternal: lock=977273687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=843
,V/AlarmManager(  843): ELAPSED_WAKEUP set : Alarm{397abd1d type 2 when 183525 android} when 183525
D/PowerManagerServiceEx(  843): releaseWakeLockInternal: lock=977273687 [*alarm*], flags=0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1752): disconnect managed GoogleApiClient
,D/charger_monitor(  458): init target 500000
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  843): battery changed pluggedType: 2
V/AlarmManager(  843): ELAPSED_WAKEUP set : Alarm{4f8b92 type 2 when 187596 com.google.android.gms} when 187596
,I/PhenotypeConfigurator( 1752): Scheduling Phenotype for one-off execution 4416 seconds from now (1454681770239)
,D/GetConfigurationSnapshotOperation( 1752): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1752): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1752): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  843): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 1752): propertyValue:false
D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/LocationManagerService(  843): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1752): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 1752): propertyValue:false
D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1752): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1752): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  843): android: cancelAsUser(2) by android
,I/NotificationManager( 1752): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  843): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  843): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  843): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  843): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  843): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 195233502846; DSPS: 6496100; Offset : -3021263465
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 215234242475; DSPS: 7151484; Offset : -3021256051
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 235235026217; DSPS: 7806870; Offset : -3021266052
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  458): init target 500000
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  843): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 255235800480; DSPS: 8462256; Offset : -3021285194
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  458): init target 500000
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  843): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 275236481045; DSPS: 9117638; Offset : -3021275886
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 295237253902; DSPS: 9773023; Offset : -3021265759
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  458): init target 500000
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  843): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 315237928529; DSPS: 10428405; Offset : -3021262858
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 335238668522; DSPS: 11083790; Offset : -3021285545
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  843): battery changed pluggedType: 2
,D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  843): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/LocationManagerService(  843): remove cfa178a
D/LocationManagerService(  843): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  843): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  843): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  843): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  843): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  843): acquireWakeLockInternal: lock=977273687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=843
,D/PowerManagerServiceEx(  843): releaseWakeLockInternal: lock=977273687 [*alarm*], flags=0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 355239380181; DSPS: 11739172; Offset : -3021245531
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  843): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 375240413976; DSPS: 12394567; Offset : -3021279618
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 395241068135; DSPS: 13049948; Offset : -3021266250
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 415241806512; DSPS: 13705332; Offset : -3021260894
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  843): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 435242560255; DSPS: 14360717; Offset : -3021269465
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 455243220560; DSPS: 15016099; Offset : -3021280886
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 475243947271; DSPS: 15671483; Offset : -3021286232
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  843): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 495244767524; DSPS: 16326869; Offset : -3021259644
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 515245420901; DSPS: 16982251; Offset : -3021277862
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 535246082821; DSPS: 17637633; Offset : -3021287406
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  843): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 555246841720; DSPS: 18293017; Offset : -3021260852
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 575247586816; DSPS: 18948402; Offset : -3021278330
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 595248306444; DSPS: 19603785; Offset : -3021260841
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  843): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 615248987217; DSPS: 20259168; Offset : -3021282051
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 635249651949; DSPS: 20914549; Offset : -3021258370
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 655250518765; DSPS: 21569938; Offset : -3021276355
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  843): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 675251200476; DSPS: 22225320; Offset : -3021265901
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 695251925104; DSPS: 22880704; Offset : -3021273878
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 715252650357; DSPS: 23536088; Offset : -3021281098
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  843): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 735253339359; DSPS: 24191470; Offset : -3021263066
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 755254057477; DSPS: 24846854; Offset : -3021277552
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 775254761271; DSPS: 25502237; Offset : -3021275819
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 795255429285; DSPS: 26157619; Offset : -3021278801
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 815256162454; DSPS: 26813003; Offset : -3021278679
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 835256903487; DSPS: 27468387; Offset : -3021269730
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  843): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 855257584730; DSPS: 28123769; Offset : -3021259612
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 875258310556; DSPS: 28779153; Offset : -3021266521
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 895258970287; DSPS: 29434535; Offset : -3021278307
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  843): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 915259741426; DSPS: 30089920; Offset : -3021269847
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 935260696315; DSPS: 30745311; Offset : -3021261211
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  843): acquireWakeLockInternal: lock=977273687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=843
,V/AlarmManager(  843): ELAPSED_WAKEUP set : Alarm{a4dfd42 type 2 when 952277 com.android.bluetooth} when 952277
D/PowerManagerServiceEx(  843): releaseWakeLockInternal: lock=977273687 [*alarm*], flags=0x0
,W/bt-smp  ( 2062): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2062): Plain text(LSB ~ MSB) = 0e 36 7a 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2062): Encrypted text(LSB ~ MSB) = ea 0f 59 8e 77 44 1c f3 43 e4 5f bf 8c 15 2f dd 
W/bt-btm  ( 2062): Stopping oneshot timer
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 955261421775; DSPS: 31400695; Offset : -3021268251
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  843): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 975262120518; DSPS: 32056078; Offset : -3021271205
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  843): acquireWakeLockInternal: lock=977273687, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=843
,V/AlarmManager(  843): ELAPSED_WAKEUP set : Alarm{96b2153 type 2 when 992578 com.google.android.gms} when 992578
D/PowerManagerServiceEx(  843): releaseWakeLockInternal: lock=977273687 [*alarm*], flags=0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 995262919156; DSPS: 32711464; Offset : -3021266492
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1015263678993; DSPS: 33366849; Offset : -3021269152
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  843): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1035264392214; DSPS: 34022232; Offset : -3021257809
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1055265142154; DSPS: 34677617; Offset : -3021270574
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1075265895584; DSPS: 35333002; Offset : -3021280369
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  843): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1095266642972; DSPS: 35988386; Offset : -3021265378
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1115267375985; DSPS: 36643770; Offset : -3021264682
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1135268100821; DSPS: 37299154; Offset : -3021272346
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  843): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1155268820761; DSPS: 37954538; Offset : -3021284750
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1175269539764; DSPS: 38609921; Offset : -3021267859
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1195270487570; DSPS: 39265312; Offset : -3021266229
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/HeadsetStateMachine( 2062): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1913): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1913): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1875): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1875): Battery Level Remaining: 100%
D/LEDHandler( 1875): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  843): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  843): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  843): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1215271172718; DSPS: 39920695; Offset : -3021282621
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  843): User[0] Flushing usage stats to disk
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1235271924742; DSPS: 40576079; Offset : -3021263175
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1255272662129; DSPS: 41231463; Offset : -3021258079
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  458): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1875): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1275273336080; DSPS: 41886845; Offset : -3021255828
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 7899): 
D/AndroidRuntime( 7899): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7899): CheckJNI is OFF
D/AndroidRuntime( 7899): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  843): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  843): Killing 5562:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  843): Skipping PackageSetting{304396ff com.example.hello/10317} due to missing metadata
I/WindowState(  843): WIN DEATH: Window{3766208 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  843): Focus left window: Window{3766208 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  843): Window went away: Window{3766208 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  843):   Force finishing activity ActivityRecord{122a3219 u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  843): Display changed displayId=0
D/DSDPConnection( 1780): Display #0 changed.
W/ActivityManager(  843): Spurious death for ProcessRecord{3ff6aa90 5562:com.test.thalitest/u0a316}, curProc for 5562: null
I/ActivityManager(  843): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/art     ( 2026): Explicit concurrent mark sweep GC freed 22839(1348KB) AllocSpace objects, 5(119KB) LOS objects, 40% free, 12MB/21MB, paused 1.112ms total 76.812ms
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1951): [Launcher.java:5203:onStart()]onStart
I/InputReader(  843): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1913): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1752): Ignoring removeGeofence because network location is disabled.
W/System.err( 3594): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3594): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3594): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3594): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3594): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3594): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3594): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3594): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3594): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3594): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3594): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3594): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 2268): Explicit concurrent mark sweep GC freed 11067(626KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 15MB/20MB, paused 1.164ms total 108.197ms
I/[LGHome]EVENT( 1951): [Launcher.java:776:onResume()]onResume
I/ActivityManager(  843): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7930 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1951): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1951): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1951): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]EVENT( 1951): [Launcher.java:929:onResume()]onResume end
I/Activity( 1951): Activity.onPostResume() called 
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]EVENT( 1951): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1951): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1951): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/art     (  843): Explicit concurrent mark sweep GC freed 53031(3MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 23MB/35MB, paused 2.499ms total 221.018ms
I/art     (  843): WaitForGcToComplete blocked for 190.663ms for cause Explicit
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework](  843): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  843): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  843): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  843): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  843): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1fbeaff9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  843): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  843): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  843): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  843): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  843): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  843): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1fbeaff9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  843): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  843): Focus entered window: Window{3962ba8c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1372): handleShortcutListChanged...
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]EVENT( 1951): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1951): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1951): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1951): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourcesManager( 7930): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7930): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/ResourcesManager( 7930): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1951): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1951): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
W/InputMethodManagerService(  843): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
D/KeyguardModel( 1372): handleShortcutListChanged...
W/InputMethodManagerService(  843): Got RemoteException sending setActive(false) notification to pid 5562 uid 10316
D/administrator(  843): Handling package changes for user 0
I/LGEmail ( 7930): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[LGHome]Launcher.Model( 1951): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1951): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LGEmail ( 7930): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/Timeline(  843): Timeline: Activity_windows_visible id: ActivityRecord{973139c u0 com.lge.launcher2/.Launcher t221} time:1294785
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
W/IInputConnectionWrapper( 1951): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1951): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1951): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1627): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1951): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1951): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1951): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1951): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1951): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/NotificationService(  843): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  843): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  843): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
D/TaskPersister(  843): removeObsoleteFile: deleting file=222_task.xml
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
W/Resources( 1951): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1951): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1951): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1951): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1951): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1951): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1951): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1951): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1951): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1951): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1951): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1951): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/art     (  843): Explicit concurrent mark sweep GC freed 8115(469KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 13.622ms total 399.660ms
D/LCardEmulationManager( 1852): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1852): getDefaultRoute
I/PackageChangeReceiver( 7930): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/AppUp4:PreloadHelper( 7412): added Exclude : com.test.thalitest
D/AndroidRuntime( 7899): Shutting down VM
I/ActivityManager(  843): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7957 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  843): Killing 7437:com.android.gallery3d/u0a23 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1951): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1951): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1951): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1951): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1951): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
W/libprocessgroup(  843): failed to open /acct/uid_10023/pid_7437/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1951): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1951): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7957): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7957): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 7957): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7957): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7957): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/sensors_hal_Time(  843): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  843): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  843): tsOffsetIs: Apps: 1295274040761; DSPS: 42542228; Offset : -3021252973
I/[LgeWidgetLib]LgeAppWidgetHostView( 1951): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/IndexDatabaseHelper( 7957): Using schema version: 115
I/IndexDatabaseHelper( 7957): Index is fine
E/[LgeWidgetLib]LgeAppWidgetHostView( 1951): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1951): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1951): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline( 1951): Timeline: Activity_idle id: android.os.BinderProxy@3b89b6b time:1295351
I/art     ( 1951): Explicit concurrent mark sweep GC freed 27568(1495KB) AllocSpace objects, 19(2MB) LOS objects, 39% free, 15MB/25MB, paused 887us total 52.741ms
D/PackageIntentReceiver( 7957): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 7957): Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
D/HideNavigationAppsReceiver( 7957): replacing : false
D/HideNavigationAppsReceiver( 7957): Delete mPackageMame : com.test.thalitest
D/ButtonCombinationReceiver( 7957): Receive package name : com.test.thalitest
D/ButtonCombinationReceiver( 7957): replacing : false

```
