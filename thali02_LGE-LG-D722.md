#### Test 58135655a685cd3_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,D/ChimeraCfgMgr( 5620): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5620): Loading module APK com.google.android.play.games
--------- beginning of system
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  475): init target 500000
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
W/MainApplication( 5235): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/charger_monitor(  475): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/MainApplication( 5235): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/NativeLibraryUtils( 5620): Install completed successfully. count=14 extracted=0
I/art     ( 5620): CheckpointMarkThreadRoots callback created = 0xaaf48db0
I/art     ( 5620): CheckpointMarkThreadRoots callback created = 0xaaf48d90
D/ChimeraCfgMgr( 5620): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5620): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 5620): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 5620): Submit a task: k
D/ChimeraCfgMgr( 5620): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5620): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 5620): Processing package: com.test.thalitest
D/GassUtils( 5620): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5620): Found info for package com.test.thalitest in db.
I/PeopleDatabaseHelper( 5620): cleanUpNonGplusAccounts done.
D/WearableService( 1732): callingUid 10006, callindPid: 1732
D/LocationInitializer( 5620): Restart initialization of location
E/MDM     ( 1732): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/BaseAppContext( 5620): Using Auth Proxy for data requests.
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
D/AndroidRuntime( 5662): 
D/AndroidRuntime( 5662): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/Icing   ( 5620): Storage manager: low false usage 1.70MB avail 2.37GB capacity 4.06GB
D/AndroidRuntime( 5662): CheckJNI is OFF
I/ActivityManager(  971): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5690 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/BaseAppContext( 5620): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 5620): Using Auth Proxy for data requests.
I/art     ( 5620): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5620): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/BaseAppContext( 5620): Using Auth Proxy for data requests.
W/BaseAppContext( 5620): Using Auth Proxy for data requests.
W/BaseAppContext( 5620): Using Auth Proxy for data requests.
W/BaseAppContext( 5620): Using Auth Proxy for data requests.
W/BaseAppContext( 5620): Using Auth Proxy for data requests.
E/Icing   ( 5620): Array storage bad crc 1773741963 vs 1204220394
E/Icing   ( 5620): Array storage bad crc 1118736210 vs 645066901
E/Icing   ( 5620): Array storage bad crc 1679672019 vs 3701581238
E/Icing   ( 5620): Trie mmap suffix failed
I/art     ( 5470): Explicit concurrent mark sweep GC freed 7917(399KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 874us total 38.417ms
I/art     (  971): Explicit concurrent mark sweep GC freed 20735(998KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 3.609ms total 173.464ms
D/AndroidRuntime( 5662): Calling main entry com.android.commands.am.Am
W/Icing   ( 5620): Docstore bad crc 0x24bbd82d vs 0x2f8b0bdc
I/ActivityManager(  971): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
D/ActivityManager(  971): setTaskToReturnTo : TaskRecord{3dbfbdfe #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  971): setTaskToReturnTo : TaskRecord{3dbfbdfe #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  971): AppWindowTokenEx init.. 
D/ContextHelper(  971): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  971): Focus left window: Window{10285e1c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5662): Shutting down VM
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
D/SplitWindow(  971): check instance of lgWin Window{1b783a98 u0 Starting com.test.thalitest}
W/IcingInternalCorpora( 5620): getNumBytesRead when not calculated.
E/Icing   ( 5620): Array storage bad crc 3273046437 vs 0
E/Icing   ( 5620): Trie mmap node failed
I/ActivityManager(  971): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5735 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
,I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1960): Closing mic
I/WindowStateAnimator(  971): Starting window displayed
I/SystemUI[Framework](  971): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx(  971): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  971): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  971): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  971): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@26ab6a9d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  971): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/MicrophoneInputStream( 1960): mic_close com.google.android.apps.gsa.speech.audio.u@3246c716
V/AudioRecord( 1960): stop()
D/AudioRecord( 1960): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
D/BarTransitions( 1372): draw background and invalidate : color = a000000
V/AudioFlinger(  279): Record stopped OK
V/AudioPolicyManager(  279): stopInput() input 17
V/AudioPolicyService(  279): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  279): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  279): ThreadBase::setParameters() routing=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
D/BarTransitions( 1372): draw background and invalidate : color = c0c0c0c
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb3848000
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  279): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  279): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  279): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  279): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  279): disable_audio_route: exit
E/audio_hw_primary(  279): disable_snd_device: enter 144
D/hardware_info(  279): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  279): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  279): stop_input_stream: exit: status(0)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  279): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  279): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  279): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyService(  279): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  279): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  279): setParameters(): io 17, keyvalue hotword_active=0, calling pid 279
V/AudioFlinger(  279): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  279): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  279): in_set_parameters: exit: status(0)
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb3848000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioRecord( 1960): stop()
V/AudioRecord( 1960): stop()
V/AudioRecord( 1960): stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 17
V/AudioPolicyManager(  279): closeInput(17)
V/AudioFlinger(  279): releasing 16 from 1960 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/AudioFlinger(  279): closeInput() 17
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): ThreadBase::exit
V/AudioSystem( 3246): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioSystem(  971): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): RecordThread 0xb3848000 exiting
V/AudioSystem( 2035): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1960): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2108): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  279): removeClient_l() pid 1960, calling pid 279
I/HotwordRecognitionRnr( 1960): Stopping hotword detection.
I/HotwordRecognitionRnr( 1960): Hotword detection finished
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ContextHelper( 5735): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/Gmail   ( 5690): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5690): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/WebViewFactory( 5735): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/LibraryLoader( 5735): Time to load native libraries: 2 ms (timestamps 3954-3956)
I/LibraryLoader( 5735): Expected native library version number "",actual native library version number ""
E/Gmail   ( 5690): Error finding the version of the Email provider.....
E/Gmail   ( 5690): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5690): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5690): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5690): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5690): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5690): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5690): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5690): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5690): We do not support migrating this version of the Email provider.
W/ActivityManager(  971): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/WebViewChromiumFactoryProvider( 5735): Binding Chromium to main looper Looper (main, tid 1) {384538be}
I/Gmail   ( 5690): Observing account changes for notifications
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/LibraryLoader( 5735): Expected native library version number "",actual native library version number ""
I/chromium( 5735): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/ChimeraCfgMgr( 5620): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5620): Module APK com.google.android.play.games already loaded
I/Gmail   ( 5690): getAccountsCursor
I/BrowserStartupController( 5735): Initializing chromium process, singleProcess=true
W/art     ( 5735): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5735): ApplicationContext is null in ApplicationStatus
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  971): Killing 5397:com.android.gallery3d/u0a23 (adj 15): empty #11
W/chromium( 5735): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5735): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5735): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5735): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5735): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5735): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5735): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5735): Remote Branch: 
I/Adreno-EGL( 5735): Local Patches: 
I/Adreno-EGL( 5735): Reconstruct Branch: 
W/libprocessgroup(  971): failed to open /acct/uid_10023/pid_5397/cgroup.procs: No such file or directory
I/Icing   ( 5620): updateResources: need to parse f{com.google.android.gms}
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
V/AudioPolicyService(  279): registerClient() client 0xb57e9fa0, uid 10316
D/BluetoothManagerService(  971): Message: 20
D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bbf58a4:true
D/BluetoothAdapterService(580395722)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@25234170
V/DownloadManager( 3194): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@8b986f7 on behalf of 5620
,W/InstanceID/Rpc( 5620): Found 10006
,W/InstanceID/Rpc( 5620): Found 10006
I/art     ( 5620): Background sticky concurrent mark sweep GC freed 12133(947KB) AllocSpace objects, 10(160KB) LOS objects, 6% free, 13MB/14MB, paused 6.567ms total 94.267ms
,I/ActivityManager(  971): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5802 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 24.066ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 21.107ms
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.905ms
,W/art     ( 5735): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5735): onDetachedFromWindow called when already detached. Ignoring
,V/DownloadManager( 3194): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@1827e964 on behalf of 5620
V/DownloadManager( 3194): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@197307cd on behalf of 5620
D/SystemWebViewEngine( 5735): CordovaWebView is running on device made by: LGE
,I/Gmail   ( 5690): notifyAccountChanged
I/Gmail   ( 5690): getAccountsCursor
W/art     ( 5735): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5735): Attempt to remove local handle scope entry from IRT, ignoring
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5690): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5690): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5690): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5690): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Activity( 5735): Activity.onPostResume() called 
,D/OpenGLRenderer( 5735): Render dirty regions requested: true
I/OpenGLRenderer( 5735): Initialized EGL, version 1.4
,D/PhoneMonitor( 5802): Register our PhoneStateListener
D/OpenGLRenderer( 5735): Enabling debug mode 0
D/Atlas   ( 5735): Validating map...
,D/SplitWindow(  971): check instance of lgWin Window{3a670196 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5735): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/Icing   ( 5620): Internal init done: storage state 0
I/ActivityManager(  971): Killing 5416:com.android.contacts/u0a18 (adj 15): empty #11
,D/PhoneMonitor( 5802): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/InputDispatcher(  971): Focus entered window: Window{3a670196 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/NotificationManager( 5620): com.google.android.gms: cancel(10436) by com.google.android.gms
,W/libprocessgroup(  971): failed to open /acct/uid_10018/pid_5416/cgroup.procs: No such file or directory
V/TelephonyAutoProfiling( 5802): [loadFeatureFromXml] *** start feature loading from xml
,W/InputMethodManagerService(  971): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/TelephonyAutoProfiling( 5802): [parse] Load xml
V/TelephonyAutoProfiling( 5802): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 5802): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/ActivityManager(  971): Displayed com.test.thalitest/.MainActivity: +1s321ms
I/Timeline(  971): Timeline: Activity_windows_visible id: ActivityRecord{26fb795f u0 com.test.thalitest/.MainActivity t222} time:84759
I/Icing   ( 5620): 22 corpora need re-polling
,I/Timeline( 5735): Timeline: Activity_idle id: android.os.BinderProxy@8e8aea5 time:84788
,I/Icing   ( 5620): Post-init done
I/CheckinService( 5620): Checkin interval check for package: unspecified last checkin: 1454591066636 min interval config: 0 actual interval: 4897
,D/PhoneMonitor( 5802): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/InitAlarmsService( 3814): Clearing and rescheduling alarms.
,I/Gmail   ( 5690): getAccountsCursor
I/art     ( 5620): Background partial concurrent mark sweep GC freed 27042(1682KB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 12MB/21MB, paused 11.871ms total 146.802ms
I/CheckinService( 5620): Disabling old GoogleServicesFramework version
,D/CalendarProvider2( 5513): Scheduling check of next Alarm
D/CalendarProvider2( 5513): SCHEDULE_ALARM_REMOVE
,W/BindingManager( 5735): Cannot call determinedVisibility() - never saw a connection for the pid: 5735
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5844 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 5620): Checking schedule, now: 1454591071756 next: 1454591096599
,I/CheckinService( 5620): active receiver: disabled
,W/ResourcesManager( 5844): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/JsMessageQueue( 5735): Set native->JS mode to OnlineEventsBridgeMode
,I/Icing   ( 5620): Indexing 1612944C7007A012B1C904336C8580EC6DBD4F91 from com.google.android.music
I/ActivityManager(  971): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=5863 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Babel_SMS( 5844): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5844): MmsConfig.loadMmsSettings
I/Babel_SMS( 5844): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5844): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5844): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5844): MmsConfig.loadFromResources
E/Babel_SMS( 5844): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5844): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5844): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5844): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5844): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5844): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 5844): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5844): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5844): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5844): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5844): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5844): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5844): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5844): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5844): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5844): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5844): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5844): found sensor: Motion Accel, handle=46
I/MusicStore( 5863): Database version: 120
,I/ActivityManager(  971): Process com.android.calendar (pid 3814) has died
W/art     ( 5844): Suspending all threads took: 5.560ms
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5863): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/art     ( 5844): CheckpointMarkThreadRoots callback created = 0xb042d8e0
,W/Settings( 5844): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/jxcore_app_log( 5735): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426156032
,I/Babel_Crash( 5844): startup - clean
I/Babel   ( 5844): deleted: false for 0
,I/art     ( 5844): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,I/chromium( 5735): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5863): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5863): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5863): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5863): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/CalendarProvider2( 5513): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5513): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,V/JNIHelp ( 5863): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 5735): CheckpointMarkThreadRoots callback created = 0xb051dd90
,I/art     ( 5735): CheckpointMarkThreadRoots callback created = 0xb051dd60
,W/ActivityThread( 5863): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5863): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@eadc5e1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5863): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5863): GMSCore installation verified
,I/ConfigStore( 5863): Config Database version: 1
W/AudioCapabilities( 5844): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5844): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5844): Unsupported mime audio/g726
W/AudioCapabilities( 5844): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5844): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5844): Unsupported mime video/mjpg
I/art     ( 5863): Background sticky concurrent mark sweep GC freed 23556(1175KB) AllocSpace objects, 4(64KB) LOS objects, 8% free, 10MB/11MB, paused 13.336ms total 100.376ms
,W/VideoCapabilities( 5844): Unsupported mime video/theora
,W/AudioCapabilities( 5844): Unsupported mime audio/evrc
W/AudioCapabilities( 5844): Unsupported mime audio/qcelp
,W/VideoCapabilities( 5844): Unrecognized profile 2130706433 for video/avc
I/Icing   ( 5620): Indexing done 1612944C7007A012B1C904336C8580EC6DBD4F91
I/Icing   ( 5620): Indexing 1F53EECCEBEB5877C2973BC154C132777EB605A6 from com.google.android.apps.books
W/ActivityManager(  971): Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{19838f7c 5620:com.google.android.gms/u0a6} (pid=5620, uid=10006) that is not exported from uid 10046
W/AudioCapabilities( 5844): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5844): Unsupported mime audio/qcelp
W/AudioCapabilities( 5844): Unsupported mime audio/evrc
E/Icing   ( 5620): Cursor call threw an exception: Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{19838f7c 5620:com.google.android.gms/u0a6} (pid=5620, uid=10006) that is not exported from uid 10046
I/Icing   ( 5620): Indexing done 1F53EECCEBEB5877C2973BC154C132777EB605A6
,E/Icing   ( 5620): Aborting indexing of corpus volumes__id
I/Icing   ( 5620): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
W/VideoCapabilities( 5844): Unsupported mime video/mp4v-esdp
,I/MediaRouter( 5863): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 5863): type=WIFI subType= reason=null isConnected=true
I/VideoCapabilities( 5844): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5844): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5844): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5844): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5844): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  971): Process com.lge.bnr (pid 5235) has died
,I/art     (  971): Explicit concurrent mark sweep GC freed 20537(1008KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 5.138ms total 232.035ms
I/NetworkMonitor( 5863): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 5863): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/vclib   ( 5844): onServiceConnected
I/GoogleURLConnFactory( 5863): Using platform SSLCertificateSocketFactory
W/Babel   ( 5844): Attempted to change video mute state without an active call.
,I/NotificationManager( 5863): com.google.android.music: cancel(1061) by com.google.android.music
,I/NotificationManager( 5844): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5844): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5844): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 5735): Background sticky concurrent mark sweep GC freed 30954(3MB) AllocSpace objects, 11(2MB) LOS objects, 30% free, 13MB/19MB, paused 7.085ms total 51.052ms
,I/ActivityManager(  971): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5909 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AudioManager( 5147): getMode name:com.lge.qremote
,I/AudioManager( 5147): getMode name:com.lge.qremote
,I/AudioManager( 5147): getMode name:com.lge.qremote
,I/AudioManager( 5147): getMode name:com.lge.qremote
,I/AudioManager( 5147): getMode name:com.lge.qremote
V/JNIHelp ( 5844): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
E/MDM     ( 1732): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5620): Restart initialization of location
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5147): getMode name:com.lge.qremote
D/UEI.SmartControl( 5909): Quickset Services start...
,W/GCoreFlp( 1732): No location to return for getLastLocation()
I/UEI.SmartControl( 5909): Manufacture = LGE
W/FusedLocationProvider( 1732): location=null
,D/UEI.SmartControl( 5909): File observer start...
I/AudioManager( 5147): getMode name:com.lge.qremote
,E/UEI.SmartControl( 5909): IR Port is disabled: false
D/UEI.SmartControl( 5909): Starting file observer...
D/UEI.SmartControl( 5909): Extracting JNI libs...
D/UEI.SmartControl( 5909): --- this system supports 32-bit or 64-bit only
W/System  ( 5844): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5844): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5844): com.google.android.talk: cancel(8) by com.google.android.talk
,D/Icing   ( 5620): Loaded CLD2 Version V2.0 - 20141016
,I/ActivityManager(  971): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5936 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/Icing   ( 5620): Indexing B2F716F68058802BDD4E913C0921699984AB1871 from com.google.android.videos
,D/UEI.SmartControl( 5909): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5909): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5909): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager(  971): Process com.google.android.apps.docs (pid 5487) has died
,I/UEI.SmartControl( 5909): --- Selecting new region: 2
,I/UEI.SmartControl( 5909): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5909): Platform has CIR...
D/UEI.SmartControl( 5909): NO CIR support, need to check package...
I/UEI.SmartControl( 5909): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5909): QS Service created
I/ActivityManager(  971): Start proc com.google.android.videos for content provider com.google.android.videos/.search.IcingContentProvider: pid=5953 uid=10099 gids={50099, 9997, 3003, 1028, 1015, 3002} abi=armeabi
,E/UEI.SmartControl( 5909): QS start get config
,I/AppUp4:AppBoxCP( 5936): onCreate
,W/AppUp4:DB( 5936):  [AppBoxDatabaseHelper] construct
D/UEI.SmartControl( 5909): Loading JNI Libs...
D/UEI.SmartControl( 5909):  configuring local db...
W/ResourcesManager( 5953): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,I/AppUp4:DB( 5936):  setFingerPrint start
I/AppUp4:DB( 5936):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5936):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5936):  SDK version = 0
I/AppUp4:DB( 5936):  beforefinger == newfinger no write in DB
,I/ActivityManager(  971): Process com.google.android.apps.plus (pid 5542) has died
,D/AppUp4:AppBoxApplication( 5936): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5936): onReceive
I/AppUp4:CustModeStarterReceiver( 5936): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5936): Context : android.app.ReceiverRestrictedContext@10d4840
D/AppUp4:CustFacade( 5936): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5936): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5936): begin check event
I/AppUp4:CustModeStarterReceiver( 5936): Event For Nothing, skip.
I/ActivityManager(  971): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5974 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/UEI.SmartControl( 5909):  ---- Has DB8: true
,D/UEI.SmartControl( 5909): QS start statue = true Error code = 0
D/UEI.SmartControl( 5909): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5909): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5909): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5909): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5909): IrrcClient ++ 
D/irrcClient( 5909): getIrrcService ++ 
D/irrcClient( 5909): getIrrcService -- 
D/irrcClient( 5909): IrrcClient -- 
W/irrc_jni( 5909): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5909): Services init done
,I/UEI.SmartControl( 5909): Device manager: loading config....
D/UEI.SmartControl( 5909): Config is loaded...
,I/ActivityManager(  971): Process com.lge.lockscreensettings (pid 5435) has died
D/UEI.SmartControl( 5909): QS Service init finished
D/UEI.SmartControl( 5909): QS Service version name: 0.1.73
D/UEI.SmartControl( 5909): QS Service version code: 1073
,D/UEI.SmartControl( 5909): Service requested: Control
D/UEI.SmartControl( 5909): Internal service binding...
,W/ResourcesManager( 5974): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5974): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5909): -----IControl: 11
D/UEI.SmartControl( 5909): Caller: com.lge.qremote
W/ResourcesManager( 5974): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5909): ------------ IControl registerCallback...
D/UEI.SmartControl( 5909):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5909): Registering callback...
I/UEI.SmartControl( 5909): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5909): -----IControl: 19
D/UEI.SmartControl( 5909): Caller: com.lge.qremote
,I/UEI.SmartControl( 5909): Registering Services Ready callback...
I/UEI.SmartControl( 5909): Notify client services are ready...
D/UEI.SmartControl( 5909): -----IControl: 8
D/UEI.SmartControl( 5909): Caller: com.lge.qremote
,W/jxcore-log( 5735): Initializing JXcore engine
,W/jxcore-log( 5735): JXcore engine is ready
I/ActivityManager(  971): Process com.android.vending (pid 5577) has died
,I/AppConfig( 5974): Total System Memory = 906309632
I/GalleryUtils( 5974): Application Heap = 96 MB
,I/AppConfig( 5974): App Tier : NOT_DEF
,D/SystemHelper( 5974): region [EU], country [EU], operator [OPEN], sub-operator []
,I/art     ( 5470): Explicit concurrent mark sweep GC freed 2783(108KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 3.998ms total 46.348ms
,W/Thread-677( 5895): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6314]" dev="sockfs" ino=6314 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-677( 5895): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-677( 5895): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7446]" dev="sockfs" ino=7446 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-677( 5895): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-677( 5895): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-677( 5895): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26921]" dev="sockfs" ino=26921 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,I/ActivityManager(  971): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6013 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/jxcore-log( 5735): Starting JXcore engine
I/ActivityManager(  971): Killing 5452:com.lge.eula/1000 (adj 15): empty #11
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,W/libprocessgroup(  971): failed to open /acct/uid_1000/pid_5452/cgroup.procs: No such file or directory
,I/Icing   ( 5620): Indexing done B2F716F68058802BDD4E913C0921699984AB1871
,I/Icing   ( 5620): Indexing 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9 from com.google.android.gms
W/ResourcesManager( 6013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6013): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6013): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6013): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6013): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/Icing   ( 5620): Indexing done 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9
,I/Icing   ( 5620): Indexing FC5805F301A6400196925772B79FE617968B1409 from com.google.android.videos
W/jxcore-log( 5735): Platform android
W/jxcore-log( 5735): 
,W/jxcore-log( 5735): Process ARCH arm
W/jxcore-log( 5735): 
W/PlayMovies( 5953): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 5953): 
I/Icing   ( 5620): Indexing done FC5805F301A6400196925772B79FE617968B1409
,I/Icing   ( 5620): Indexing 261F31C44790DA98645222D6E4244392E5409193 from com.google.android.gms
I/Icing   ( 5620): Indexing done 261F31C44790DA98645222D6E4244392E5409193
I/Icing   ( 5620): Indexing AC7CA1348821615DDDE9D587591668A8B8E68A6F from com.google.android.googlequicksearchbox
I/ActivityManager(  971): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6037 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/PlayMovies( 5953): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 5953): 
,D/PlayMovies( 5953): PersistentCache.cleanup:94 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/PlayMovies( 5953): 
,D/PlayMovies( 5953): TransferService.onCreate:60 creating transfer service
D/PlayMovies( 5953): 
I/SystemConfig( 6013): BUILD Country: EU
,I/SystemConfig( 6013): BUILD Operator: OPEN
W/AudioCapabilities( 5953): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5953): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5953): Unsupported mime audio/g726
W/AudioCapabilities( 5953): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5953): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5953): Unsupported mime video/mjpg
,W/VideoCapabilities( 5953): Unsupported mime video/theora
W/AudioCapabilities( 5953): Unsupported mime audio/evrc
W/AudioCapabilities( 5953): Unsupported mime audio/qcelp
W/VideoCapabilities( 5953): Unrecognized profile 2130706433 for video/avc
V/AlarmManager(  971): RTC_WAKEUP set : Alarm{1e680ffd type 0 when 1454591075401 com.google.android.googlequicksearchbox} when 1454591075401
,W/AudioCapabilities( 5953): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5953): Unsupported mime audio/qcelp
W/AudioCapabilities( 5953): Unsupported mime audio/evrc
I/Icing   ( 5620): Indexing done AC7CA1348821615DDDE9D587591668A8B8E68A6F
I/Icing   ( 5620): Indexing 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652 from com.google.android.googlequicksearchbox
,W/VideoCapabilities( 5953): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 5953): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager(  971): Process com.google.android.gm (pid 5690) has died
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,D/WVCdm   (  279): Instantiating CDM.
I/WVCdm   (  279): CdmEngine::QueryStatus
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
W/ContextImpl( 5953): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
,W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
I/WVCdm   (  279): L3 Terminate.
I/ActivityManager(  971): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6065 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6013): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6013): existFile = false
I/SystemConfig( 6013): canReadFile = false
I/SystemConfig( 6013): systemFeature RCS result false
D/SystemConfig( 6013): refreshRcsSupport() :false
,I/Icing   ( 5620): Indexing done 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652
I/Icing   ( 5620): Indexing 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D from com.google.android.gm
I/ActivityManager(  971): Start proc com.google.android.gm for content provider com.google.android.gm/.provider.SearchQuery$Provider: pid=6084 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 6037): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/LockScreenSettings( 6065): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/jxcore-log( 5735): JXcore Cordova bridge is ready!
I/jxcore-log( 5735): 
W/jxcore-log( 5735): JXcore engine is started
,D/LockScreenSettings( 6065): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6065): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6065): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6065): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6065): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6108 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 30.021ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.901ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 309us total 25.039ms
,D/Finsky  ( 6037): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/Settings( 6037): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6037): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6037): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3194): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@37e8f882 on behalf of 6037
I/ActivityManager(  971): Killing 5802:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/Finsky  ( 6037): [699] SignatureUtils.faultInOtherSignatures: Will not allow first-party apps signed by test keys
D/Finsky  ( 6037): [699] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.videos
,I/jxcore-log( 5735): Toggling radios to true
I/jxcore-log( 5735): 
,D/BluetoothAdapter( 5735): enable(): BT is already enabled..!
W/ResourcesManager( 6108): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/libprocessgroup(  971): failed to open /acct/uid_10038/pid_5802/cgroup.procs: No such file or directory
,D/WifiServiceImplEx(  971): setWifiEnabled: true pid=5735, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/Finsky  ( 6037): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6037): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 6037): Skipping gmscore version check
D/WifiService(  971): setWifiEnabled: true pid=5735, uid=10316
D/WifiServiceImplEx(  971): disconnect pid=5735, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  971): reconnect pid=5735, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5735): Radios toggled
I/jxcore-log( 5735): 
D/Finsky  ( 6037): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/jxcore-log( 5735): My device name is: LGE-LG-D722
I/jxcore-log( 5735): 
I/Gmail   ( 6084): getAccountsCursor
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2748): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2748): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  971): WifiStateMachine: Leaving Connected state
,D/Finsky  ( 6037): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/WifiConfigStore(  971): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1802): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  971): Killing 5863:com.google.android.music:main/u0a81 (adj 15): empty #11
,D/LGWifiP2pService(  971): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  971): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/Icing   ( 5620): Indexing done 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D
D/DhcpStateMachine(  971): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  275): Clearing all IP addresses on wlan0
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
,I/Icing   ( 5620): Indexing 59716A40DEE00805E4208F1709FD830CA906A723 from com.google.android.music
W/GAV2    ( 6084): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/NativeCrypto( 1732): Read error: ssl=0xb044c600: I/O error during system call, Connection timed out
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xb044c600: I/O error during system call, Broken pipe
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  971): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/ConnectivityService(  971): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  971): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): ValidatedState{ when=-8ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): DefaultState{ when=-18ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): Forcing reevaluation
,D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/ConnectivityService(  971): Default network via Wi-Fi disconnect. stop DSQN
,D/DSQN    (  971): disableDataServiceNotify
D/DSQN    (  971): stop dsqn bin
D/ConnectivityService(  971): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/ActivityManager(  971): Killing 5513:com.android.providers.calendar/u0a14 (adj 15): empty #12
,D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  971): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  971): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  971): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/DhcpStateMachine(  971): StoppedState
,E/lowmemorykiller(  241): Error opening /proc/5863/oom_score_adj; errno=2
,I/ActivityThread( 5620): Removing dead content provider:android.content.ContentProviderProxy@31322629
W/libprocessgroup(  971): failed to open /acct/uid_10081/pid_5863/cgroup.procs: No such file or directory
,W/ActivityManager(  971): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/libprocessgroup(  971): failed to open /acct/uid_10014/pid_5513/cgroup.procs: No such file or directory
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ConnectivityService(  971): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiHS20(  971): hidePasspointNotification off =false
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/Tethering(  971): MasterInitialState.processMessage what=3
V/NetworkPolicy(  971): [LG_RESTRICTED] !!!isConnected  type  :1
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:36.55 DNS addrs= 0.0.0.0, 0.0.0.0, 
E/WifiStateMachine(  971): Start Disconnecting Watchdog 1
D/ConnectivityService(  971): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  971): hidePasspointNotification off =false
E/Icing   ( 5620): Cursor call threw an exception: null
E/Icing   ( 5620): Indexing content provider failed; will retry 3 times
I/Icing   ( 5620): Indexing done 59716A40DEE00805E4208F1709FD830CA906A723
E/Icing   ( 5620): Aborting indexing of corpus albums
I/Icing   ( 5620): Retrying indexing in 300000ms
D/ConnectivityService(  971): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/QCNEJ   ( 1838): |CORE| No family connected
D/ConnectivityService(  971): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/LGWifiP2pService(  971): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  971): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 2748): wlan0: CTRL-EVENT-SCAN-STARTED 
D/DhcpStateMachine(  971): StoppedState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  275): Clearing all IP addresses on wlan0
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:36.562 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/NetworkPolicy(  971): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  971): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  971): Removing idletimer
D/WifiHS20(  971): hidePasspointNotification off =false
D/TelephonyNetworkFactory-1( 1750): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/Settings(  971): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/ConnectivityService(  971): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = -1
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:36.58 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/Gmail   ( 6084): Observing account changes for notifications
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
,E/Gmail   ( 6084): Error finding the version of the Email provider.....
E/Gmail   ( 6084): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6084): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6084): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6084): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6084): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6084): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6084): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6084): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6084): We do not support migrating this version of the Email provider.
I/Gmail   ( 6084): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,D/WifiNetworkAgent(  971): NetworkAgent: NetworkAgent channel lost
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:36.638 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  971): hidePasspointNotification off =false
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WIFI    (  971): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  971):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:36.643 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  971): setSupplicantStateDISCONNECTED
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
,D/WifiServerServiceExt(  971): setSupplicantStateSCANNING
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/InputReader(  971): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/administrator(  971): Handling package changes for user 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
,I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
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
,I/art     (  971): Explicit concurrent mark sweep GC freed 39542(1904KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.538ms total 330.274ms
V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{1fbb1602 type 2 when 89910 com.android.providers.calendar} when 89910
,I/Icing   ( 5620): Not indexing corpus from package com.android.chrome as it has never connected
E/Icing   ( 5620): Aborting indexing of corpus omnibox
,I/Icing   ( 5620): Indexing 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3 from com.google.android.gms
I/UpdateIcingCorporaServi( 1960): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/Icing   ( 5620): Indexing done 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3
I/Icing   ( 5620): Indexing F200CD067697391E5BA8387C554D1EADCF480F28 from com.google.android.gms
,I/ActivityManager(  971): Killing 5909:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5147): android.os.DeadObjectException
,W/System.err( 5147): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5147): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5147): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5147): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5147): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5147): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5147): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5147): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5147): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5147): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5147): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5147): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5147): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5147): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5147): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5147): android.os.DeadObjectException
W/System.err( 5147): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5147): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5147): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5147): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5147): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5147): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5147): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5147): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5147): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5147): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5147): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5147): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5147): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5147): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5147): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/UpdateIcingCorporaServi( 1960): UpdateCorporaTask done [took 94 ms] updated apps [took 94 ms] 
,I/Icing   ( 5620): Indexing done F200CD067697391E5BA8387C554D1EADCF480F28
I/Icing   ( 5620): Indexing 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5 from com.google.android.music
,I/NotificationService(  971): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  971): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  971): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/ResourcesManager(  971): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  971): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/libprocessgroup(  971): failed to open /acct/uid_10089/pid_5909/cgroup.procs: No such file or directory
W/ActivityManager(  971): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  971): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=6172 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/BackupManagerService(  971): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/ActivityManager(  971): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6178 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Process com.android.contacts (pid 6013) has died
,D/PackageBroadcastService( 5620): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
V/BackupManagerService(  971): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
V/BackupManagerService(  971): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@20f794c2
I/PackageBroadcastService( 5620): Null package name or gms related package.  Ignoreing.
,I/AudioManager( 5147): getMode name:com.lge.qremote
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/UEI.SmartControl( 6178): Quickset Services start...
I/UEI.SmartControl( 6178): Manufacture = LGE
D/UEI.SmartControl( 6178): File observer start...
E/UEI.SmartControl( 6178): IR Port is disabled: false
D/UEI.SmartControl( 6178): Starting file observer...
D/UEI.SmartControl( 6178): Extracting JNI libs...
D/UEI.SmartControl( 6178): --- this system supports 32-bit or 64-bit only
,I/ActivityManager(  971): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6223 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2748): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/MusicStore( 6172): Database version: 120
,I/Gmail   ( 6084): notifyAccountChanged
,I/Gmail   ( 6084): getAccountsCursor
I/Gmail   ( 6084): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  971): Process com.android.gallery3d (pid 5974) has died
I/wpa_supplicant( 2748): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
D/UEI.SmartControl( 6178): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
I/Gmail   ( 6084): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/UEI.SmartControl( 6178): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6178): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/LocSvc_java(  971): onReceive
,I/Gmail   ( 6084): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6084): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2748): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2748): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:37.793 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:37.796 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
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
,W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/WifiServiceExtension(  971): setVHTCapabilityType  : false
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  971): setSupplicantStateASSOCIATING
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:37.821 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:37.823 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
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
D/LocationProviderProxy(  971): applying state to connected service
,I/WifiServerServiceExt(  971): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  971): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  971): setSecurityType  : 2
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6172): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:37.868 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:37.869 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/ConnectivityService(  971): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  971): Got NetworkAgent Messenger
D/ConnectivityService(  971): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  971): NetworkAgent connected
,D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
E/WifiConfigStore(  971): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  971): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/UEI.SmartControl( 6178): --- Selecting new region: 2
I/UEI.SmartControl( 6178): -- Running on KitKat(19) and above! JNI will be used.
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Setting iface cfg
E/WifiStateMachine(  971): Start Dhcp Watchdog 2
D/DhcpStateMachine(  971): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  971): WaitBeforeStartState
D/UEI.SmartControl( 6178): Platform has CIR...
,D/UEI.SmartControl( 6178): NO CIR support, need to check package...
I/UEI.SmartControl( 6178): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6178): QS Service created
D/PhoneMonitor( 6223): Register our PhoneStateListener
,I/ActivityManager(  971): Process com.lge.appbox.client (pid 5936) has died
D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  971): setSupplicantStateASSOCIATED
D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WifiServerServiceExt(  971): setSupplicantStateGROUP_HANDSHAKE
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  971): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 34615(2015KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 13MB/22MB, paused 5.433ms total 170.054ms
,E/UEI.SmartControl( 6178): QS start get config
V/SetupWizard( 6223): Connected to Gservices successfully
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6172): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/WifiStateMachine(  971): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  971): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  971): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@12ea3091 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  971): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@12ea3091 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  971): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  971): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  971): DHCP Start wake lock is acquired.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6172): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/CommandListener(  275): Setting iface cfg
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  971): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  971): setSupplicantStateCOMPLETED
,D/WifiServerServiceExt(  971): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  971): setSupplicantStateCOMPLETED
D/ConnectivityService(  971): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  971): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  971): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  971): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  971): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  971): ignoring duplicate network state non-change
D/PhoneMonitor( 6223): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6223): [loadFeatureFromXml] *** start feature loading from xml
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  971): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,D/TelephonyAutoProfiling( 6223): [parse] Load xml
E/WifiStateMachine(  971): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  971): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
V/TelephonyAutoProfiling( 6223): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6223): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20(  971): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  971): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:38.129 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:38.132 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,E/ConnectivityService(  971): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  971): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  971): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  275): netlink response contains error (File exists)
D/ConnectivityService(  971): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  971): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  971): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/UEI.SmartControl( 6178): Loading JNI Libs...
D/ConnectivityService(  971): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  971): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  971): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  971): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  971):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  971):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  971):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  971): currentScore = 0, newScore = 20
D/ConnectivityService(  971):    accepting network in place of null
D/ConnectivityService(  971): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.1,34 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:38.135 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
E/ConnectivityService(  971): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  971): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI    (  971): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  971):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  971): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  971): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  971): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  971): MasterInitialState.processMessage what=3
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:38.165 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/UEI.SmartControl( 6178):  configuring local db...
D/ConnectivityService(  971): validation of new default Network = false
D/ConnectivityService(  971): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  971): enableDataServiceNotify 
D/DSQN    (  971): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): [LWD] Start DNSResolver start to wait
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): [LWD] wait 500ms before dns check
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
V/NetworkPolicy(  971): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  971): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
W/ResourcesManager( 6172): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6172): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/DSQN    ( 6262): DSQN samuel.seo ver 141203
E/DSQN    ( 6262): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6262): created command queue thread
I/DSQN    ( 6262): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6262): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/PhoneMonitor( 6223): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/LocationInitializer( 5620): Restart initialization of location
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/DSQN    ( 6262): first global connection report this to start monitoring at DSQM.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/DSQN    ( 6262): restart monitoring
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  971): DSQM DsqnNotification wlan0  1
D/DSQN    (  971): start to monitor internet connection
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/DSQN    ( 6262): dsqn report finish
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1732): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/DhcpStateMachine(  971): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  971): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  971): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6268): version 5.5.6 starting
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/dhcpcd  ( 6268): get_duid: Read-only file system
V/JNIHelp ( 6172): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/dhcpcd  ( 6268): wlan0: rebinding lease of 192.168.1.134
W/ActivityThread( 6172): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6172): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@389649eb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6172): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6172): GMSCore installation verified
,I/ConfigStore( 6172): Config Database version: 1
,I/art     ( 6172): Background sticky concurrent mark sweep GC freed 22891(1138KB) AllocSpace objects, 4(64KB) LOS objects, 9% free, 10MB/11MB, paused 5.229ms total 73.516ms
,I/Gmail   ( 6084): getAccountsCursor
I/Icing   ( 5620): Indexing done 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5
,I/Icing   ( 5620): Indexing 98E736199A4D0A3DAA0BBDB44355DD80A1943A96 from com.google.android.googlequicksearchbox
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): [LWD] DNSResolver start dns
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
I/Icing   ( 5620): Indexing done 98E736199A4D0A3DAA0BBDB44355DD80A1943A96
I/Icing   ( 5620): Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  971): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6284 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out(  971): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): Checking http://clients3.google.com/generate_204 on "NG700"
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Feb 2016 13:04:38 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454591078807], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454591078789]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  971): Validated
D/ConnectivityService(  971): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  971):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  971): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  971): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  971): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  971):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/UEI.SmartControl( 6178):  ---- Has DB8: true
,D/UEI.SmartControl( 6178): QS start statue = true Error code = 0
D/UEI.SmartControl( 6178): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6178): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6178): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6178): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6178): IrrcClient ++ 
D/irrcClient( 6178): getIrrcService ++ 
D/irrcClient( 6178): getIrrcService -- 
D/irrcClient( 6178): IrrcClient -- 
W/irrc_jni( 6178): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6178): Services init done
,I/UEI.SmartControl( 6178): Device manager: loading config....
D/UEI.SmartControl( 6178): Config is loaded...
I/ActivityManager(  971): Process com.google.android.videos (pid 5953) has died
,D/WifiDataContinuityService(  971): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/UEI.SmartControl( 6178): QS Service init finished
D/UEI.SmartControl( 6178): QS Service version name: 0.1.73
,I/WifiServerServiceExt(  971): set CMD_CAPTIVE_CHECK_COMPLETED
D/UEI.SmartControl( 6178): QS Service version code: 1073
I/MediaRouter( 6172): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
D/UEI.SmartControl( 6178): Service requested: Control
,I/NetworkMonitor( 6172): type=WIFI subType= reason=null isConnected=true
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
D/UEI.SmartControl( 6178):  ----- QS SDK is ready!!!
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/Icing   ( 5620): Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
I/Icing   ( 5620): Indexing BC9EFFA8FB4EBD74F2B7898FFA6492656D342420 from com.google.android.music
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/UEI.SmartControl( 6178): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6178): Internal service binding...
D/UEI.SmartControl( 6178): -----IControl: 11
D/UEI.SmartControl( 6178): Caller: com.lge.qremote
D/UEI.SmartControl( 6178): ------------ IControl registerCallback...
I/UEI.SmartControl( 6178): Registering callback...
W/ResourcesManager( 6284): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6178): -----IControl: 19
D/UEI.SmartControl( 6178): Caller: com.lge.qremote
I/UEI.SmartControl( 6178): Registering Services Ready callback...
I/UEI.SmartControl( 6178): Notify client services are ready...
D/UEI.SmartControl( 6178): -----IControl: 8
D/UEI.SmartControl( 6178): Caller: com.lge.qremote
I/Icing   ( 5620): Indexing done BC9EFFA8FB4EBD74F2B7898FFA6492656D342420
I/Icing   ( 5620): Indexing 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4 from com.google.android.googlequicksearchbox
,I/NetworkMonitor( 6172): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 6172): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6172): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 6172): com.google.android.music: cancel(1061) by com.google.android.music
,D/CalendarApplication( 6284): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6284): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6284): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@e47e7c3, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@10d4840, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@202b7379, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@384538be, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2db73d1f, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@309ea86c, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3a66ce35, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@229822ca, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@79c8c3b, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2103df58, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@12c318b1, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@387da196, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@24bdb117, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3f839904, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@bf8eed, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@276a4122, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2a6247b3, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@25234170, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1a932ce9, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@d8f4d6e, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@afac0f, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@33d3049c, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@8e8aea5, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@28e6d27a, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2c4fa2b, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1a59ce88, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1a5a9021, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2aff9c46, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@14970e07, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2b014b34, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@12af0d5d, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3d8936d2, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3a8c83a3, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3101e6a0, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@31d42259, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@39fee1e, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@ed9b6ff, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@30aecccc, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2e9b8b15, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@23d8ce2a, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@309cc41b, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3e61e9b8, 
I/[SystemU,I]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/GeneralPreferenceUtils( 6284): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6284): [init]
,I/Config  ( 6284): LGCalendar ver.4.40.17
I/Config  ( 6284): start check model
I/Config  ( 6284): start check native_ca
I/Config  ( 6284): Config Operator=OPEN, Country=EU
D/Config  ( 6284): [setDefaultValuesToPref]
D/Config  ( 6284): [parseProfiles]
I/Icing   ( 5620): Indexing done 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4
I/Icing   ( 5620): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
D/ProfilesParser( 6284): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6284): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6284): [updateProfiletoCountryInfo]
D/GeneralPreference( 6284): [checkAndMigrateOldPreference]
D/AlertReceiver( 6284): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6284): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6284): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,D/ConnectivityService(  971): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
I/Icing   ( 5620): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
I/Icing   ( 5620): Indexing B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839 from com.google.android.gms
,I/Icing   ( 5620): Indexing done B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839
I/Icing   ( 5620): Indexing 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15 from com.google.android.googlequicksearchbox
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  971): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  971): identical MTU - not setting
D/Nat464Xlat(  971): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  971): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  971):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  971): Wi-Fi IP changed. Lp difference / No Route difference
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524295
D/DSQN    (  971): enableDataServiceNotify 
D/DSQN    (  971): start dsqn bin
I/ActivityManager(  971): Process com.google.android.talk (pid 5844) has died
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:39.266 DNS addrs= 192.168.1.1, 0.0.0.0, 
,D/DSQN    (  971): dsqn is running restart
I/AlertUtils( 6284): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/DSQN    ( 6314): DSQN samuel.seo ver 141203
E/DSQN    ( 6314): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6314): created command queue thread
I/DSQN    ( 6314): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6314): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/Icing   ( 5620): Indexing done 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15
I/Icing   ( 5620): updateResources: need to parse f{com.google.android.gms}
,W/HolidayIntentService( 6284): onHandleIntent
,D/HolidayDataLoader( 6284): readJsonAsset : holiday.json
D/AlertService( 6284): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6284): [updateWidgets] 
D/MonthWidgetProvider( 6284): [onReceive]
D/CalendarWidgetProvider( 6284): [onReceive]
D/CalendarWidgetProvider( 6284): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6284): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6284): [onReceive]
D/CalendarWidgetProvider( 6284): [onReceive]
D/CalendarWidgetProvider( 6284): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6284): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5147): getMode name:com.lge.qremote
,E/HolidayIntentService( 6284): onHandleIntent:holiday data empty
,I/art     (  971): Explicit concurrent mark sweep GC freed 51616(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 13.340ms total 182.564ms
I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/ActivityManager(  971): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6324 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  971): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  971): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  971): onReceive
D/LocSvc_java(  971): got connectivity action
,D/LocSvc_java(  971): broadcast - no network connections
D/LocSvc_java(  971): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  971): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  971): onReceive
D/LocSvc_java(  971): got connectivity action
D/LocSvc_java(  971): broadcast - no network connections
D/LocSvc_java(  971): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  971): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  971): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  971): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  971): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  971): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  971): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  971): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/dhcpcd  ( 6268): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
D/GpsLocationProvider(  971): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,I/NetworkMonitor( 6172): type=WIFI subType= reason=null isConnected=true
,D/GpsLocationProvider(  971): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/dhcpcd  ( 6268): wlan0: leased 192.168.1.134 for 86400 seconds
I/NetworkMonitor( 6172): type=WIFI subType= reason=null isConnected=true
I/AlertUtils( 6284): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6284): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6284): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6284): End InitializeAlertRingtoneService.onHandleIntent
,I/Icing   ( 5620): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  971): Process com.google.android.apps.plus (pid 6108) has died
,W/ResourcesManager( 6324): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6324): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6324): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6324): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6324): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager(  971): Process com.lge.lockscreensettings (pid 6065) has died
,I/IndexDatabaseHelper( 6324): Using schema version: 115
,I/IndexDatabaseHelper( 6324): Index is fine
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  971): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  971): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  971): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  971): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  971): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  971): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  971): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  971): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  971): RunningState
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
I/ActivityManager(  971): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6370 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,V/AlarmManager(  971): RTC_WAKEUP set : Alarm{2ba3d253 type 0 when 1454591080139 com.android.vending} when 1454591080139
,D/Finsky  ( 6037): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/PCSuite ( 6370): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PCSuite ( 6370): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 6370): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/NotificationManager(  971): android: cancelAsUser(2) by android
,I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6397 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6397): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationManager( 1960): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
D/libc-netbsd( 6037): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6037): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6037): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6037): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 6037): propertyValue:false
D/libc-netbsd( 6037): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6037): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6314): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6314): restart monitoring
,I/DSQN    ( 6314): dsqn report finish
D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  971): DSQM DsqnNotification wlan0  1
D/DSQN    (  971): start to monitor internet connection
I/Icing   ( 5620): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5620): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/libc-netbsd( 6037): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6037): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:40.989 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Babel_SMS( 6397): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6397): MmsConfig.loadMmsSettings
I/Babel_SMS( 6397): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6397): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6397): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6397): MmsConfig.loadFromResources
E/Babel_SMS( 6397): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6397): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 94407961792; DSPS: 3192404; Offset : -3020510720
,D/SensorManager( 6397): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6397): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6397): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6397): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6397): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6397): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6397): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6397): found sensor: LGE Step Detector Sensor, handle=43
,D/SensorManager( 6397): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6397): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6397): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6397): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6397): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6397): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6397): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6397): found sensor: Motion Accel, handle=46
V/WifiInternetCheck(  971): Single check msg out of sync, ignoring.
D/ConnectivityService(  971): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  971): onReceive
D/LocSvc_java(  971): got connectivity action
D/LocSvc_java(  971): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  971): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  971): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  971): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  971): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  971): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkMonitor( 6172): type=WIFI subType= reason=null isConnected=true
I/art     ( 6397): CheckpointMarkThreadRoots callback created = 0xb042d890
D/GpsLocationProvider(  971): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Settings( 6397): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6397): startup - clean
I/art     ( 6397): CheckpointMarkThreadRoots callback created = 0xb042d870
,I/GAV2    ( 6084): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GAv4-SVC( 5620): Google Analytics 8.4.89 is starting up.
I/NotificationManager(  971): android: cancelAsUser(2) by android
,I/Babel   ( 6397): deleted: false for 0
,I/qtaguid ( 6037): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6037): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6037): untagSocket(41) failed with errno -22
D/Finsky  ( 6037): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  971): Process com.google.android.music:main (pid 6172) has died
,V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
I/PCSuite ( 6370): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6370): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6370): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
,I/PCSuite ( 6370): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6370): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6370): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6397): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6397): Unsupported mime audio/adpcm
W/AudioCapabilities( 6397): Unsupported mime audio/g726
W/AudioCapabilities( 6397): Unsupported mime audio/x-ms-wma
D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
W/AudioCapabilities( 6397): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6397): Unsupported mime video/mjpg
I/PCSuite ( 6370): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6370): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6370): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/VideoCapabilities( 6397): Unsupported mime video/theora
V/WiFiOffLoadBroadcast( 6324): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6324): MCCMNC not supported: null
W/AudioCapabilities( 6397): Unsupported mime audio/evrc
W/AudioCapabilities( 6397): Unsupported mime audio/qcelp
W/VideoCapabilities( 6397): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6397): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6397): Unsupported mime audio/qcelp
W/AudioCapabilities( 6397): Unsupported mime audio/evrc
,I/ActivityManager(  971): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6439 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/VideoCapabilities( 6397): Unsupported mime video/mp4v-esdp
,I/NotificationManager(  971): android: cancelAsUser(2) by android
,I/VideoCapabilities( 6397): Unsupported profile 4 for video/mp4v-es
,W/ResourcesManager( 6439): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/VideoCapabilities( 6397): Unrecognized profile 2130706433 for video/avc
W/ResourcesManager( 6439): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 6397): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6397): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6397): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6397): onServiceConnected
,W/Babel   ( 6397): Attempted to change video mute state without an active call.
I/ActivityManager(  971): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6458 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/qtaguid ( 6037): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6037): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6037): untagSocket(41) failed with errno -22
I/MultiDex( 6439): VM with version 2.1.0 has multidex support
I/MultiDex( 6439): install
I/MultiDex( 6439): VM has multidex support, MultiDex support library is disabled.
,I/NotificationManager( 6397): com.google.android.talk: cancel(8) by com.google.android.talk
I/NotificationManager( 6397): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 6397): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6397): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Process com.google.android.gm (pid 6084) has died
,I/PhoneApp( 1750): onTrimMemory: 10
I/PhoneApp( 1750): trim memory
I/BackgroundMemoryTrimmer( 1960): Trimming objects from memory, since app is in the background.
,D/UEI.SmartControl( 6178): Service.onTrimMemory: 60
E/UEI.SmartControl( 6178): Setup service releasing memory...
,V/JNIHelp ( 6439): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
V/JNIHelp ( 6397): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 6458): onCreate
W/AppUp4:DB( 6458):  [AppBoxDatabaseHelper] construct
,W/ActivityThread( 6439): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6439): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e2c37d0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6439): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6439): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6439): com.google.android.gms: cancel(39789) by com.google.android.gms
W/art     ( 6397): Suspending all threads took: 27.385ms
,I/AppUp4:DB( 6458):  setFingerPrint start
I/AppUp4:DB( 6458):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/art     ( 6178): Explicit concurrent mark sweep GC freed 10564(755KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 417us total 100.339ms
I/AppUp4:DB( 6458):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6458):  SDK version = 0
I/AppUp4:DB( 6458):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6458): AppBoxApplication onCreate()
D/ChimeraCfgMgr( 6439): Reading stored module config
,I/AppUp4:CustModeStarterReceiver( 6458): onReceive
I/AppUp4:CustModeStarterReceiver( 6458): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6458): Context : android.app.ReceiverRestrictedContext@10d4840
D/AppUp4:CustFacade( 6458): isCustomizationCompleted : false
,I/art     ( 6037): CheckpointMarkThreadRoots callback created = 0xb059d550
D/AppUp4:CustFacade( 6458): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6458): begin check event
I/AppUp4:CustModeStarterReceiver( 6458): Event For Nothing, skip.
,E/lowmemorykiller(  241): Error writing /proc/6223/oom_score_adj; errno=22
I/art     ( 6037): CheckpointMarkThreadRoots callback created = 0xb059d510
,W/System  ( 6397): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6397): Installed default security provider GmsCore_OpenSSL
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
,D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  971): Process com.google.android.setupwizard (pid 6223) has died
I/BackgroundMemoryTrimmer( 1960): Trimming objects from memory, since app is in the background.
,I/PhoneApp( 1750): onTrimMemory: 10
I/PhoneApp( 1750): trim memory
D/UEI.SmartControl( 6178): Service.onTrimMemory: 60
E/UEI.SmartControl( 6178): Setup service releasing memory...
D/NativeLibraryUtils( 6439): Install completed successfully. count=14 extracted=0
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  971): propertyValue:false
I/ActivityManager(  971): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6486 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  971): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  971): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
,D/ChimeraCfgMgr( 6439): Loading module com.google.android.gms.car from APK com.google.android.gms
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  971): propertyValue:false
V/WifiInternetCheck(  971): isHttpConnectionAvailable - We got a valid response : 204
,I/art     ( 5470): Explicit concurrent mark sweep GC freed 3119(124KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 429us total 35.348ms
,W/ResourcesManager( 6486): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6486): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6486): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/CAR.SERVICE( 6439): Connecting to CarCallService...
,I/art     ( 6439): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6439): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6439): com.google.android.projection.gearhead isn't installed.
,I/AppConfig( 6486): Total System Memory = 906309632
I/GalleryUtils( 6486): Application Heap = 96 MB
I/AppConfig( 6486): App Tier : NOT_DEF
,D/SystemHelper( 6486): region [EU], country [EU], operator [OPEN], sub-operator []
D/CAR.TEL.Service( 6439): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6439): Creating a new PhoneAdapter instance
,W/ActivityManager(  971): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6439): setListener: com.google.android.gms.car.dn@38fea0df
W/ActivityManager(  971): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6439): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6439): Starting CarCallService with initial phone null
I/NotificationManager( 6439): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  971): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6514 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/CAR.SERVICE( 6439): Package validated; name: com.android.vending
I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 23.562ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 325us total 21.343ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.977ms
,I/NotificationManager( 6037): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6037): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,W/ResourcesManager( 6514): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6514): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6514): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6514): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6514): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 6514): BUILD Country: EU
,I/SystemConfig( 6514): BUILD Operator: OPEN
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  971): android: cancelAsUser(2) by android
I/ActivityManager(  971): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6535 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6514): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 6514): existFile = false
I/SystemConfig( 6514): canReadFile = false
I/SystemConfig( 6514): systemFeature RCS result false
D/SystemConfig( 6514): refreshRcsSupport() :false
I/qtaguid ( 6037): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6037): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6037): untagSocket(41) failed with errno -22
,I/LockScreenSettings( 6535): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6535): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6535): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6535): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6535): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6535): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6552 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Process com.android.settings (pid 6324) has died
,W/ResourcesManager( 6037): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6037): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6552): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6037): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  971): RTC_WAKEUP set : Alarm{334ce180 type 0 when 1454591083746 com.android.vending} when 1454591083746
D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
,I/ActivityManager(  971): Process com.lge.qremote (pid 5147) has died
,D/Finsky  ( 6037): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6037): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/UEI.SmartControl( 6178): Internal timer expired: 1
,D/UEI.SmartControl( 6178): Service.onUnbind: IControl
D/UEI.SmartControl( 6178): Service.onDestroy
D/UEI.SmartControl( 6178): Shutdown IRRCPlayer... 
W/irrc_jni( 6178): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6178): ~IrrcClient ++ 
D/irrcClient( 6178): ~IrrcClient -- 
W/irrc_jni( 6178): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6178): Blaster closed
D/UEI.SmartControl( 6178): Blaster closed
D/UEI.SmartControl( 6178): Shut down QS...
D/UEI.SmartControl( 6178): Stopped file observer...
,I/UEI.SmartControl( 6178): QS lib stop result = true
D/UEI.SmartControl( 6178): QS shutdown complete
I/UpdateIcingCorporaServi( 1960): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 5620): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 1960): UpdateCorporaTask done [took 61 ms] updated apps [took 61 ms] 
,I/ActivityManager(  971): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6580 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/PackageBroadcastService( 5620): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  971): Process com.uei.lg.quicksetsdk.lite (pid 6178) has died
,I/Icing   ( 5620): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6580): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/CalendarProvider2( 6580): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1b4d8c7d
,I/art     (  971): Explicit concurrent mark sweep GC freed 39723(1942KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.624ms total 169.606ms
,D/CalendarProvider2( 6580): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6580): Created com.android.providers.calendar.CalendarAlarmManager@384538be(com.android.providers.calendar.CalendarProvider2@1b4d8c7d)
,D/CalendarProviderBroadcastReceiver( 6580): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6580): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6580): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6580): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6580): [getOrCreateCalendarAlarmManager]
D/AlertService( 6284): Beginning updateAlertNotification
,I/ActivityManager(  971): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6603 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/CalendarProvider2( 6580): [IntentService] Release Lock
,D/CalendarProvider2( 6580): CalendarProviderIntentService.onDestroy()
D/AlertService( 6284): No fired or scheduled alerts
,I/NotificationManager( 6284): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(16) by com.android.calendar
,I/NotificationManager( 6284): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6284): com.android.calendar: cancel(20) by com.android.calendar
W/ResourcesManager( 6603): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6603): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6603): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6603): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6603): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/AlertService( 6284): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6284): No events found starting within 1 week.
,I/ActivityManager(  971): Killing 6284:com.android.calendar/u0a13 (adj 15): empty #11
I/IndexDatabaseHelper( 6603): Using schema version: 115
I/IndexDatabaseHelper( 6603): Index is fine
W/libprocessgroup(  971): failed to open /acct/uid_10013/pid_6284/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6603): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6603): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6603): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6603): MCCMNC not supported: null
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  971): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6628 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  971): Killing 6458:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10011/pid_6458/cgroup.procs: No such file or directory
,W/ResourcesManager( 6628): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/BluetoothManagerService(  971): Message: 20
,D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17956f86:true
D/BluetoothAdapterService(580395722)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@25234170
D/BluetoothAdapterService(580395722)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@25234170
V/WiFiOffLoadBroadcast( 6603): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6603): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6603): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6603): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6603): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6603): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6603): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6603): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6603): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6603): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6603): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6603): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6603): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6603): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6603): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6603): MCCMNC not supported: null
I/PCSuite ( 6370): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6370): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6603): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6603): MCCMNC not supported: null
I/PCSuite ( 6370): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6370): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/Icing   ( 5620): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/jxcore-log( 5735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5735): 
I/ActivityManager(  971): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6653 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 5620): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  971): Killing 6486:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10023/pid_6486/cgroup.procs: No such file or directory
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6653): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6653): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6653): Error finding the version of the Email provider.....
E/Gmail   ( 6653): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6653): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6653): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6653): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6653): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6653): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6653): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6653): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6653): We do not support migrating this version of the Email provider.
,I/ActivityManager(  971): Killing 6514:com.android.contacts/u0a18 (adj 15): empty #11
I/Gmail   ( 6653): getAccountsCursor
W/libprocessgroup(  971): failed to open /acct/uid_10018/pid_6514/cgroup.procs: No such file or directory
,W/ActivityManager(  971): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6653): Observing account changes for notifications
,I/ActivityManager(  971): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6689 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/LGMDMManager( 6628): Create singleton instance
V/AlarmManager(  971): RTC_WAKEUP set : Alarm{1783e82f type 0 when 1454591086171 com.google.android.googlequicksearchbox} when 1454591086171
,D/UEI.SmartControl( 6689): Quickset Services start...
I/UEI.SmartControl( 6689): Manufacture = LGE
D/UEI.SmartControl( 6689): File observer start...
E/UEI.SmartControl( 6689): IR Port is disabled: false
D/UEI.SmartControl( 6689): Starting file observer...
D/UEI.SmartControl( 6689): Extracting JNI libs...
D/UEI.SmartControl( 6689): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 6689): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6689): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6689): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/AudioManager( 6628): getMode name:com.lge.qremote
,I/AudioManager( 6628): getMode name:com.lge.qremote
I/UEI.SmartControl( 6689): --- Selecting new region: 2
,I/UEI.SmartControl( 6689): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6689): Platform has CIR...
,D/UEI.SmartControl( 6689): NO CIR support, need to check package...
I/UEI.SmartControl( 6689): Model: LG-D722 uses JNI
I/Gmail   ( 6653): notifyAccountChanged
D/UEI.SmartControl( 6689): QS Service created
I/Gmail   ( 6653): getAccountsCursor
,I/Gmail   ( 6653): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6653): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6653): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6653): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  971): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6722 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/UEI.SmartControl( 6689): QS start get config
,D/UEI.SmartControl( 6689): Loading JNI Libs...
,D/UEI.SmartControl( 6689):  configuring local db...
,I/Gmail   ( 6653): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 5735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5735): 
,I/MusicStore( 6722): Database version: 120
,I/ActivityManager(  971): Process com.android.vending (pid 6037) has died
D/CAR.SERVICE( 6439): mConnectedToCar = false, abort
,E/ActivityThread( 6439): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@23a41be7 that was originally bound here
E/ActivityThread( 6439): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@23a41be7 that was originally bound here
E/ActivityThread( 6439): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6439): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6439): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6439): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6439): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6439): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6439): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6439): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6439): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6439): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6439): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6439): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6439): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6439): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6439): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6439): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6439): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6439): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6439): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6439): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6439): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6439): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6439): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/ActivityThread( 6439): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@9c0d37e that was originally bound here
E/ActivityThread( 6439): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@9c0d37e that was originally bound here
E/ActivityThread( 6439): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6439): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6439): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6439): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6439): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6439): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6439): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6439): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6439): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6439): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6439): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6439): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6439): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6439): 	at android.app.ActivityThread.access,$1900(ActivityThread.java:155)
E/ActivityThread( 6439): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6439): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6439): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6439): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6439): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6439): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6439): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6439): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  971): Unbind failed: could not find connection for android.os.BinderProxy@3addc179
I/jxcore-log( 5735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5735): 
,I/jxcore-log( 5735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5735): 
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6722): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/UEI.SmartControl( 6689):  ---- Has DB8: true
,D/UEI.SmartControl( 6689): QS start statue = true Error code = 0
D/UEI.SmartControl( 6689): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6689): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6689): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6689): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6689): IrrcClient ++ 
D/irrcClient( 6689): getIrrcService ++ 
D/irrcClient( 6689): getIrrcService -- 
D/irrcClient( 6689): IrrcClient -- 
W/irrc_jni( 6689): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6689): Services init done
I/UEI.SmartControl( 6689): Device manager: loading config....
D/UEI.SmartControl( 6689): QS Service init finished
D/UEI.SmartControl( 6689): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6689): QS Service version code: 1073
D/UEI.SmartControl( 6689): Service requested: Control
D/UEI.SmartControl( 6689): Config is loaded...
I/jxcore-log( 5735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5735): 
,D/UEI.SmartControl( 6689): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6689): Internal service binding...
,D/UEI.SmartControl( 6689): -----IControl: 11
D/UEI.SmartControl( 6689): Caller: com.lge.qremote
D/UEI.SmartControl( 6689): ------------ IControl registerCallback...
I/UEI.SmartControl( 6689): Registering callback...
D/UEI.SmartControl( 6689): -----IControl: 19
D/UEI.SmartControl( 6689): Caller: com.lge.qremote
I/UEI.SmartControl( 6689): Registering Services Ready callback...
I/UEI.SmartControl( 6689): Notify client services are ready...
,D/UEI.SmartControl( 6689): -----IControl: 8
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6722): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/UEI.SmartControl( 6689): Caller: com.lge.qremote
D/UEI.SmartControl( 6689):  ----- QS SDK is ready!!!
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6722): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/UEI.SmartControl( 6689): Notify AllClients services are ready: 0
I/jxcore-log( 5735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5735): 
,I/jxcore-log( 5735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5735): 
,W/ResourcesManager( 6722): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6722): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/jxcore-log( 5735): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5735): 
V/JNIHelp ( 6722): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6722): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6722): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@389649eb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6722): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6722): GMSCore installation verified
I/ConfigStore( 6722): Config Database version: 1
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/MediaRouter( 6722): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6722): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6722): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  971): Killing 6535:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10069/pid_6535/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6722): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  971): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6753 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/GHttpClientFactory( 6722): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6722): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  971): Killing 6552:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/ResourcesManager( 6753): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6753): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6753): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  971): Killing 6439:com.google.android.gms:car/u0a6 (adj 15): empty #12
,W/libprocessgroup(  971): failed to open /acct/uid_10086/pid_6552/cgroup.procs: No such file or directory
,W/libprocessgroup(  971): failed to open /acct/uid_10006/pid_6439/cgroup.procs: No such file or directory
I/NotificationManager( 6722): com.google.android.music: cancel(1061) by com.google.android.music
I/art     (  971): Explicit concurrent mark sweep GC freed 12680(612KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.644ms total 149.488ms
,I/LGEmail ( 6753): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6753): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/eas_req ( 6753): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  971): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6797 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6753): JNI_OnLoad()
I/HubEmail( 6753): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6753): registerNatives()
I/HubEmail( 6753): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6753): registerNativeMethods()
I/HubEmail( 6753): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6753): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6753): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  971): Killing 6580:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10014/pid_6580/cgroup.procs: No such file or directory
,D/LGDMClient( 6797): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6797): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6797): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6797): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6797): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6797): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 6797): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  971): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6820 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/LGDMClient( 6797): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 320us total 23.984ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.204ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.419ms
,W/ContextImpl( 6797): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6797): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6797): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6797): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6797): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6797): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  971): Killing 6603:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_1000/pid_6603/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6820): onCreate
,W/AppUp4:DB( 6820):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6820):  setFingerPrint start
I/AppUp4:DB( 6820):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6820):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6820):  SDK version = 0
I/AppUp4:DB( 6820):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6820): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6820): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6820): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6820): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 6820): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6820): onReceive
I/AppUp4:CustModeStarterReceiver( 6820): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6820): Context : android.app.ReceiverRestrictedContext@2db73d1f
D/AppUp4:CustFacade( 6820): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6820): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6820): begin check event
I/AppUp4:CustModeStarterReceiver( 6820): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6820): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6820): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6820): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6820): handleAsyncCustNotification do not startCustService
I/ActivityManager(  971): Killing 6370:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_1000/pid_6370/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3246): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3246): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3246): networkInfo.isConnected() = false
I/ActivityManager(  971): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6848 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6848): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6848): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6848): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  971): Killing 6397:com.google.android.talk/u0a61 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/rmt_storage(  273): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  273): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  273): wakelock acquired: 1, error no: 42
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
W/libprocessgroup(  971): failed to open /acct/uid_10061/pid_6397/cgroup.procs: No such file or directory
,V/DownloadManager( 3194): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/CheckinService( 5620): Checkin interval check for package: unspecified last checkin: 1454591066636 min interval config: 0 actual interval: 22565
,V/DownloadManager( 3194): DownloadService onCreate
I/DownloadManager( 3194): in removeSpuriousFiles
I/NotificationManager( 3194): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/ActivityManager(  971): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6870 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/CheckinService( 5620): Checking schedule, now: 1454591089255 next: 1454591096599
I/CheckinService( 5620): active receiver: disabled
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  273): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  273): 
V/DownloadManager( 3194): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/rmt_storage(  273): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@759b93 on behalf of 3194
V/DownloadManager( 3194): DownloadService onStartCommand
I/DownloadManager( 3194): in trimDatabase
V/DownloadManager( 3194): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,D/PhoneMonitor( 6848): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6848): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6848): [parse] Load xml
V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@f321ace on behalf of 3194
,V/TelephonyAutoProfiling( 6848): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6848): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3194): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@5d45def on behalf of 3194
,D/PhoneMonitor( 6848): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  971): Killing 6689:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6628): android.os.DeadObjectException
W/System.err( 6628): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6628): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 6628): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6628): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6628): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6628): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6628): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6628): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6628): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6628): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6628): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6628): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6628): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6628): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6628): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6628): android.os.DeadObjectException
W/System.err( 6628): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6628): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6628): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6628): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6628): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6628): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6628): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6628): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6628): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6628): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6628): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6628): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6628): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6628): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6628): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  971): failed to open /acct/uid_10089/pid_6689/cgroup.procs: No such file or directory
W/ActivityManager(  971): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,V/DownloadManager( 3194): DownloadService onDestroy
D/WeatherAncestor( 2780): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:4:49
,I/ActivityManager(  971): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6901 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UpdateThreadPoolManager( 2780): 2 : This is isUpdating : false
D/WeatherAncestor( 2780): connectivity changed - connection : true
D/Weather_cast( 2780): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2780): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:4:49
,D/WeatherService( 2780): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6918 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  971): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2780): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2780): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2780): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6918): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6901): Quickset Services start...
I/UEI.SmartControl( 6901): Manufacture = LGE
D/UEI.SmartControl( 6901): File observer start...
E/UEI.SmartControl( 6901): IR Port is disabled: false
D/UEI.SmartControl( 6901): Starting file observer...
D/UEI.SmartControl( 6901): Extracting JNI libs...
D/UEI.SmartControl( 6901): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 6901): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6901): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6901): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
I/UEI.SmartControl( 6901): --- Selecting new region: 2
,I/UEI.SmartControl( 6901): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6901): Platform has CIR...
D/UEI.SmartControl( 6901): NO CIR support, need to check package...
I/UEI.SmartControl( 6901): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6901): QS Service created
E/UEI.SmartControl( 6901): QS start get config
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:50.033 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 6901): Loading JNI Libs...
D/UEI.SmartControl( 6901):  configuring local db...
,I/Babel_SMS( 6918): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6918): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6918): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6918): MmsConfig.loadFromDatabase
E/Babel_SMS( 6918): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6918): MmsConfig.loadFromResources
E/Babel_SMS( 6918): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6918): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
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
,I/Babel_Crash( 6918): startup - clean
I/art     ( 6918): CheckpointMarkThreadRoots callback created = 0xaaf39450
,I/Babel   ( 6918): deleted: false for 0
I/art     ( 6918): CheckpointMarkThreadRoots callback created = 0xaaf39430
,D/UEI.SmartControl( 6901):  ---- Has DB8: true
,D/UEI.SmartControl( 6901): QS start statue = true Error code = 0
D/UEI.SmartControl( 6901): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6901): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6901): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6901): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6901): IrrcClient ++ 
D/irrcClient( 6901): getIrrcService ++ 
D/irrcClient( 6901): getIrrcService -- 
D/irrcClient( 6901): IrrcClient -- 
W/irrc_jni( 6901): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6901): Services init done
D/UEI.SmartControl( 6901): QS Service init finished
D/UEI.SmartControl( 6901): QS Service version name: 0.1.73
D/UEI.SmartControl( 6901): QS Service version code: 1073
D/UEI.SmartControl( 6901): Service requested: Control
I/UEI.SmartControl( 6901): Device manager: loading config....
,D/UEI.SmartControl( 6901): Config is loaded...
D/UEI.SmartControl( 6901):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6901): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6901): Request IControl service: devices are loaded...
I/ActivityManager(  971): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6961 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  971): Killing 6628:com.lge.qremote/u0a106 (adj 15): empty #11
,W/AudioCapabilities( 6918): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6918): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6918): Unsupported mime audio/g726
W/AudioCapabilities( 6918): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6918): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6918): Unsupported mime video/mjpg
W/VideoCapabilities( 6918): Unsupported mime video/theora
W/AudioCapabilities( 6918): Unsupported mime audio/evrc
,W/AudioCapabilities( 6918): Unsupported mime audio/qcelp
W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6918): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6918): Unsupported mime audio/qcelp
W/AudioCapabilities( 6918): Unsupported mime audio/evrc
W/VideoCapabilities( 6918): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6918): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6918): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup(  971): failed to open /acct/uid_10106/pid_6628/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6901): Internal service binding...
,I/vclib   ( 6918): onServiceConnected
,W/Babel   ( 6918): Attempted to change video mute state without an active call.
I/NotificationManager( 6918): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6918): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6918): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6918): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6918): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6918): propertyValue:false
I/Babel   ( 6918): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  971): Killing 6653:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10053/pid_6653/cgroup.procs: No such file or directory
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6961): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6961): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6961): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6961): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6961): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6961):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6961):   adb logcat -s GAv4
,W/GAv4    ( 6961): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6961): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6961): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/WebViewFactory( 6961): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6961): Time to load native libraries: 2 ms (timestamps 4676-4678)
I/LibraryLoader( 6961): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6961): Binding Chromium to main looper Looper (main, tid 1) {ce53500}
,I/LibraryLoader( 6961): Expected native library version number "",actual native library version number ""
I/chromium( 6961): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6961): Initializing chromium process, singleProcess=true
,W/art     ( 6961): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6961): ApplicationContext is null in ApplicationStatus
W/chromium( 6961): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6961): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6961): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6961): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6961): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6961): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6961): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6961): Remote Branch: 
I/Adreno-EGL( 6961): Local Patches: 
I/Adreno-EGL( 6961): Reconstruct Branch: 
I/NSApplication( 6961): Starting up...
,V/AudioPolicyService(  279): registerClient() client 0xb57f2a80, uid 10079
W/AudioManagerAndroid( 6961): Requires BLUETOOTH permission
,I/ActivityManager(  971): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7025 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  971): Killing 6722:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/CheckinService( 5620): Done disabling old GoogleServicesFramework version
,W/libprocessgroup(  971): failed to open /acct/uid_10081/pid_6722/cgroup.procs: No such file or directory
,I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7052 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  971): Killing 6753:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10021/pid_6753/cgroup.procs: No such file or directory
,W/ResourcesManager( 7052): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/iu.SyncManager( 5620): SYNC; picasa accounts
,D/NetworkLogImpl( 5620): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5620): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager(  971): Killing 6797:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/iu.UploadsManager( 5620): num queued entries: 0
I/iu.UploadsManager( 5620): num updated entries: 0
,I/iu.SyncManager( 5620): NEXT; no task
W/libprocessgroup(  971): failed to open /acct/uid_1000/pid_6797/cgroup.procs: No such file or directory
,I/ActivityManager(  971): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7081 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7081): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7081): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:04:53.051 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7081): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7081): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7081): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7081): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7081): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7081): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7081): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@389649eb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7081): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7081): GMSCore installation verified
I/ConfigStore( 7081): Config Database version: 1
,I/MediaRouter( 7081): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7081): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7081): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7081): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  971): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7117 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7081): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7081): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7117): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7117): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7117): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  971): Killing 6820:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10011/pid_6820/cgroup.procs: No such file or directory
,I/NotificationManager( 7081): com.google.android.music: cancel(1061) by com.google.android.music
,I/art     (  971): Explicit concurrent mark sweep GC freed 19859(989KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.937ms total 154.092ms
,I/LGEmail ( 7117): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7117): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7117): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  971): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7148 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7117): JNI_OnLoad()
I/HubEmail( 7117): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7117): registerNatives()
I/HubEmail( 7117): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7117): registerNativeMethods()
I/HubEmail( 7117): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7117): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  971): Killing 6848:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/libprocessgroup(  971): failed to open /acct/uid_10038/pid_6848/cgroup.procs: No such file or directory
,W/Settings( 7117): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7148): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7148): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7148): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7148): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7148): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7148): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7148): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7148): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  971): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7172 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7148): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 21.133ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 336us total 23.170ms
,E/LGDMClient( 7148): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7148): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7148): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7148): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7148): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 21.946ms
I/ActivityManager(  971): Killing 6870:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10051/pid_6870/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7172): onCreate
W/AppUp4:DB( 7172):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7172):  setFingerPrint start
I/AppUp4:DB( 7172):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7172):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7172):  SDK version = 0
I/AppUp4:DB( 7172):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7172): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7172): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7172): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7172): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7172): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7172): onReceive
I/AppUp4:CustModeStarterReceiver( 7172): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7172): Context : android.app.ReceiverRestrictedContext@2db73d1f
D/AppUp4:CustFacade( 7172): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7172): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7172): begin check event
I/AppUp4:CustModeStarterReceiver( 7172): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7172): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7172): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7172): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7172): handleAsyncCustNotification do not startCustService
I/ActivityManager(  971): Killing 6901:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
E/libprocessgroup(  971): failed to kill 1 processes for processgroup 6901
,I/LgeMiscReceiver( 3246): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3246): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3246): networkInfo.isConnected() = false
,I/ActivityManager(  971): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7194 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/PhoneMonitor( 7194): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7194): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7194): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  971): Killing 6918:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7194): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7194): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7194): [parse] Load xml
V/TelephonyAutoProfiling( 7194): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7194): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7194): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  971): failed to open /acct/uid_10061/pid_6918/cgroup.procs: No such file or directory
V/DownloadManager( 3194): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3194): DownloadService onCreate
,I/NotificationManager( 3194): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3194): in removeSpuriousFiles
V/DownloadManager( 3194): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@7b66385 on behalf of 3194
I/DownloadManager( 3194): in trimDatabase
V/DownloadManager( 3194): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@39b2ea0b on behalf of 3194
I/ActivityManager(  971): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7220 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3194): DownloadService onStartCommand
V/DownloadManager( 3194): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@ffeb301 on behalf of 3194
I/CheckinService( 5620): Checkin interval check for package: unspecified last checkin: 1454591066636 min interval config: 0 actual interval: 28626
I/CheckinService( 5620): Checking schedule, now: 1454591095285 next: 1454591096599
I/CheckinService( 5620): active receiver: disabled
,V/DownloadManager( 3194): DownloadService onDestroy
,I/ActivityManager(  971): Killing 6961:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,E/libprocessgroup(  971): failed to kill 1 processes for processgroup 6961
,D/WeatherAncestor( 2780): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:4:55
,D/UpdateThreadPoolManager( 2780): 2 : This is isUpdating : false
D/WeatherAncestor( 2780): connectivity changed - connection : true
D/Weather_cast( 2780): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2780): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:4:55
D/WeatherService( 2780): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7242 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  971): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2780): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2780): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2780): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7242): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7242): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7242): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7242): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7242): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7242): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7242): MmsConfig.loadFromResources
E/Babel_SMS( 7242): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7242): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7242): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7242): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7242): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7242): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7242): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7242): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7242): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7242): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7242): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7242): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7242): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7242): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7242): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7242): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7242): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7242): found sensor: Motion Accel, handle=46
,W/Settings( 7242): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7242): startup - clean
I/Babel   ( 7242): deleted: false for 0
,I/art     ( 7242): CheckpointMarkThreadRoots callback created = 0xb042d5b0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/art     ( 7242): CheckpointMarkThreadRoots callback created = 0xb042d590
,I/ActivityManager(  971): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7278 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7242): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7242): Unsupported mime audio/adpcm
W/AudioCapabilities( 7242): Unsupported mime audio/g726
W/AudioCapabilities( 7242): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7242): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 7242): Unsupported mime video/mjpg
W/VideoCapabilities( 7242): Unsupported mime video/theora
W/AudioCapabilities( 7242): Unsupported mime audio/evrc
,I/jxcore-log( 5735): Test app app.js loaded
I/jxcore-log( 5735): 
W/AudioCapabilities( 7242): Unsupported mime audio/qcelp
W/VideoCapabilities( 7242): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7242): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7242): Unsupported mime audio/qcelp
W/AudioCapabilities( 7242): Unsupported mime audio/evrc
W/VideoCapabilities( 7242): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7242): Unsupported profile 4 for video/mp4v-es
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5735): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5735): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5735): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5735): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5735): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5735): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5735): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5735): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5735): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5735): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b55b31f added. We now have 1 listener(s)
D/BluetoothAdapterService(580395722)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@25234170
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7278): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/VideoCapabilities( 7242): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7242): Unrecognized profile 2130706433 for video/avc
I/jxcore-log( 5735): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5735): 
,W/VideoCapabilities( 7242): Unrecognized profile 2130706433 for video/avc
I/GAv4    ( 7278): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7278):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7278):   adb logcat -s GAv4
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7278): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/VideoCapabilities( 7242): Unrecognized profile 2130706433 for video/avc
W/GAv4    ( 7278): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7278): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/vclib   ( 7242): onServiceConnected
W/Babel   ( 7242): Attempted to change video mute state without an active call.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7278): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,D/libc-netbsd( 7242): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7242): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7242): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7242): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 7242): propertyValue:false
I/NotificationManager( 7242): com.google.android.talk: cancel(10436) by com.google.android.talk
I/chromium( 5735): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
W/GAv4    ( 7278): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7278): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 7242): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  971): Killing 7025:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10048/pid_7025/cgroup.procs: No such file or directory
,I/WebViewFactory( 7278): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7278): Time to load native libraries: 1 ms (timestamps 99-100)
I/LibraryLoader( 7278): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7278): Binding Chromium to main looper Looper (main, tid 1) {ce53500}
I/LibraryLoader( 7278): Expected native library version number "",actual native library version number ""
I/chromium( 7278): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7278): Initializing chromium process, singleProcess=true
,W/art     ( 7278): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7278): ApplicationContext is null in ApplicationStatus
W/chromium( 7278): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7278): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7278): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7278): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7278): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7278): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7278): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7278): Remote Branch: 
I/Adreno-EGL( 7278): Local Patches: 
I/Adreno-EGL( 7278): Reconstruct Branch: 
,V/AudioPolicyService(  279): registerClient() client 0xb4027840, uid 10079
,W/AudioManagerAndroid( 7278): Requires BLUETOOTH permission
I/NSApplication( 7278): Starting up...
I/ActivityManager(  971): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7343 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Killing 7052:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10086/pid_7052/cgroup.procs: No such file or directory
,I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7365 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  971): Killing 7081:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10081/pid_7081/cgroup.procs: No such file or directory
W/ResourcesManager( 7365): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Killing 7117:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10021/pid_7117/cgroup.procs: No such file or directory
,I/ActivityManager(  971): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7389 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7389): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  971): Message: 20
D/BluetoothManagerService(  971): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@36e3ae6e:true
,D/BluetoothAdapterService(580395722)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@25234170
D/BluetoothAdapterService(580395722)( 2035): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@25234170
I/AudioManager( 7389): getMode name:com.lge.qremote
,I/ActivityManager(  971): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7407 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7407): Database version: 120
,V/AlarmManager(  971): RTC_WAKEUP set : Alarm{3af1425d type 0 when 1454591096599 com.google.android.gms} when 1454591096599
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7407): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  971): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7430 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  971): RTC_WAKEUP set : Alarm{bdfc7d2 type 0 when 1454591097949 com.android.vending} when 1454591097949
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7407): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7407): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7407): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7407): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7407): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7407): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7407): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@389649eb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7407): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7407): GMSCore installation verified
I/ConfigStore( 7407): Config Database version: 1
D/Finsky  ( 7430): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/MediaRouter( 7407): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 7407): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7407): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7407): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  971): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7477 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7407): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7407): Using platform SSLCertificateSocketFactory
,D/Finsky  ( 7430): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7430): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7430): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7430): com.android.vending: cancel(-1050172287) by com.android.vending
,I/art     (  971): Explicit concurrent mark sweep GC freed 26796(1478KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.070ms total 164.277ms
,V/DownloadManager( 3194): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@23a41be7 on behalf of 7430
W/ResourcesManager( 7477): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7477): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7477): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/Ads     ( 7430): Skipping gmscore version check
,D/Finsky  ( 7430): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7430): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  971): Killing 7148:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_1000/pid_7148/cgroup.procs: No such file or directory
,I/NotificationManager( 7407): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7477): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/Finsky  ( 7430): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/LGEmail ( 7477): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/Finsky  ( 7430): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/eas_req ( 7477): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/Finsky  ( 7430): [945] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7430): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  971): Killing 7172:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10011/pid_7172/cgroup.procs: No such file or directory
,I/HubEmail( 7477): JNI_OnLoad()
I/HubEmail( 7477): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7477): registerNatives()
I/HubEmail( 7477): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7477): registerNativeMethods()
I/HubEmail( 7477): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7477): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  971): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7514 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/Settings( 7477): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.196ms
,I/ActivityManager(  971): Killing 7194:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 22.058ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 22.133ms
,W/libprocessgroup(  971): failed to open /acct/uid_10038/pid_7194/cgroup.procs: No such file or directory
,D/LGDMClient( 7514): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7514): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7514): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7514): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7514): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7514): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7514): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7514): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  971): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7537 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7514): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
E/LGDMClient( 7514): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7514): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7514): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7514): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7514): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  971): Killing 7220:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10051/pid_7220/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7537): onCreate
W/AppUp4:DB( 7537):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7537):  setFingerPrint start
I/AppUp4:DB( 7537):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7537):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 7537):  SDK version = 0
I/AppUp4:DB( 7537):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7537): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7537): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7537): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7537): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7537): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7537): onReceive
I/AppUp4:CustModeStarterReceiver( 7537): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7537): Context : android.app.ReceiverRestrictedContext@2db73d1f
D/AppUp4:CustFacade( 7537): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7537): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7537): begin check event
I/AppUp4:CustModeStarterReceiver( 7537): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7537): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7537): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7537): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7537): handleAsyncCustNotification do not startCustService
I/ActivityManager(  971): Killing 7242:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10061/pid_7242/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3246): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3246): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3246): networkInfo.isConnected() = true
,D/PhoneState( 3246): setPdpRejectCasuse : false
I/ActivityManager(  971): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7556 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7556): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7556): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7556): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  971): Killing 7278:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,D/PhoneMonitor( 7556): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7556): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7556): [parse] Load xml
V/TelephonyAutoProfiling( 7556): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7556): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7556): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  971): failed to open /acct/uid_10079/pid_7278/cgroup.procs: No such file or directory
V/DownloadManager( 3194): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3194): DownloadService onCreate
I/DownloadManager( 3194): in removeSpuriousFiles
,V/DownloadManager( 3194): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3194): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@290a7394 on behalf of 3194
I/DownloadManager( 3194): in trimDatabase
V/DownloadManager( 3194): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@3e548632 on behalf of 3194
I/ActivityManager(  971): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7581 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3194): DownloadService onStartCommand
V/DownloadManager( 3194): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@ce53500 on behalf of 3194
I/CheckinService( 5620): Checkin interval check for package: unspecified last checkin: 1454591066636 min interval config: 0 actual interval: 33115
I/CheckinService( 5620): Checking schedule, now: 1454591099766 next: 1454591096599
I/CheckinService( 5620): active receiver: enabled
,V/DownloadManager( 3194): DownloadService onDestroy
I/CheckinService( 5620): Preparing to send checkin request
,I/EventLogService( 5620): Accumulating logs since 1454591056677
D/WeatherAncestor( 2780): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:4:59
,D/UpdateThreadPoolManager( 2780): 2 : This is isUpdating : false
D/WeatherAncestor( 2780): connectivity changed - connection : true
D/Weather_cast( 2780): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2780): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:4:59
D/WeatherService( 2780): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7600 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  971): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2780): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2780): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2780): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7600): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
I/art     ( 5470): Explicit concurrent mark sweep GC freed 1833(66KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 379us total 34.335ms
,D/WeatherService( 2780): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:5:0
D/WeatherService( 2780): 2 : TimeTick Intent And Screen On
D/WeatherService( 2780): 2 : SDK version : 21
W/ActivityManager(  971): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2780): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2780): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2780): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2780): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2780): 2 : This is isUpdating : false
D/WeatherService( 2780): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2780): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2780): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2780): 2 : Fixed theme : optimus
D/WeatherReflect( 2780): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
,D/lim     ( 2780): 2 : time = 14:05
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/WeatherReflect( 2780): Model Name : LG-D722
D/WeatherTheme( 2780): 2 : Different view - status_min_formatted : 04 != 05
D/WeatherTheme( 2780): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2780): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,D/Theme   ( 2780): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2780): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/CheckinRequestBuilder( 5620): Checkin reason type: 8 attempt count: 1
,D/Weather4x2_optimus( 2780): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2780): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2780): forecast size is 0
D/Theme   ( 2780): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2780): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2780): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2780): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2780): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2780): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2780): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2780): url is : null
D/Theme   ( 2780): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2780): 2 : update view, appWidgetId: 2
E/ActivityThread( 5620): Failed to find provider info for com.google.android.wearable.settings
,D/WeatherService( 2780): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:5:0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Babel_SMS( 7600): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7600): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7600): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7600): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7600): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7600): MmsConfig.loadFromResources
E/Babel_SMS( 7600): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7600): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/SensorManager( 7600): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7600): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7600): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7600): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7600): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7600): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7600): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7600): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7600): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7600): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7600): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7600): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7600): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7600): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7600): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7600): found sensor: Motion Accel, handle=46
W/Settings( 7600): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7600): startup - clean
I/Babel   ( 7600): deleted: false for 0
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/art     ( 7600): CheckpointMarkThreadRoots callback created = 0xb042d520
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 7600): CheckpointMarkThreadRoots callback created = 0xb042d4f0
,I/ActivityManager(  971): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7644 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7600): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7600): Unsupported mime audio/adpcm
W/AudioCapabilities( 7600): Unsupported mime audio/g726
W/AudioCapabilities( 7600): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7600): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7600): Unsupported mime video/mjpg
W/VideoCapabilities( 7600): Unsupported mime video/theora
,W/AudioCapabilities( 7600): Unsupported mime audio/evrc
,W/AudioCapabilities( 7600): Unsupported mime audio/qcelp
W/VideoCapabilities( 7600): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7600): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7600): Unsupported mime audio/qcelp
W/AudioCapabilities( 7600): Unsupported mime audio/evrc
W/VideoCapabilities( 7600): Unsupported mime video/mp4v-esdp
,I/ActivityManager(  971): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7661 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/VideoCapabilities( 7600): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7600): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7600): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7600): Unrecognized profile 2130706433 for video/avc
W/ResourcesManager( 7661): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7661): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/VideoCapabilities( 7600): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 7600): onServiceConnected
W/Babel   ( 7600): Attempted to change video mute state without an active call.
,D/libc-netbsd( 7600): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7600): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7600): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7600): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 7600): propertyValue:false
I/NotificationManager( 7600): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/GAv4    ( 7644): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7644):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7644):   adb logcat -s GAv4
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7644): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/MultiDex( 7661): VM with version 2.1.0 has multidex support
,I/MultiDex( 7661): install
I/MultiDex( 7661): VM has multidex support, MultiDex support library is disabled.
I/Babel   ( 7600): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 7644): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7644): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7644): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
V/JNIHelp ( 7661): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ContextImpl( 7644): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7644): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7644): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityThread( 7661): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7661): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e2c37d0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7661): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7661): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 7661): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 7661): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7661): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 114408757774; DSPS: 3847790; Offset : -3020507753
,D/NativeLibraryUtils( 7661): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): CdmEngine::OpenSession
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
I/WebViewFactory( 7644): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
,I/LibraryLoader( 7644): Time to load native libraries: 4 ms (timestamps 4549-4553)
,I/LibraryLoader( 7644): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7644): Binding Chromium to main looper Looper (main, tid 1) {ce53500}
I/LibraryLoader( 7644): Expected native library version number "",actual native library version number ""
I/chromium( 7644): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=2946477577
I/BrowserStartupController( 7644): Initializing chromium process, singleProcess=true
W/art     ( 7644): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7644): ApplicationContext is null in ApplicationStatus
W/chromium( 7644): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7644): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7644): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7644): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7644): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7644): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7644): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7644): Remote Branch: 
I/Adreno-EGL( 7644): Local Patches: 
I/Adreno-EGL( 7644): Reconstruct Branch: 
,V/AudioPolicyService(  279): registerClient() client 0xb551cea0, uid 10079
,W/AudioManagerAndroid( 7644): Requires BLUETOOTH permission
I/NSApplication( 7644): Starting up...
,I/ActivityManager(  971): Killing 7365:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/art     ( 7661): CheckpointMarkThreadRoots callback created = 0xb04d3ed0
,I/art     ( 7661): CheckpointMarkThreadRoots callback created = 0xb04d3ec0
,W/libprocessgroup(  971): failed to open /acct/uid_10086/pid_7365/cgroup.procs: No such file or directory
,I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7728 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  971): Killing 7407:com.google.android.music:main/u0a81 (adj 15): empty #11
I/dex2oat ( 7726): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 7726): dex2oat took 99.012ms (threads: 4)
,I/Adreno-EGL( 7661): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7661): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7661): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7661): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7661): Remote Branch: 
I/Adreno-EGL( 7661): Local Patches: 
I/Adreno-EGL( 7661): Reconstruct Branch: 
,W/libprocessgroup(  971): failed to open /acct/uid_10081/pid_7407/cgroup.procs: No such file or directory
,W/ResourcesManager( 7728): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  971): Explicit concurrent mark sweep GC freed 16168(755KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.481ms total 141.225ms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  971): Killing 7430:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  971): failed to open /acct/uid_10036/pid_7430/cgroup.procs: No such file or directory
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5620): Restart initialization of location
E/MDM     ( 1732): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  971): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7761 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
,I/WVCdm   (  279): CdmEngine::OpenSession
,D/Finsky  ( 7761): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7761): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7761): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7761): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7761): com.android.vending: cancel(-1050172287) by com.android.vending
I/MusicWidget( 2751): mDelayedStopHandler : unbind
,V/DownloadManager( 3194): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@9c0d37e on behalf of 7761
,D/Finsky  ( 7761): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7761): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7761): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/MusicBrowser( 2108): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2108): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2108): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2108): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2108): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2108): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2108): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2108): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,D/Ads     ( 7761): Skipping gmscore version check
I/MediaFocusControl(  971):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@28e6d27acom.lge.music.MediaPlaybackService$6@2c4fa2b
,D/Finsky  ( 7761): [999] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7761): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/MusicBrowser( 2108): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2108): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2108): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2108): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2108): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@79c8c3b
I/MusicBrowser( 2108): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2108): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2108): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/ActivityManager(  971): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7815 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/MusicBrowser( 2108): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2108): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2108): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
V/LGMDMManager( 7389): Create singleton instance
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicBrowser( 2108): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2108): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2108): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2108): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2108): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/NotificationManager(  971): android: cancelAsUser(2) by android
I/MusicBrowser( 2108): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2108): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2108): reset
V/MediaPlayer[Native]( 2108): setListener
,V/MediaPlayer[Native]( 2108): disconnect
V/MediaPlayer[Native]( 2108): destructor
V/AudioFlinger(  279): releasing 19 from 2108 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2108): disconnect
D/MusicBrowser( 2108): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
,I/AudioManager( 7389): getMode name:com.lge.qremote
I/SmartShareClient( 2108): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2108): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2108): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2108): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2108): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2108): [SmartShareManagerClient] unregisterListener: 442093192
W/SmartShareClient( 2108): [SmartShareManagerClient] unregisterListener invalid listener: 442093192
I/SmartShareClient( 2108): [SmartShareManagerClient] terminate service: 2108/MediaPlaybackService/539718521
E/HomeCloudIF( 2108): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2108): [SmartShareManagerClient] unbindService context:android.app.Application@1a5a9021
,D/libc-netbsd( 7761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/UEI.SmartControl( 7815): Quickset Services start...
,I/UEI.SmartControl( 7815): Manufacture = LGE
D/UEI.SmartControl( 7815): File observer start...
E/UEI.SmartControl( 7815): IR Port is disabled: false
D/UEI.SmartControl( 7815): Starting file observer...
D/UEI.SmartControl( 7815): Extracting JNI libs...
D/UEI.SmartControl( 7815): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  971): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7835 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 7761): propertyValue:false
V/CloudHub( 2108): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2108): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2108): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2108): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2108): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  971): Killing 7477:com.lge.email/u0a21 (adj 15): empty #11
I/CloudHub( 2108): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
,D/UEI.SmartControl( 7815): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7815): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7815): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,W/libprocessgroup(  971): failed to open /acct/uid_10021/pid_7477/cgroup.procs: No such file or directory
I/UEI.SmartControl( 7815): --- Selecting new region: 2
I/UEI.SmartControl( 7815): -- Running on KitKat(19) and above! JNI will be used.
,I/WVCdm   (  279): CdmEngine::CloseSession
D/UEI.SmartControl( 7815): Platform has CIR...
D/UEI.SmartControl( 7815): NO CIR support, need to check package...
I/UEI.SmartControl( 7815): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7815): QS Service created
,E/UEI.SmartControl( 7815): QS start get config
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=3426062330
D/UEI.SmartControl( 7815): Loading JNI Libs...
,D/UEI.SmartControl( 7815):  configuring local db...
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7835): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7835): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  971): Killing 7514:com.lge.lgdmsclient/1000 (adj 15): empty #11
D/UEI.SmartControl( 7815):  ---- Has DB8: true
,D/UEI.SmartControl( 7815): QS start statue = true Error code = 0
D/UEI.SmartControl( 7815): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7815): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7815): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7815): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7815): IrrcClient ++ 
D/irrcClient( 7815): getIrrcService ++ 
D/irrcClient( 7815): getIrrcService -- 
D/irrcClient( 7815): IrrcClient -- 
W/irrc_jni( 7815): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7815): Services init done
I/UEI.SmartControl( 7815): Device manager: loading config....
D/UEI.SmartControl( 7815): Config is loaded...
W/libprocessgroup(  971): failed to open /acct/uid_1000/pid_7514/cgroup.procs: No such file or directory
,W/ActivityManager(  971): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/UEI.SmartControl( 7815): QS Service init finished
D/UEI.SmartControl( 7815): QS Service version name: 0.1.73
D/UEI.SmartControl( 7815): QS Service version code: 1073
D/UEI.SmartControl( 7815): Service requested: Control
D/UEI.SmartControl( 7815): Internal service binding...
D/UEI.SmartControl( 7815): -----IControl: 11
D/UEI.SmartControl( 7815): Caller: com.lge.qremote
D/UEI.SmartControl( 7815): ------------ IControl registerCallback...
,I/UEI.SmartControl( 7815): Registering callback...
W/ActivityManager(  971): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/UEI.SmartControl( 7815): -----IControl: 19
D/UEI.SmartControl( 7815): Caller: com.lge.qremote
I/UEI.SmartControl( 7815): Registering Services Ready callback...
I/UEI.SmartControl( 7815): Notify client services are ready...
D/UEI.SmartControl( 7815): -----IControl: 8
I/Gmail   ( 7835): Observing account changes for notifications
D/UEI.SmartControl( 7815): Caller: com.lge.qremote
,D/UEI.SmartControl( 7815):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7815): Notify AllClients services are ready: 0
E/Gmail   ( 7835): Error finding the version of the Email provider.....
E/Gmail   ( 7835): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7835): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7835): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7835): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7835): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7835): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7835): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7835): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7835): We do not support migrating this version of the Email provider.
I/AudioManager( 7389): getMode name:com.lge.qremote
,I/Gmail   ( 7835): getAccountsCursor
I/ActivityManager(  971): Killing 7537:com.lge.appbox.client/u0a11 (adj 15): empty #11
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup(  971): failed to open /acct/uid_10011/pid_7537/cgroup.procs: No such file or directory
,I/ActivityManager(  971): Killing 7556:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10038/pid_7556/cgroup.procs: No such file or directory
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  971): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7877 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  971): Killing 7581:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/art     (  303): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 288us total 24.090ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 23.683ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.538ms
,W/libprocessgroup(  971): failed to open /acct/uid_10051/pid_7581/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 7877): Register our PhoneStateListener
,I/ActivityManager(  971): Killing 7600:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7877): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7877): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7877): [parse] Load xml
V/TelephonyAutoProfiling( 7877): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7877): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7877): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/Gmail   ( 7835): notifyAccountChanged
,I/Gmail   ( 7835): getAccountsCursor
I/Gmail   ( 7835): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7835): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7835): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7835): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  971): failed to open /acct/uid_10061/pid_7600/cgroup.procs: No such file or directory
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 5620): Checkin interval check for package: unspecified last checkin: 1454591066636 min interval config: 0 actual interval: 37723
,I/AudioManager( 7389): getMode name:com.lge.qremote
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 5620): Checkin interval check for package: unspecified last checkin: 1454591066636 min interval config: 0 actual interval: 37763
E/MDM     ( 1732): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5620): Restart initialization of location
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
I/AudioManager( 7389): getMode name:com.lge.qremote
I/AudioManager( 7389): getMode name:com.lge.qremote
,I/AudioManager( 7389): getMode name:com.lge.qremote
,W/ContextImpl( 3624): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/AudioManager( 7389): getMode name:com.lge.qremote
I/AudioManager( 7389): getMode name:com.lge.qremote
,I/AudioManager( 7389): getMode name:com.lge.qremote
,I/Gmail   ( 7835): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): L3 Terminate.
I/Adreno-EGL( 7661): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7661): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7661): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7661): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7661): Remote Branch: 
I/Adreno-EGL( 7661): Local Patches: 
I/Adreno-EGL( 7661): Reconstruct Branch: 
,I/Adreno-EGL( 7661): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7661): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7661): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7661): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7661): Remote Branch: 
I/Adreno-EGL( 7661): Local Patches: 
I/Adreno-EGL( 7661): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5620): Classify the device as Phone.
,I/art     (  971): Explicit concurrent mark sweep GC freed 22544(1019KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.540ms total 149.177ms
,D/libc-netbsd( 5620): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5620): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5620): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5620): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 5620): propertyValue:false
D/libc-netbsd( 5620): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5620): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5620): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5620): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5620): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5620): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5620): Sending checkin request (9758 bytes)
,I/CheckinRequestBuilder( 5620): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5620): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5620): Classify the device as Phone.
,I/CheckinTask( 5620): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5620): Checking schedule, now: 1454591106458 next: 1455118355451
,I/CheckinService( 5620): active receiver: disabled
,I/CheckinService( 5620): Checking schedule, now: 1454591106487 next: 1455118355451
I/CheckinService( 5620): active receiver: disabled
,D/CheckinService( 5620): Recording last checkin time for package unspecified as 1454591106496
V/SetupWizard( 7877): Connected to Gservices successfully
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/GAV2    ( 7835): Thread[GAThread,5,main]: No campaign data found.
,D/UEI.SmartControl( 7815): Internal timer expired: 1
,I/ActivityManager(  971): Killing 7343:com.android.chrome/u0a48 (adj 15): empty #11
,I/ActivityManager(  971): Killing 7644:com.google.android.apps.magazines/u0a79 (adj 15): empty #12
,W/libprocessgroup(  971): failed to open /acct/uid_10048/pid_7343/cgroup.procs: No such file or directory
,W/libprocessgroup(  971): failed to open /acct/uid_10079/pid_7644/cgroup.procs: No such file or directory
I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  971): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  971): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7964 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  971): Handling package changes for user 0
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
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
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7964): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  971): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  971): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  971): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  971): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  971): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/BackupManagerService(  971): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2bf87a3d
,W/ResourcesManager(  971): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Babel_SMS( 7964): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7964): MmsConfig.loadMmsSettings
I/Babel_SMS( 7964): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 7964): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7964): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7964): MmsConfig.loadFromResources
E/Babel_SMS( 7964): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7964): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,W/ResourceType(  971): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager(  971): Process com.google.android.apps.plus (pid 7728) has died
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,D/SensorManager( 7964): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7964): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7964): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7964): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7964): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7964): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7964): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7964): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7964): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7964): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7964): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7964): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7964): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7964): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7964): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7964): found sensor: Motion Accel, handle=46
I/art     ( 7964): CheckpointMarkThreadRoots callback created = 0xb042d890
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/Settings( 7964): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7964): startup - clean
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  971): applying state to connected service
,I/art     ( 7964): CheckpointMarkThreadRoots callback created = 0xb042d870
,I/Babel   ( 7964): deleted: false for 0
,W/AudioCapabilities( 7964): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7964): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7964): Unsupported mime audio/g726
W/AudioCapabilities( 7964): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7964): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 7964): Unsupported mime video/mjpg
W/VideoCapabilities( 7964): Unsupported mime video/theora
,I/ActivityManager(  971): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8002 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/AudioCapabilities( 7964): Unsupported mime audio/evrc
,W/AudioCapabilities( 7964): Unsupported mime audio/qcelp
W/VideoCapabilities( 7964): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7964): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7964): Unsupported mime audio/qcelp
W/AudioCapabilities( 7964): Unsupported mime audio/evrc
,W/VideoCapabilities( 7964): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7964): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager(  971): Process com.android.vending (pid 7761) has died
W/VideoCapabilities( 7964): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7964): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7964): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7964): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 8002): onCreate
W/AppUp4:DB( 8002):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 8002):  setFingerPrint start
,I/AppUp4:DB( 8002):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
W/art     ( 7964): Suspending all threads took: 6.685ms
,I/AppUp4:DB( 8002):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8002):  SDK version = 0
I/AppUp4:DB( 8002):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8002): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 8002): onReceive
I/AppUp4:CustModeStarterReceiver( 8002): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 8002): Context : android.app.ReceiverRestrictedContext@10d4840
D/AppUp4:CustFacade( 8002): isCustomizationCompleted : false
D/AppUp4:CustFacade( 8002): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 8002): begin check event
I/AppUp4:CustModeStarterReceiver( 8002): Event For Nothing, skip.
I/ActivityManager(  971): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8023 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 7964): onServiceConnected
W/Babel   ( 7964): Attempted to change video mute state without an active call.
I/NotificationManager( 7964): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7964): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7964): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 8023): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8023): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 8023): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 7964): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/System  ( 7964): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7964): Installed default security provider GmsCore_OpenSSL
I/AppConfig( 8023): Total System Memory = 906309632
I/GalleryUtils( 8023): Application Heap = 96 MB
I/NotificationManager( 7964): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 8023): App Tier : NOT_DEF
D/SystemHelper( 8023): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  971): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8049 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  971): Process com.google.android.gm (pid 7835) has died
,W/ResourcesManager( 8049): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8049): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8049): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 8049): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 8049): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 8049): BUILD Country: EU
I/SystemConfig( 8049): BUILD Operator: OPEN
,I/ActivityManager(  971): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8071 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/SystemConfig( 8049): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 8049): existFile = false
,I/SystemConfig( 8049): canReadFile = false
I/SystemConfig( 8049): systemFeature RCS result false
D/SystemConfig( 8049): refreshRcsSupport() :false
,I/LockScreenSettings( 8071): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 8071): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 8071): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 8071): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 8071): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 8071): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  971): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8088 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Killing 2108:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  279): 2108 died, releasing its sessions
V/AudioFlinger(  279):  pid 1750 @ 0
V/AudioFlinger(  279):  pid 3246 @ 1
V/AudioFlinger(  279):  pid 3246 @ 2
,W/libprocessgroup(  971): failed to open /acct/uid_10028/pid_2108/cgroup.procs: No such file or directory
,W/ResourcesManager( 8088): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1960): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  971): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8112 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  971): Killing 7877:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1960): UpdateCorporaTask done [took 100 ms] updated apps [took 100 ms] 
,W/libprocessgroup(  971): failed to open /acct/uid_10038/pid_7877/cgroup.procs: No such file or directory
D/Finsky  ( 8112): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/Finsky  ( 8112): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8112): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 8112): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 8112): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3194): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3194): created cursor android.database.sqlite.SQLiteCursor@38fea0df on behalf of 8112
,I/art     ( 5470): Explicit concurrent mark sweep GC freed 3512(143KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 399us total 42.618ms
,D/Ads     ( 8112): Skipping gmscore version check
,D/Finsky  ( 8112): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 8112): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 8112): [1] Libraries$2.run: Finished loading 1 libraries.
D/PackageBroadcastService( 5620): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5620): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 8112): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5620): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 5620): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5620): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  971): Killing 7815:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7389): android.os.DeadObjectException
,W/System.err( 7389): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7389): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7389): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7389): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7389): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7389): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7389): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7389): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7389): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7389): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7389): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7389): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7389): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7389): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7389): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7389): android.os.DeadObjectException
W/System.err( 7389): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7389): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7389): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7389): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7389): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7389): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7389): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7389): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7389): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7389): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7389): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7389): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7389): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7389): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7389): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,D/charger_monitor(  475): init target 500000
,W/libprocessgroup(  971): failed to open /acct/uid_10089/pid_7815/cgroup.procs: No such file or directory
W/ActivityManager(  971): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  475): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ActivityManager(  971): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=8184 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,D/UEI.SmartControl( 8184): Quickset Services start...
,I/UEI.SmartControl( 8184): Manufacture = LGE
D/UEI.SmartControl( 8184): File observer start...
E/UEI.SmartControl( 8184): IR Port is disabled: false
D/UEI.SmartControl( 8184): Starting file observer...
D/UEI.SmartControl( 8184): Extracting JNI libs...
D/UEI.SmartControl( 8184): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 8184): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 8184): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 8184): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 8184): --- Selecting new region: 2
I/UEI.SmartControl( 8184): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 8184): Platform has CIR...
D/UEI.SmartControl( 8184): NO CIR support, need to check package...
I/UEI.SmartControl( 8184): Model: LG-D722 uses JNI
D/UEI.SmartControl( 8184): QS Service created
E/UEI.SmartControl( 8184): QS start get config
,D/UEI.SmartControl( 8184): Loading JNI Libs...
,D/UEI.SmartControl( 8184):  configuring local db...
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:05:14.14 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 8184):  ---- Has DB8: true
,D/UEI.SmartControl( 8184): QS start statue = true Error code = 0
D/UEI.SmartControl( 8184): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 8184): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 8184): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 8184): IRRCPlayer_nativeInit ++ 
D/irrcClient( 8184): IrrcClient ++ 
D/irrcClient( 8184): getIrrcService ++ 
D/irrcClient( 8184): getIrrcService -- 
D/irrcClient( 8184): IrrcClient -- 
W/irrc_jni( 8184): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 8184): Services init done
,I/UEI.SmartControl( 8184): Device manager: loading config....
D/UEI.SmartControl( 8184): QS Service init finished
D/UEI.SmartControl( 8184): Config is loaded...
D/UEI.SmartControl( 8184): QS Service version name: 0.1.73
D/UEI.SmartControl( 8184): QS Service version code: 1073
D/UEI.SmartControl( 8184): Service requested: Control
I/ActivityManager(  971): Killing 7661:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,D/UEI.SmartControl( 8184): -----IControl: 11
D/UEI.SmartControl( 8184): Caller: com.lge.qremote
D/UEI.SmartControl( 8184): ------------ IControl registerCallback...
I/UEI.SmartControl( 8184): Registering callback...
D/UEI.SmartControl( 8184): -----IControl: 19
D/UEI.SmartControl( 8184): Caller: com.lge.qremote
I/UEI.SmartControl( 8184): Registering Services Ready callback...
I/UEI.SmartControl( 8184): Notify client services are ready...
D/UEI.SmartControl( 8184): -----IControl: 8
D/UEI.SmartControl( 8184): Caller: com.lge.qremote
D/UEI.SmartControl( 8184):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 8184): Notify AllClients services are ready: 0
,W/libprocessgroup(  971): failed to open /acct/uid_10006/pid_7661/cgroup.procs: No such file or directory
D/UEI.SmartControl( 8184): Internal service binding...
I/AudioManager( 7389): getMode name:com.lge.qremote
I/art     (  971): Explicit concurrent mark sweep GC freed 30499(1535KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.347ms total 163.227ms
,I/AudioManager( 7389): getMode name:com.lge.qremote
,I/AudioManager( 7389): getMode name:com.lge.qremote
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  971): Killing 8002:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  971): failed to open /acct/uid_10011/pid_8002/cgroup.procs: No such file or directory
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:05:17.154 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 8184): Internal timer expired: 1
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 134409677402; DSPS: 4503180; Offset : -3020504068
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
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
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{2d926684 type 2 when 144809 com.google.android.gms} when 144809
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 33912(2MB) AllocSpace objects, 30(480KB) LOS objects, 40% free, 13MB/22MB, paused 2.175ms total 99.765ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1732): Vacuum at: now=1454591131853 tag=VacuumService
I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 5115 seconds from now (1454591132259)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  971): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  971): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LocationManagerService(  971): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  971): android: cancelAsUser(2) by android
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  971): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  971): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  971): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-75 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:05:35.228 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_2_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_2_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:05:38.252 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 154410784582; DSPS: 5158577; Offset : -3020525987
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-67 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:05:44.279 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:05:47.294 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  971): ALS enabled for SRE
D/PowerManagerServiceEx(  971): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (47568 ms ago)
,D/qdlights(  971): set_light_backlight: 251
,D/qdlights(  971): set_light_backlight: 248
,D/qdlights(  971): set_light_backlight: 245
,D/qdlights(  971): set_light_backlight: 241
,D/qdlights(  971): set_light_backlight: 238
,D/qdlights(  971): set_light_backlight: 235
,D/qdlights(  971): set_light_backlight: 231
,D/qdlights(  971): set_light_backlight: 228
,D/qdlights(  971): set_light_backlight: 225
,D/qdlights(  971): set_light_backlight: 221
,D/qdlights(  971): set_light_backlight: 218
,D/qdlights(  971): set_light_backlight: 215
,D/qdlights(  971): set_light_backlight: 211
,D/qdlights(  971): set_light_backlight: 208
,D/qdlights(  971): set_light_backlight: 205
,D/qdlights(  971): set_light_backlight: 201
,D/qdlights(  971): set_light_backlight: 198
,D/qdlights(  971): set_light_backlight: 195
,D/qdlights(  971): set_light_backlight: 191
,D/qdlights(  971): set_light_backlight: 188
,D/qdlights(  971): set_light_backlight: 185
,D/qdlights(  971): set_light_backlight: 181
,D/qdlights(  971): set_light_backlight: 178
,D/qdlights(  971): set_light_backlight: 175
,D/qdlights(  971): set_light_backlight: 171
,D/qdlights(  971): set_light_backlight: 168
,D/qdlights(  971): set_light_backlight: 165
,D/qdlights(  971): set_light_backlight: 161
,D/qdlights(  971): set_light_backlight: 158
,D/qdlights(  971): set_light_backlight: 155
,D/qdlights(  971): set_light_backlight: 151
,D/qdlights(  971): set_light_backlight: 148
,D/qdlights(  971): set_light_backlight: 145
,D/qdlights(  971): set_light_backlight: 141
,D/qdlights(  971): set_light_backlight: 138
,D/qdlights(  971): set_light_backlight: 135
,D/qdlights(  971): set_light_backlight: 131
,D/qdlights(  971): set_light_backlight: 128
,D/qdlights(  971): set_light_backlight: 125
,D/qdlights(  971): set_light_backlight: 121
,D/qdlights(  971): set_light_backlight: 118
,D/qdlights(  971): set_light_backlight: 115
,D/qdlights(  971): set_light_backlight: 111
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/qdlights(  971): set_light_backlight: 108
D/qdlights(  971): set_light_backlight: 105
,D/qdlights(  971): set_light_backlight: 101
,D/qdlights(  971): set_light_backlight: 98
,D/qdlights(  971): set_light_backlight: 95
,D/qdlights(  971): set_light_backlight: 91
,D/qdlights(  971): set_light_backlight: 88
,D/qdlights(  971): set_light_backlight: 85
,D/qdlights(  971): set_light_backlight: 81
,D/qdlights(  971): set_light_backlight: 78
,D/qdlights(  971): set_light_backlight: 75
,D/qdlights(  971): set_light_backlight: 71
,D/qdlights(  971): set_light_backlight: 68
,D/qdlights(  971): set_light_backlight: 65
,D/qdlights(  971): set_light_backlight: 61
,D/qdlights(  971): set_light_backlight: 58
,D/qdlights(  971): set_light_backlight: 55
,D/qdlights(  971): set_light_backlight: 51
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/qdlights(  971): set_light_backlight: 48
D/qdlights(  971): set_light_backlight: 45
,D/qdlights(  971): set_light_backlight: 41
,D/qdlights(  971): set_light_backlight: 38
,D/qdlights(  971): set_light_backlight: 35
,D/qdlights(  971): set_light_backlight: 31
,D/qdlights(  971): set_light_backlight: 28
,D/qdlights(  971): set_light_backlight: 25
,D/qdlights(  971): set_light_backlight: 21
,D/qdlights(  971): set_light_backlight: 18
,D/qdlights(  971): set_light_backlight: 15
,D/qdlights(  971): set_light_backlight: 11
,D/qdlights(  971): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-68 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:05:56.332 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-04 14:05:59.353 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/PowerManagerServiceEx(  971): acquireWakeLockInternal: lock=982788684, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=971
,D/WeatherService( 2780): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:6:0
D/WeatherService( 2780): 2 : TimeTick Intent And Screen On
D/WeatherService( 2780): 2 : SDK version : 21
W/ActivityManager(  971): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2780): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2780): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2780): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2780): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2780): 2 : This is isUpdating : false
D/WeatherService( 2780): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2780): 2 : buildUpdate, appWidgetId: 2
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
D/WeatherTheme( 2780): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2780): 2 : Fixed theme : optimus
D/WeatherReflect( 2780): 2 : Map key string is -2
,D/lim     ( 2780): 2 : time = 14:06
I/WeatherReflect( 2780): Model Name : LG-D722
D/WeatherTheme( 2780): 2 : Different view - status_min_formatted : 05 != 06
D/WeatherTheme( 2780): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2780): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2780): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2780): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/Weather4x2_optimus( 2780): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2780): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2780): forecast size is 0
,D/Theme   ( 2780): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2780): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2780): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2780): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2780): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2780): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2780): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2780): url is : null
D/Theme   ( 2780): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2780): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2780): 2 : update view, appWidgetId: 2
D/WeatherService( 2780): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:6:0
,D/PowerManagerServiceEx(  971): releaseWakeLockInternal: lock=982788684 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 174411526502; DSPS: 5813961; Offset : -3020516775
,I/PowerManagerService(  971): ALS enabled for SRE
D/PowerManagerServiceEx(  971): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (54556 ms ago)
I/PowerManagerService(  971): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  971): ALS enabled for SRE
D/PowerManagerServiceEx(  971): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (54570 ms ago)
,W/ContextImpl(  971): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  971): Sleeping (uid 1000)...
,D/LPWGController(  971): [updateScreenState] screen on = false
D/LPWGController(  971): disable proximity sensor
D/LPWGController(  971): enable proximity sensor
,I/SensorManager(  971): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@18c15a95] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  971): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  971): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  971): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  971): activate: handle is 48, enable
,V/sensors_hal_Ctx(  971): activate sensors is 1400000000000
D/sensors_hal_Thresh(  971): enable: handle=48
I/sensors_hal_SAM(  971): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  971): waitForResponse: timeout=1000
V/sensors_hal_SAM(  971): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  971): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Thresh(  971): enable: Received response: 0
D/PowerManagerServiceEx(  971): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (54638 ms ago)
I/Adreno-EGL(  971): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  971): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  971): Build Date: 03/02/15 Mon
I/Adreno-EGL(  971): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  971): Remote Branch: 
I/Adreno-EGL(  971): Local Patches: 
I/Adreno-EGL(  971): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (535 us)
,I/Sensors (  418): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  971): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  971): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  971): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  971): processInd: handle 48, count=1
V/sensors_hal_Thresh(  971): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  971): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  971): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  971): poll: count: 256
I/sensors_hal_Ctx(  971): poll: released wakelock sensor_ind
D/sensors_hal_Util(  971): waitForResponse: timeout=0
D/LPWGController(  971): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  971): current mode = 1  value = 1 1
,I/LPWGController(  971): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  971): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  971): set_light_backlight: 0
,I/SensorManager(  971): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  971): activate: handle is 46, disable
V/sensors_hal_Ctx(  971): activate sensors is 1000000000000
D/sensors_hal_LP2(  971): enable: handle=46
D/sensors_hal_LP2(  971): enable: Disabling sensor handle=46
,I/sensors_hal_SAM(  971): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  971): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  971): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  971): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  971): Display changed displayId=0
,D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
D/SurfaceControl(  971): Excessive delay in setPowerMode(): 231ms
,I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  971): Got set_interactive hint
D/KeyguardViewMediator( 1372): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1372): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1372): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1372): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1372): unregisterProximitySensor
,D/WifiServerServiceExt(  971): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1372): onScreenTurnedOff why = 3
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 971
I/WifiServerServiceExt(  971): set CMD_KT_SCAN_INTERVAL
D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=on
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
V/voice   (  279): voice_set_parameters: enter: screen_state=on
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: exit
V/voice   (  279): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  279): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  279): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  279): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  279): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  279): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  279): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  279): adev_set_parameters: exit with code(0)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,D/GpsLocationProvider(  971): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:true
I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1802): stopPatternFlashing()
,D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): updateLightsLocked : turn off led
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1802): RESTART MSG
,D/SplitWindow(  971): check instance of lgWin Window{20ff9f38 u0 SearchPanel}
,D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1802): lockStatus = 0
D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
,D/LNfcService( 1785): isRequireNfcCRouting() return true
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
D/InputDispatcher(  971): Window went away: Window{384c7826 u0 SearchPanel}
,I/[SystemUI]Clock( 1372): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
,D/Ulp_jni (  971): JNI:system_update. Event-0
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): ACTION_SCREEN_ON
,D/WeatherService( 2780): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:6:2
D/WeatherService( 2780): 2 : ACTION screen on
D/WeatherService( 2780): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2780): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2780): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:6:2
D/AppCleanupService( 4098): android.intent.action.SCREEN_ON
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 971
D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=off
V/voice   (  279): voice_set_parameters: enter: screen_state=off
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  279): voice_extn_compress_voip_set_parameters: exit
V/voice   (  279): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  279): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  279): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  279): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  279): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  279): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  279): adev_set_parameters: exit with code(0)
,D/WifiController(  971): CMD_SCREEN_OFF 
D/WifiController(  971): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  971): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:false
,I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1802): clear
I/LEDService( 1802): updateLightsLocked : turn on led
E/LEDService( 1802): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1802): Can't handle this request of patternId:0
D/LEDHandler( 1802): RESTART MSG
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1876): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  971): ACTION_SCREEN_OFF
D/WeatherService( 2780): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:6:2
D/WeatherService( 2780): 2 : ACTION screen off
E/NxpNfcJni( 1785): getReconnectState = 0x0
,D/WeatherService( 2780): 2 : TimeTick Receiver Unregister
D/WeatherService( 2780): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:6:2
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true,
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: 0
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 1
D/AppCleanupService( 4098): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4098): AppUsageStatsSaveTask
,E/NxpNfcJni( 1785): getReconnectState = 0x0
,I/Sensors (  418): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1372): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{caa0b11 type 2 when 180508 com.android.systemui} when 180508
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1372): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1372): doKeyguard: not showing because lockscreen is off
V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{13ec1476 type 2 when 183119 android} when 183119
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  475): init target 500000
,D/charger_monitor(  475): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 194412291910; DSPS: 6469346; Offset : -3020514099
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  971): ELAPSED_WAKEUP set : Alarm{3304da77 type 2 when 205974 com.google.android.gms} when 205974
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 214413028673; DSPS: 7124730; Offset : -3020509992
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 234413780177; DSPS: 7780115; Offset : -3020521452
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  475): init target 500000
,D/charger_monitor(  475): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2035): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  971): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  971): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  971): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 254414458658; DSPS: 8435497; Offset : -3020514306
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 274415225422; DSPS: 9090882; Offset : -3020510483
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5735): --= Surplus to requirements =--
I/jxcore-log( 5735): 
I/jxcore-log( 5735): ****TEST TOOK:  ms ****
I/jxcore-log( 5735): 
I/jxcore-log( 5735): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5735): 
,D/sensors_hal_Time(  971): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  971): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  971): tsOffsetIs: Apps: 294415899008; DSPS: 9746264; Offset : -3020508387
,D/AndroidRuntime( 8350): 
D/AndroidRuntime( 8350): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8350): CheckJNI is OFF
,D/AndroidRuntime( 8350): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  971): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  971): Killing 5735:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
,I/WindowState(  971): WIN DEATH: Window{3a670196 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  971): Focus left window: Window{3a670196 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  971): Window went away: Window{3a670196 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  971): Skipping PackageSetting{3a1e2320 com.example.hello/10317} due to missing metadata
,I/ActivityManager(  971):   Force finishing activity ActivityRecord{26fb795f u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  971): Display changed displayId=0
,D/DSDPConnection( 1750): Display #0 changed.
W/ActivityManager(  971): Spurious death for ProcessRecord{22ab76e4 5735:com.test.thalitest/u0a316}, curProc for 5735: null
I/ActivityManager(  971): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,I/ActivityManager(  971):   Force finishing activity ActivityRecord{26fb795f u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  971): Duplicate finish request for ActivityRecord{26fb795f u0 com.test.thalitest/.MainActivity t222 f}
,I/[LGHome]EVENT( 1876): [Launcher.java:5203:onStart()]onStart
,D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1876): [Launcher.java:776:onResume()]onResume
,I/art     ( 5620): Explicit concurrent mark sweep GC freed 6583(344KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 13MB/17MB, paused 852us total 94.039ms
I/art     ( 1960): Explicit concurrent mark sweep GC freed 7133(412KB) AllocSpace objects, 1(23KB) LOS objects, 40% free, 12MB/21MB, paused 9.560ms total 104.049ms
W/System.err( 3624): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
,W/System.err( 3624): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3624): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3624): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
I/InputReader(  971): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 3624): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3624): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3624): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3624): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3624): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3624): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3624): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3624): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  971): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8380 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
,I/[LGHome]LGActivityUtil( 1876): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1876): [Launcher.java:929:onResume()]onResume end
I/Activity( 1876): Activity.onPostResume() called 
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
,W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
,W/[LGHome]LGWallpaperInfo( 1876): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1876): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/art     (  971): Explicit concurrent mark sweep GC freed 50722(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 6.414ms total 251.767ms
I/art     (  971): WaitForGcToComplete blocked for 212.645ms for cause Explicit
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework](  971): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1372): handleShortcutListChanged...
,D/InputDispatcher(  971): Focus entered window: Window{10285e1c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  971): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  971): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  971): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  971): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@26ab6a9d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  971): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  971): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  971): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  971): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  971): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  971): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@26ab6a9d,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  971): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
,D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1372): handleShortcutListChanged...
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1876): [setNavigationBarColor] color=0x 0
W/ResourcesManager( 8380): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8380): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8380): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/administrator(  971): Handling package changes for user 0
,I/LGEmail ( 8380): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,W/InputMethodManagerService(  971): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,D/LGEmail ( 8380): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/InputMethodManagerService(  971): Got RemoteException sending setActive(false) notification to pid 5735 uid 10316
I/art     (  971): Explicit concurrent mark sweep GC freed 8704(493KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.830ms total 268.103ms
,I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  971): Timeline: Activity_windows_visible id: ActivityRecord{5fe27a8 u0 com.lge.launcher2/.Launcher t221} time:296236
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/NotificationService(  971): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  971): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/JobSchedulerService(  971): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  971): removeObsoleteFile: deleting file=222_task.xml
,D/PhoneStatusBar( 1372): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
,I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
W/IInputConnectionWrapper( 1876): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1621): Unable to connect to the editor to retrieve text... will retry later
D/AndroidRuntime( 8350): Shutting down VM
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,W/IInputConnectionWrapper( 1876): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
,W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
,W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,I/PackageChangeReceiver( 8380): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,W/ResourcesManager(  971): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  971): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8407 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  971): Killing 7964:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  971): failed to open /acct/uid_10061/pid_7964/cgroup.procs: No such file or directory
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/AppUp4:AppBoxCP( 8407): onCreate
,W/AppUp4:DB( 8407):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 8407):  setFingerPrint start
I/AppUp4:DB( 8407):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 8407):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8407):  SDK version = 0
I/AppUp4:DB( 8407):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8407): AppBoxApplication onCreate()
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
D/AppUp4:PreloadHelper( 8407): added Exclude : com.test.thalitest
,I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourceType(  971): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  971): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8427 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  971): Killing 8023:com.android.gallery3d/u0a23 (adj 15): empty #11
I/art     (  303): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 322us total 23.185ms
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created

```
