#### Test 58380500c26a9ef_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
V/JNIHelp ( 5403): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 5403): CheckpointMarkThreadRoots callback created = 0xaaf2a360
W/System  ( 5403): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5403): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
--------- beginning of system
V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{dd2ec75 type 2 when 80234 android} when 80234
I/ActivityManager(  847): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5479 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/GservicesProvider( 5479): Gservices pushing to system: true; secure/global: true
I/ActivityManager(  847): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5500 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1942): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/art     ( 1942): Suspending all threads took: 11.047ms
I/art     ( 1942): Background sticky concurrent mark sweep GC freed 15456(1157KB) AllocSpace objects, 12(254KB) LOS objects, 8% free, 13MB/14MB, paused 16.079ms total 96.415ms
I/GoogleHttpClient( 5479): GMS http client unavailable, use old client
D/AndroidRuntime( 5472): 
D/AndroidRuntime( 5472): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5472): CheckJNI is OFF
I/GoogleHttpClient( 5479): GMS http client unavailable, use old client
I/ActivityManager(  847): Killing 5233:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10014/pid_5233/cgroup.procs: No such file or directory
I/ActivityManager(  847): Killing 5255:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10021/pid_5255/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 1942): UpdateCorporaTask done [took 337 ms] updated apps [took 159 ms] updated contacts [took 178 ms]
D/AndroidRuntime( 5472): Calling main entry com.android.commands.am.Am
I/ActivityManager(  847): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/Finsky  ( 5500): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ActivityManager(  847): setTaskToReturnTo : TaskRecord{62edd57 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  847): setTaskToReturnTo : TaskRecord{62edd57 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  847): AppWindowTokenEx init.. 
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/ContextHelper(  847): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  847): Focus left window: Window{36713c96 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5472): Shutting down VM
D/SplitWindow(  847): check instance of lgWin Window{1eb0f729 u0 Starting com.test.thalitest}
I/ActivityManager(  847): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5545 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1942): Closing mic
I/MicrophoneInputStream( 1942): mic_close com.google.android.apps.gsa.speech.audio.u@32aa2d6f
V/AudioRecord( 1942): stop()
D/AudioRecord( 1942): AudioRecord->stop()
V/AudioFlinger(  275): RecordHandle::stop()
V/AudioFlinger(  275): RecordThread::stop
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
V/AudioFlinger(  275): Record stopped OK
V/AudioPolicyManager(  275): stopInput() input 16
V/AudioPolicyService(  275): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  275): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  275): AudioCommandThread() waking up
V/AudioPolicyService(  275): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  275): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  275): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  275): ThreadBase::setParameters() routing=0
V/AudioFlinger(  275): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  275): processConfigEvents_l() remaining events 1
V/AudioFlinger(  275): processConfigEvents_l() DONE thread 0xb3824000
D/audio_hw_primary(  275): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
I/WindowStateAnimator(  847): Starting window displayed
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1368): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1cb9f889,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1368): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1368):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1368): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1368): draw background and invalidate : color = e000000
D/BarTransitions( 1368): draw background and invalidate : color = 100f0f0f
V/audio_hw_primary(  275): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  275): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  275): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  275): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  275): disable_audio_route: exit
E/audio_hw_primary(  275): disable_snd_device: enter 144
D/hardware_info(  275): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  275): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  275): stop_input_stream: exit: status(0)
V/audio_hw_primary(  275): in_standby: exit:  status(0)
V/AudioFlinger(  275): RecordThread: loop stopping
V/AudioPolicyService(  275): AudioCommandThread() going to sleep
V/AudioPolicyManager(  275): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  275): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  275): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  275): inserting command: 10 at index 0, num commands 0
,V/AudioPolicyService(  275): AudioCommandThread() waking up
V/AudioPolicyService(  275): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  275): AudioCommandThread() going to sleep
V/AudioPolicyService(  275): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  275): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  275): AudioCommandThread() waking up
V/AudioPolicyService(  275): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  275): setParameters(): io 16, keyvalue hotword_active=0, calling pid 275
V/AudioFlinger(  275): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  275): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  275): RecordThread: loop starting
V/AudioFlinger(  275): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  275): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  275): in_set_parameters: exit: status(0)
V/AudioFlinger(  275): processConfigEvents_l() DONE thread 0xb3824000
V/AudioFlinger(  275): RecordThread: loop stopping
V/AudioPolicyService(  275): AudioCommandThread() going to sleep
V/AudioRecord( 1942): stop()
V/AudioRecord( 1942): stop()
V/AudioRecord( 1942): stop()
V/AudioFlinger(  275): RecordHandle::stop()
V/AudioFlinger(  275): RecordThread::stop
V/AudioPolicyManager(  275): releaseInput() 16
V/AudioPolicyManager(  275): closeInput(16)
V/AudioFlinger(  275): releasing 15 from 1942 for -1
V/AudioFlinger(  275):  decremented refcount to 0
V/AudioFlinger(  275): purging stale effects
V/AudioFlinger(  275): closeInput() 16
V/AudioSystem(  275): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1368): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  847): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  275): ThreadBase::exit
V/AudioFlinger(  275): RecordThread: loop starting
V/AudioSystem( 1942): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2787): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1970): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  275): RecordThread 0xb3824000 exiting
V/AudioSystem( 1747): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  275): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  275): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  275): in_standby: exit:  status(0)
V/AudioSystem( 3223): ioConfigChanged() event 4, ioHandle 16
V/AudioPolicyService(  275): AudioCommandThread() adding update audio port list
I/HotwordRecognitionRnr( 1942): Stopping hotword detection.
V/AudioPolicyService(  275): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  275): releaseInput() exit
V/AudioPolicyService(  275): AudioCommandThread() waking up
V/AudioFlinger(  275): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  275): AudioCommandThread() processing update audio port list
V/AudioFlinger(  275): removeClient_l() pid 1942, calling pid 275
V/AudioPolicyService(  275): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1942): Hotword detection finished
D/ContextHelper( 5545): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/Finsky  ( 5500): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 5500): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5500): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5500): com.android.vending: cancel(-1050172287) by com.android.vending
I/WebViewFactory( 5545): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@3a7f2de1 on behalf of 5500
I/NotificationManager( 5500): com.android.vending: cancel(1003285959) by com.android.vending
D/Finsky  ( 5500): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5500): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 5500): Skipping gmscore version check
I/LibraryLoader( 5545): Time to load native libraries: 2 ms (timestamps 1594-1596)
I/LibraryLoader( 5545): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5545): Binding Chromium to main looper Looper (main, tid 1) {27853fd0}
I/ActivityManager(  847): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5587 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/LibraryLoader( 5545): Expected native library version number "",actual native library version number ""
I/chromium( 5545): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5545): Initializing chromium process, singleProcess=true
W/art     ( 5545): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5545): ApplicationContext is null in ApplicationStatus
D/Finsky  ( 5500): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 5500): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5500): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  847): Killing 5282:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10009/pid_5282/cgroup.procs: No such file or directory
W/chromium( 5545): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5545): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5545): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5545): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5545): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5545): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5545): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5545): Remote Branch: 
I/Adreno-EGL( 5545): Local Patches: 
I/Adreno-EGL( 5545): Reconstruct Branch: 
W/ResourcesManager( 5587): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5587): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/AudioPolicyService(  275): registerClient() client 0xb551c6e0, uid 10316
D/BluetoothManagerService(  847): Message: 20
D/BluetoothManagerService(  847): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2be1bb3f:true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
,I/MultiDex( 5587): VM with version 2.1.0 has multidex support
I/MultiDex( 5587): install
I/MultiDex( 5587): VM has multidex support, MultiDex support library is disabled.
W/art     ( 5545): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5545): onDetachedFromWindow called when already detached. Ignoring
,V/JNIHelp ( 5587): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/SystemWebViewEngine( 5545): CordovaWebView is running on device made by: LGE
W/art     ( 5545): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 5545): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityThread( 5587): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5587): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@37fe0da8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5587): Installed default security provider GmsCore_OpenSSL
I/Activity( 5545): Activity.onPostResume() called 
I/NotificationManager( 5587): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5587): com.google.android.gms: cancel(39789) by com.google.android.gms
D/OpenGLRenderer( 5545): Render dirty regions requested: true
I/OpenGLRenderer( 5545): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5545): Enabling debug mode 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/Atlas   ( 5545): Validating map...
D/charger_monitor(  487): init target 500000
,D/SplitWindow(  847): check instance of lgWin Window{2e99a541 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5545): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/ChimeraCfgMgr( 5587): Reading stored module config
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/PackageBroadcastService( 5587): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/InputDispatcher(  847): Focus entered window: Window{2e99a541 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  847): battery changed pluggedType: 2
W/MainApplication( 5157): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
D/charger_monitor(  487): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/MainApplication( 5157): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ChimeraCfgMgr( 5587): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5587): Loading module APK com.google.android.play.games
,W/InputMethodManagerService(  847): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  847): Displayed com.test.thalitest/.MainActivity: +1s268ms
I/Timeline(  847): Timeline: Activity_windows_visible id: ActivityRecord{31aef044 u0 com.test.thalitest/.MainActivity t222} time:82393
I/Timeline( 5545): Timeline: Activity_idle id: android.os.BinderProxy@1ccb48df time:82417
,W/art     ( 5587): Suspending all threads took: 7.702ms
,W/BindingManager( 5545): Cannot call determinedVisibility() - never saw a connection for the pid: 5545
,D/NativeLibraryUtils( 5587): Install completed successfully. count=14 extracted=0
I/art     ( 5587): CheckpointMarkThreadRoots callback created = 0xb042d460
,I/art     ( 5587): CheckpointMarkThreadRoots callback created = 0xb042d440
,D/JsMessageQueue( 5545): Set native->JS mode to OnlineEventsBridgeMode
,D/ChimeraCfgMgr( 5587): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5587): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 5587): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5587): Submit a task: k
,D/ChimeraCfgMgr( 5587): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/PeopleDatabaseHelper( 5587): cleanUpNonGplusAccounts done.
,D/ChimeraCfgMgr( 5587): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 5587): Processing package: com.test.thalitest
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,D/GassUtils( 5587): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5587): Found info for package com.test.thalitest in db.
W/BaseAppContext( 5587): Using Auth Proxy for data requests.
I/Icing   ( 5587): Storage manager: low false usage 1.74MB avail 2.38GB capacity 4.06GB
,D/WearableService( 1734): callingUid 10006, callindPid: 1734
,E/MDM     ( 1734): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/art     ( 5587): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5587): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/BaseAppContext( 5587): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5587): Using Auth Proxy for data requests.
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/BaseAppContext( 5587): Using Auth Proxy for data requests.
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5587): Restart initialization of location
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  847): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5684 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 23.203ms
,W/BaseAppContext( 5587): Using Auth Proxy for data requests.
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 304us total 22.483ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 24.379ms
,W/BaseAppContext( 5587): Using Auth Proxy for data requests.
W/BaseAppContext( 5587): Using Auth Proxy for data requests.
,W/BaseAppContext( 5587): Using Auth Proxy for data requests.
,D/jxcore_app_log( 5545): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426135552
,I/chromium( 5545): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
W/IcingInternalCorpora( 5587): getNumBytesRead when not calculated.
,I/art     ( 5545): Background sticky concurrent mark sweep GC freed 22322(1731KB) AllocSpace objects, 4(60KB) LOS objects, 3% free, 11MB/11MB, paused 6.885ms total 65.981ms
,I/art     ( 5545): CheckpointMarkThreadRoots callback created = 0x9c149500
,I/art     ( 5545): CheckpointMarkThreadRoots callback created = 0x9c1494d0
,I/art     ( 5587): Background sticky concurrent mark sweep GC freed 16200(1456KB) AllocSpace objects, 14(224KB) LOS objects, 11% free, 12MB/14MB, paused 6.129ms total 71.977ms
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Icing   ( 5587): updateResources: need to parse f{com.google.android.gms}
,I/Gmail   ( 5684): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5684): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/art     (  847): Explicit concurrent mark sweep GC freed 28491(1410KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.315ms total 227.600ms
W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5684): Error finding the version of the Email provider.....
E/Gmail   ( 5684): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5684): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5684): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5684): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5684): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5684): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5684): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5684): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5684): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5684): getAccountsCursor
I/ActivityManager(  847): Killing 5304:com.lge.appbox.client/u0a11 (adj 15): empty #11
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 5587): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5587): Module APK com.google.android.play.games already loaded
,D/InitAlarmsService( 3785): Clearing and rescheduling alarms.
,W/libprocessgroup(  847): failed to open /acct/uid_10011/pid_5304/cgroup.procs: No such file or directory
,W/ActivityManager(  847): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5684): Observing account changes for notifications
I/ActivityManager(  847): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5731 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
,I/Icing   ( 5587): Internal init done: storage state 0
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@5274706 on behalf of 5587
W/ResourcesManager( 5731): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/NotificationManager( 5587): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 5479): Explicit concurrent mark sweep GC freed 7889(397KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.035ms total 79.711ms
,D/CalendarProvider2( 5731): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@307f2ef7
,I/ActivityManager(  847): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5761 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
W/InstanceID/Rpc( 5587): Found 10006
,W/InstanceID/Rpc( 5587): Found 10006
D/CalendarProvider2( 5731): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5731): Created com.android.providers.calendar.CalendarAlarmManager@27853fd0(com.android.providers.calendar.CalendarProvider2@307f2ef7)
I/Icing   ( 5587): Post-init done
,D/CalendarProvider2( 5731): Scheduling check of next Alarm
,I/ActivityManager(  847): Process com.android.contacts (pid 5349) has died
,I/Gmail   ( 5684): notifyAccountChanged
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@1e0141c7 on behalf of 5587
D/CalendarProvider2( 5731): SCHEDULE_ALARM_REMOVE
I/Gmail   ( 5684): getAccountsCursor
I/Gmail   ( 5684): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5684): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@f7dd3f4 on behalf of 5587
I/Gmail   ( 5684): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5684): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PhoneMonitor( 5761): Register our PhoneStateListener
,I/ActivityManager(  847): Process com.android.calendar (pid 3785) has died
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PhoneMonitor( 5761): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5761): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 5761): [parse] Load xml
V/TelephonyAutoProfiling( 5761): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5761): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5761): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 5587): Checkin interval check for package: unspecified last checkin: 1454983570908 min interval config: 0 actual interval: 7609
,I/CheckinService( 5587): Disabling old GoogleServicesFramework version
,I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5791 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/CheckinService( 5587): Checking schedule, now: 1454983578653 next: 1454983600824
I/CheckinService( 5587): active receiver: disabled
,I/ActivityManager(  847): Process com.lge.bnr (pid 5157) has died
,I/Gmail   ( 5684): getAccountsCursor
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5791): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/jxcore-log( 5545): Initializing JXcore engine
,W/jxcore-log( 5545): JXcore engine is ready
,W/Thread-672( 5705): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7355]" dev="sockfs" ino=7355 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-672( 5705): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,W/Thread-672( 5705): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8805]" dev="sockfs" ino=8805 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-672( 5705): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-672( 5705): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-672( 5705): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[27816]" dev="sockfs" ino=27816 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5545): Starting JXcore engine
I/Babel_SMS( 5791): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5791): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5791): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5791): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5791): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5791): MmsConfig.loadFromResources
E/Babel_SMS( 5791): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5791): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5791): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 5791): found sensor: LGE Magnetometer Sensor, handle=10
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
I/art     ( 5791): CheckpointMarkThreadRoots callback created = 0xb045d640
,W/Settings( 5791): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/jxcore-log( 5545): Platform android
W/jxcore-log( 5545): 
W/jxcore-log( 5545): Process ARCH arm
W/jxcore-log( 5545): 
I/Babel_Crash( 5791): startup - clean
,I/art     ( 5791): CheckpointMarkThreadRoots callback created = 0xb045d620
,I/Icing   ( 5587): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Babel   ( 5791): deleted: false for 0
,I/CalendarProvider2( 5731): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5731): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/Icing   ( 5587): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5587): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/AudioCapabilities( 5791): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5791): Unsupported mime audio/adpcm
W/AudioCapabilities( 5791): Unsupported mime audio/g726
W/AudioCapabilities( 5791): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5791): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 5791): Unsupported mime video/mjpg
W/VideoCapabilities( 5791): Unsupported mime video/theora
W/AudioCapabilities( 5791): Unsupported mime audio/evrc
,W/AudioCapabilities( 5791): Unsupported mime audio/qcelp
W/VideoCapabilities( 5791): Unrecognized profile 2130706433 for video/avc
,V/AlarmManager(  847): RTC_WAKEUP set : Alarm{a6790de type 0 when 1454983579521 com.google.android.googlequicksearchbox} when 1454983579521
,W/AudioCapabilities( 5791): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5791): Unsupported mime audio/qcelp
W/AudioCapabilities( 5791): Unsupported mime audio/evrc
W/VideoCapabilities( 5791): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5791): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5791): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5791): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5791): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5791): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5791): onServiceConnected
W/Babel   ( 5791): Attempted to change video mute state without an active call.
,I/NotificationManager( 5791): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5791): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5791): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5791): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/jxcore-log( 5545): JXcore Cordova bridge is ready!
I/jxcore-log( 5545): 
W/jxcore-log( 5545): JXcore engine is started
I/ActivityManager(  847): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5838 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/System  ( 5791): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5791): Installed default security provider GmsCore_OpenSSL
I/AudioManager( 5079): getMode name:com.lge.qremote
I/AudioManager( 5079): getMode name:com.lge.qremote
,I/AudioManager( 5079): getMode name:com.lge.qremote
,I/AudioManager( 5079): getMode name:com.lge.qremote
D/UEI.SmartControl( 5838): Quickset Services start...
,I/UEI.SmartControl( 5838): Manufacture = LGE
I/AudioManager( 5079): getMode name:com.lge.qremote
D/UEI.SmartControl( 5838): File observer start...
E/UEI.SmartControl( 5838): IR Port is disabled: false
D/UEI.SmartControl( 5838): Starting file observer...
D/UEI.SmartControl( 5838): Extracting JNI libs...
D/UEI.SmartControl( 5838): --- this system supports 32-bit or 64-bit only
E/MDM     ( 1734): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5587): Restart initialization of location
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5079): getMode name:com.lge.qremote
W/GCoreFlp( 1734): No location to return for getLastLocation()
,W/FusedLocationProvider( 1734): location=null
I/AudioManager( 5079): getMode name:com.lge.qremote
,I/NotificationManager( 5791): com.google.android.talk: cancel(8) by com.google.android.talk
,I/jxcore-log( 5545): Toggling radios to true
I/jxcore-log( 5545): 
,D/BluetoothAdapter( 5545): enable(): BT is already enabled..!
I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5865 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/WifiServiceImplEx(  847): setWifiEnabled: true pid=5545, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  847): setWifiEnabled: true pid=5545, uid=10316
D/WifiServiceImplEx(  847): disconnect pid=5545, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  847): reconnect pid=5545, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5545): Radios toggled
I/jxcore-log( 5545): 
I/jxcore-log( 5545): My device name is: LGE-LG-D722
I/jxcore-log( 5545): 
,I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2717): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/UEI.SmartControl( 5838): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5838): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5838): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2717): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,E/WifiStateMachine(  847): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  847): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1804): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/AppUp4:AppBoxCP( 5865): onCreate
,I/UEI.SmartControl( 5838): --- Selecting new region: 2
I/UEI.SmartControl( 5838): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5838): Platform has CIR...
D/UEI.SmartControl( 5838): NO CIR support, need to check package...
I/UEI.SmartControl( 5838): Model: LG-D722 uses JNI
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/UEI.SmartControl( 5838): QS Service created
W/AppUp4:DB( 5865):  [AppBoxDatabaseHelper] construct
D/DhcpStateMachine(  847): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  271): Clearing all IP addresses on wlan0
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 7
I/AppUp4:DB( 5865):  setFingerPrint start
,I/AppUp4:DB( 5865):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
V/NativeCrypto( 1734): Read error: ssl=0xaaedf800: I/O error during system call, Connection timed out
I/AppUp4:DB( 5865):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5865):  SDK version = 0
,I/AppUp4:DB( 5865):  beforefinger == newfinger no write in DB
V/NativeCrypto( 1734): SSL shutdown failed: ssl=0xaaedf800: I/O error during system call, Broken pipe
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  847): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/ConnectivityService(  847): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  847): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): ValidatedState{ when=-7ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): DefaultState{ when=-11ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Forcing reevaluation
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/ActivityManager(  847): Process com.google.android.apps.docs (pid 5403) has died
,D/AppUp4:AppBoxApplication( 5865): AppBoxApplication onCreate()
E/WifiStateMachine(  847): Start Disconnecting Watchdog 1
I/wpa_supplicant( 2717): wlan0: CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService(  847): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiHS20(  847): hidePasspointNotification off =false
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  847): hidePasspointNotification off =false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:20.294 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:20.305 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/AppUp4:CustModeStarterReceiver( 5865): onReceive
I/AppUp4:CustModeStarterReceiver( 5865): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
,D/AppUp4:CustFacade( 5865): Context : android.app.ReceiverRestrictedContext@608c082
D/AppUp4:CustFacade( 5865): isCustomizationCompleted : false
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
,E/UEI.SmartControl( 5838): QS start get config
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/AppUp4:CustFacade( 5865): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5865): begin check event
I/AppUp4:CustModeStarterReceiver( 5865): Event For Nothing, skip.
D/CommandListener(  271): Clearing all IP addresses on wlan0
D/ConnectivityService(  847): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  847): disableDataServiceNotify
D/WifiHS20(  847): hidePasspointNotification off =false
,I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:20.361 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/DSQN    (  847): stop dsqn bin
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/WifiNetworkAgent(  847): NetworkAgent: NetworkAgent channel lost
,D/WifiHS20(  847): hidePasspointNotification off =false
D/ConnectivityService(  847): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:20.394 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:20.396 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateDISCONNECTED
D/ConnectivityService(  847): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Disconnected - quitting
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateSCANNING
D/Nat464Xlat(  847): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/UEI.SmartControl( 5838): Loading JNI Libs...
D/CSLegacyTypeTracker(  847): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  847): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/UEI.SmartControl( 5838):  configuring local db...
,D/ConnectivityManager.CallbackHandler( 1368): CM callback handler got msg 524292
D/DhcpStateMachine(  847): StoppedState
D/DhcpStateMachine(  847): StoppedState{ when=-125ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  847): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  847): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  847): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/QCNEJ   ( 1840): |CORE| No family connected
D/Tethering(  847): MasterInitialState.processMessage what=3
V/NetworkPolicy(  847): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  847): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  847): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  847): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  847):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1747): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1747):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = -1
D/NetworkManagementService(  847): Removing idletimer
W/Settings(  847): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  847): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyIcons( 1368): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1368): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  847): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5888 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/TelephonyIcons( 1368): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1368): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 5838):  ---- Has DB8: true
W/ResourcesManager( 5888): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5888): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5888): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5888): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5888): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5838): QS start statue = true Error code = 0
D/UEI.SmartControl( 5838): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5838): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 5838): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5838): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5838): IrrcClient ++ 
D/irrcClient( 5838): getIrrcService ++ 
,D/irrcClient( 5838): getIrrcService -- 
D/irrcClient( 5838): IrrcClient -- 
W/irrc_jni( 5838): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5838): Services init done
,I/UEI.SmartControl( 5838): Device manager: loading config....
D/UEI.SmartControl( 5838): Config is loaded...
D/UEI.SmartControl( 5838):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5838): Notify AllClients services are ready: 0
I/[SystemUI]QPairHandler( 1368): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1368): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
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
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/InputReader(  847): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/art     (  847): Explicit concurrent mark sweep GC freed 37684(1766KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 5.441ms total 223.920ms
,I/ActivityManager(  847): Process com.google.android.gm (pid 5684) has died
,D/UEI.SmartControl( 5838): QS Service init finished
D/UEI.SmartControl( 5838): QS Service version name: 0.1.73
D/UEI.SmartControl( 5838): QS Service version code: 1073
D/UEI.SmartControl( 5838): Service requested: Control
D/UEI.SmartControl( 5838): Internal service binding...
D/UEI.SmartControl( 5838): -----IControl: 11
,D/UEI.SmartControl( 5838): Caller: com.lge.qremote
D/UEI.SmartControl( 5838): ------------ IControl registerCallback...
I/UEI.SmartControl( 5838): Registering callback...
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/UEI.SmartControl( 5838): -----IControl: 19
D/UEI.SmartControl( 5838): Caller: com.lge.qremote
I/UEI.SmartControl( 5838): Registering Services Ready callback...
I/UEI.SmartControl( 5838): Notify client services are ready...
,D/administrator(  847): Handling package changes for user 0
D/UEI.SmartControl( 5838): -----IControl: 8
D/UEI.SmartControl( 5838): Caller: com.lge.qremote
I/SystemConfig( 5888): BUILD Country: EU
I/SystemConfig( 5888): BUILD Operator: OPEN
,I/ActivityManager(  847): Killing 5369:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10069/pid_5369/cgroup.procs: No such file or directory
,I/NotificationService(  847): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  847): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  847): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  847): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5918 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  847): Killing 5386:com.lge.eula/1000 (adj 15): empty #11
W/ResourcesManager(  847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2717): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/BackupManagerService(  847): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_5386/cgroup.procs: No such file or directory
I/SystemConfig( 5888): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5888): existFile = false
V/BackupManagerService(  847): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  847): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1889305f
,I/SystemConfig( 5888): canReadFile = false
I/SystemConfig( 5888): systemFeature RCS result false
D/SystemConfig( 5888): refreshRcsSupport() :false
D/LocSvc_java(  847): onReceive
,I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:21.464 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
,I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2717): wlan0: Associated with c0:ff:d4:d3:aa:48
I/LockScreenSettings( 5918): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/ActivityManager(  847): Process com.android.vending (pid 5500) has died
,I/wpa_supplicant( 2717): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2717): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
W/ResourceType(  847): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 4
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:21.53 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:21.538 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:21.543 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/WifiServiceExtension(  847): setVHTCapabilityType  : false
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/LockScreenSettings( 5918): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5918): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5918): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5918): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5918): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/WifiServerServiceExt(  847): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  847): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  847): setSecurityType  : 2
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:21.573 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:21.578 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
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
,D/ConnectivityService(  847): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  847): Got NetworkAgent Messenger
D/ConnectivityService(  847): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  847): NetworkAgent connected
I/UpdateIcingCorporaServi( 1942): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
E/WifiConfigStore(  847): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/WifiConfigStore(  847): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  271): Setting iface cfg
E/WifiStateMachine(  847): Start Dhcp Watchdog 2
D/DhcpStateMachine(  847): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  847): WaitBeforeStartState
I/ActivityManager(  847): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5939 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  847): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  847): applying state to connected service
I/UpdateIcingCorporaServi( 1942): UpdateCorporaTask done [took 139 ms] updated apps [took 133 ms] 
,E/WifiStateMachine(  847): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  847): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  847): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@37eff4b3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@37eff4b3 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  847): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  847): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  847): DHCP Start wake lock is acquired.
D/CommandListener(  271): Setting iface cfg
I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  271): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  847): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/ConnectivityService(  847): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  847): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt(  847): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  847): setSupplicantStateCOMPLETED
D/ConnectivityService(  847): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  847): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  847): ignoring duplicate network state non-change
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:21.782 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
D/ConnectivityService(  847): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/ConnectivityService(  847): Adding iface wlan0 to network 101
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:21.786 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
,D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  847): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:21.794 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/ConnectivityService(  847): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  847): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:21.811 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/WifiHS20(  847): [PASSPOINT] passpointNotification: hs20AP list is checked
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  847): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  271): netlink response contains error (File exists)
E/WifiStateMachine(  847): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  847): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService(  847): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  847): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  847): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  847): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  847): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,D/ConnectivityService(  847): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  847):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  847):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Connected
D/ConnectivityService(  847):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  847):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  847): currentScore = 0, newScore = 20
D/ConnectivityService(  847):    accepting network in place of null
D/ConnectivityService(  847): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1747): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1747):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  847): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  847): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  847): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  847): [e] list.add(nai) empty : false size: 1
D/Tethering(  847): MasterInitialState.processMessage what=3
D/ConnectivityService(  847): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1840): |CORE| No family connected
D/ConnectivityService(  847): validation of new default Network = false
D/ConnectivityService(  847): Default network via Wi-Fi connected. start DSQN
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/DSQN    (  847): enableDataServiceNotify 
D/DSQN    (  847): start dsqn bin
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = 1
D/WIFI    (  847): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  847):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): mWifiConnected = true, mWifiLevel = 2
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] Start DNSResolver start to wait
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] wait 500ms before dns check
V/NetworkPolicy(  847): [LG_RESTRICTED] checkMobilePolicy_type()
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1368): Remote
D/ConnectivityService(  847): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1368): CM callback handler got msg 524290
I/DSQN    ( 5961): DSQN samuel.seo ver 141203
,E/DSQN    ( 5961): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5961): created command queue thread
I/DSQN    ( 5961): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5961): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/TelephonyIcons( 1368): null signal icon name: drawable/stat_sys_signal_null
I/CheckinService( 5587): Checkin interval check for package: unspecified last checkin: 1454983570908 min interval config: 0 actual interval: 10967
I/[SystemUI]LGNetworkController( 1368): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/CheckinService( 5587): Checking schedule, now: 1454983581893 next: 1454983600824
I/CheckinService( 5587): active receiver: disabled
,D/DhcpStateMachine(  847): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  847): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  847): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5965): version 5.5.6 starting
E/dhcpcd  ( 5965): get_duid: Read-only file system
,I/dhcpcd  ( 5965): wlan0: rebinding lease of 192.168.1.134
,D/Finsky  ( 5939): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5939): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5939): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5939): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5939): com.android.vending: cancel(-1050172287) by com.android.vending
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] DNSResolver start dns
D/Finsky  ( 5939): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5939): [1] Libraries$2.run: Finished loading 1 libraries.
,V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@11dfc71d on behalf of 5939
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/Ads     ( 5939): Skipping gmscore version check
I/ActivityManager(  847): Killing 5761:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out(  847): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5961): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5961): restart monitoring
D/LGDataListener(  271): argv[0]=dsqncommand
D/LGDataListener(  271): argv[1]=wlan0
D/LGDataListener(  271): argv[2]=1
D/LGDataListener(  271): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5961): dsqn report finish
D/DSQN    (  847): DSQM DsqnNotification wlan0  1
D/DSQN    (  847): start to monitor internet connection
W/libprocessgroup(  847): failed to open /acct/uid_10038/pid_5761/cgroup.procs: No such file or directory
D/PackageBroadcastService( 5587): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/AudioManager( 5079): getMode name:com.lge.qremote
I/PackageBroadcastService( 5587): Null package name or gms related package.  Ignoreing.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 02:06:22 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454983582458], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454983582438]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  847): Validated
D/ConnectivityService(  847): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  847):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  847): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  847): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1368): CM callback handler got msg 524290
D/ConnectivityService(  847): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  847): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  847):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1747): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1747):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,D/WifiDataContinuityService(  847): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  847): set CMD_CAPTIVE_CHECK_COMPLETED
I/Icing   ( 5587): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  847): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6012 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/TelephonyIcons( 1368): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1368): updateLGTelephonySignalStrength : !hasService()
D/Finsky  ( 5939): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Netd    (  271): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  847): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  847): identical MTU - not setting
D/Nat464Xlat(  847): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  847): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  847):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  847): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  847): enableDataServiceNotify 
D/DSQN    (  847): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1368): CM callback handler got msg 524295
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:22.651 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/Finsky  ( 5939): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/DSQN    (  847): dsqn is running restart
I/DSQN    ( 6031): DSQN samuel.seo ver 141203
E/DSQN    ( 6031): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6031): created command queue thread
I/DSQN    ( 6031): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6031): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/PhoneMonitor( 6012): Register our PhoneStateListener
,V/SetupWizard( 6012): Connected to Gservices successfully
,I/ActivityManager(  847): Killing 5731:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/PhoneMonitor( 6012): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6012): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6012): [parse] Load xml
V/TelephonyAutoProfiling( 6012): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6012): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6012): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  847): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/libprocessgroup(  847): failed to open /acct/uid_10014/pid_5731/cgroup.procs: No such file or directory
D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
E/MDM     ( 1734): [117] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5587): Restart initialization of location
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 1734): propertyValue:false
,I/ActivityManager(  847): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6046 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DSQN    ( 6031): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6031): restart monitoring
I/DSQN    ( 6031): dsqn report finish
D/LGDataListener(  271): argv[0]=dsqncommand
D/LGDataListener(  271): argv[1]=wlan0
D/LGDataListener(  271): argv[2]=1
D/LGDataListener(  271): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  847): DSQM DsqnNotification wlan0  1
D/DSQN    (  847): start to monitor internet connection
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 29895(1802KB) AllocSpace objects, 10(160KB) LOS objects, 39% free, 13MB/22MB, paused 1.812ms total 122.269ms
,I/ActivityManager(  847): Process com.android.contacts (pid 5888) has died
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
I/dhcpcd  ( 5965): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5965): wlan0: leased 192.168.1.134 for 86400 seconds
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{2c88bd35 type 2 when 89994 com.android.providers.calendar} when 89994
,W/ProcessCpuTracker(  847): Skipping unknown process pid 6072
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  847): Process com.android.gallery3d (pid 5327) has died
,D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  847): onReceive
D/LocSvc_java(  847): got connectivity action
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
D/GpsLocationProvider(  847): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  847): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  847): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  847): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Gmail   ( 6046): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6046): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
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
W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6046): Error finding the version of the Email provider.....
E/Gmail   ( 6046): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6046): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6046): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6046): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6046): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6046): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6046): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6046): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6046): We do not support migrating this version of the Email provider.
,W/ActivityManager(  847): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 6046): getAccountsCursor
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6046): Observing account changes for notifications
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Icing   ( 5587): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/ActivityManager(  847): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6109 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 22.136ms
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 318us total 22.691ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 22.653ms
,I/Gmail   ( 6046): notifyAccountChanged
,I/Gmail   ( 6046): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Icing   ( 5587): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/Gmail   ( 6046): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6046): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6046): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  847): Process com.lge.appbox.client (pid 5865) has died
,I/Gmail   ( 6046): getAccountsCursor
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6109): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     (  847): Explicit concurrent mark sweep GC freed 67064(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.491ms total 156.237ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CalendarApplication( 6109): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6109): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6109): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2094efcd, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@608c082, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@22edc393, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@27853fd0, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@180dbbc9, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@338662ce, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1ba705ef, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2fc688fc, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@42d4b85, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@229ddda, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1e08120b, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3e7138e8, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@fc1b01, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1f57fda6, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3c23c3e7, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2c94fb94, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@88e663d, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@17f64e32, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@2c5eb783, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@32903d00, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@28002939, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2fb71b7e, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1ccb48df, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2e3c292c, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@8311ff5, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2125718a, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@204593fb, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@1fd8ac18, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@640c671, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@12711c56, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@114f74d7, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@9b871c4, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@17ca58ad, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@afaa7e2, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@6ac8773, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1eace630, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@36e0d2a9, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@359f602e, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@35be27cf, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2b32355c, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@11caf065, lg_preferences_recent,_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3bc5513a,
,D/GeneralPreferenceUtils( 6109): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6109): [init]
,I/Config  ( 6109): LGCalendar ver.4.40.17
I/Config  ( 6109): start check model
I/Config  ( 6109): start check native_ca
I/Config  ( 6109): Config Operator=OPEN, Country=EU
D/Config  ( 6109): [setDefaultValuesToPref]
D/Config  ( 6109): [parseProfiles]
D/ProfilesParser( 6109): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6109): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6109): [updateProfiletoCountryInfo]
D/GeneralPreference( 6109): [checkAndMigrateOldPreference]
,D/AlertReceiver( 6109): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6109): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6109): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/Gmail   ( 6046): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AlertUtils( 6109): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6109): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6109): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6109): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 6109): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6109): onHandleIntent
,D/HolidayDataLoader( 6109): readJsonAsset : holiday.json
D/AlertService( 6109): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6109): [updateWidgets] 
,D/MonthWidgetProvider( 6109): [onReceive]
D/CalendarWidgetProvider( 6109): [onReceive]
D/CalendarWidgetProvider( 6109): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6109): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6109): [onReceive]
D/CalendarWidgetProvider( 6109): [onReceive]
D/CalendarWidgetProvider( 6109): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6109): [onCreate] mContext.getPackageName() = com.android.calendar
,I/ActivityManager(  847): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6136 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/HolidayIntentService( 6109): onHandleIntent:holiday data empty
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:06:24.681 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 6136): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6136): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6136): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/NotificationManager( 1942): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/WifiInternetCheck(  847): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  847): Process com.google.android.apps.plus (pid 5434) has died
I/IndexDatabaseHelper( 6136): Using schema version: 115
I/IndexDatabaseHelper( 6136): Index is fine
D/ConnectivityService(  847): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  847): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  847): onReceive
D/LocSvc_java(  847): got connectivity action
D/LocSvc_java(  847): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  847): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  847): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  847): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  847): ignore wifi update if we are not in OPENING or CLOSING
,I/[SystemUI]QuickSettingsHandler( 1368): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  847): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
I/ActivityManager(  847): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6157 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6157): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6157): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6157): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
I/PCSuite ( 6157): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6157): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6157): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
I/PCSuite ( 6157): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6157): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6157): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
I/PCSuite ( 6157): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6157): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6157): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6182 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 5791): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 5791): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5791): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 6182): onCreate
,W/AppUp4:DB( 6182):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6182):  setFingerPrint start
I/AppUp4:DB( 6182):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6182):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6182):  SDK version = 0
I/AppUp4:DB( 6182):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6182): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6182): onReceive
,I/AppUp4:CustModeStarterReceiver( 6182): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6182): Context : android.app.ReceiverRestrictedContext@608c082
D/AppUp4:CustFacade( 6182): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6182): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6182): begin check event
I/AppUp4:CustModeStarterReceiver( 6182): Event For Nothing, skip.
,I/ActivityManager(  847): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6206 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6206): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6206): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6206): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 5838): Internal timer expired: 1
,I/AppConfig( 6206): Total System Memory = 906309632
,I/GalleryUtils( 6206): Application Heap = 96 MB
I/AppConfig( 6206): App Tier : NOT_DEF
D/SystemHelper( 6206): region [EU], country [EU], operator [OPEN], sub-operator []
,D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  847): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6227 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out(  847): propertyValue:false
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  847): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  847): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/ActivityManager(  847): Killing 5918:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
E/BandwidthController(  271): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  271): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out(  847): propertyValue:false
V/WifiInternetCheck(  847): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager(  847): Process com.google.android.gm (pid 6046) has died
,V/AlarmManager(  847): RTC_WAKEUP set : Alarm{3f48e8a6 type 0 when 1454983586099 com.android.vending} when 1454983586099
W/libprocessgroup(  847): failed to open /acct/uid_10069/pid_5918/cgroup.procs: No such file or directory
D/Finsky  ( 5939): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
W/ResourcesManager( 6227): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6227): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6227): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6227): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6227): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  847): android: cancelAsUser(2) by android
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
I/SystemConfig( 6227): BUILD Country: EU
I/SystemConfig( 6227): BUILD Operator: OPEN
,D/libc-netbsd( 5939): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5939): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5939): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5939): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  271): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 5939): propertyValue:false
D/libc-netbsd( 5939): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5939): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  847): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6250 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6227): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6227): existFile = false
I/SystemConfig( 6227): canReadFile = false
I/SystemConfig( 6227): systemFeature RCS result false
D/SystemConfig( 6227): refreshRcsSupport() :false
,D/libc-netbsd( 5939): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5939): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/LockScreenSettings( 6250): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6250): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6250): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6250): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6250): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6250): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  847): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6271 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  847): android: cancelAsUser(2) by android
,W/ResourcesManager( 6271): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/qtaguid ( 5939): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5939): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5939): untagSocket(41) failed with errno -22
,D/Finsky  ( 5939): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/ActivityManager(  847): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6298 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  847): android: cancelAsUser(2) by android
,W/ResourcesManager( 6298): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6298): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1942): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/PackageBroadcastService( 5587): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5587): Null package name or gms related package.  Ignoreing.
I/AudioManager( 5079): getMode name:com.lge.qremote
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,I/Icing   ( 5587): updateResources: need to parse f{com.google.android.gms}
D/WiFiOffLoadBroadcast( 6136): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
I/UpdateIcingCorporaServi( 1942): UpdateCorporaTask done [took 87 ms] updated apps [took 87 ms] 
,V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
I/MultiDex( 6298): VM with version 2.1.0 has multidex support
,I/MultiDex( 6298): install
I/MultiDex( 6298): VM has multidex support, MultiDex support library is disabled.
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
I/qtaguid ( 5939): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5939): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5939): untagSocket(41) failed with errno -22
V/JNIHelp ( 6298): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
I/PCSuite ( 6157): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,W/ActivityThread( 6298): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6298): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2860cd92: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
D/PCSuite ( 6157): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ProviderInstaller( 6298): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6298): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6298): com.google.android.gms: cancel(39789) by com.google.android.gms
V/WiFiOffLoadBroadcast( 6136): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6136): MCCMNC not supported: null
I/PCSuite ( 6157): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6157): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/ChimeraCfgMgr( 6298): Reading stored module config
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 5079): getMode name:com.lge.qremote
I/AudioManager( 5079): getMode name:com.lge.qremote
I/ActivityManager(  847): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6333 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ChimeraCfgMgr( 6298): Loading module com.google.android.gms.car from APK com.google.android.gms
I/ActivityManager(  847): Process com.android.contacts (pid 6227) has died
,D/NativeLibraryUtils( 6298): Install completed successfully. count=14 extracted=0
W/ResourcesManager( 6333): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6333): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@307f2ef7
,I/ActivityManager(  847): Process com.android.gallery3d (pid 6206) has died
,I/art     ( 5939): CheckpointMarkThreadRoots callback created = 0xb055f7d0
,D/CAR.SERVICE( 6298): Connecting to CarCallService...
I/art     ( 5939): CheckpointMarkThreadRoots callback created = 0xb055f7a0
,I/art     (  847): Explicit concurrent mark sweep GC freed 24770(1243KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.492ms total 164.839ms
,D/CalendarProvider2( 6333): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6333): Created com.android.providers.calendar.CalendarAlarmManager@27853fd0(com.android.providers.calendar.CalendarProvider2@307f2ef7)
D/CalendarProviderBroadcastReceiver( 6333): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6333): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6333): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6333): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6333): [getOrCreateCalendarAlarmManager]
,I/art     ( 6298): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6298): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/ActivityManager(  847): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6355 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/CAR.SERVICE( 6298): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6298): Creating a new CarCallService.
D/CalendarProvider2( 6333): [IntentService] Release Lock
,D/CAR.TEL.PhoneAdapter( 6298): Creating a new PhoneAdapter instance
D/CalendarProvider2( 6333): CalendarProviderIntentService.onDestroy()
,W/ActivityManager(  847): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6298): setListener: com.google.android.gms.car.dn@3948d989
,W/ActivityManager(  847): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6298): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6298): Starting CarCallService with initial phone null
I/NotificationManager( 6298): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6298): Package validated; name: com.android.vending
,I/ActivityManager(  847): Process com.google.android.apps.plus (pid 6271) has died
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/NotificationManager( 5939): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5939): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/Icing   ( 5587): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5587): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/Gmail   ( 6355): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6355): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  847): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6392 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  847): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 31.945ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.973ms
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 367us total 22.933ms
,E/Gmail   ( 6355): Error finding the version of the Email provider.....
E/Gmail   ( 6355): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6355): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6355): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6355): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6355): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6355): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6355): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6355): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6355): We do not support migrating this version of the Email provider.
I/Gmail   ( 6355): getAccountsCursor
I/Gmail   ( 6355): Observing account changes for notifications
I/ActivityManager(  847): Killing 6182:com.lge.appbox.client/u0a11 (adj 15): empty #11
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  847): failed to open /acct/uid_10011/pid_6182/cgroup.procs: No such file or directory
I/NotificationManager(  847): android: cancelAsUser(2) by android
,I/ActivityManager(  847): Process com.android.settings (pid 6136) has died
,I/Gmail   ( 6355): notifyAccountChanged
,I/Gmail   ( 6355): getAccountsCursor
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6355): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 95689231530; DSPS: 3226915; Offset : -2798643773
I/qtaguid ( 5939): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5939): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5939): untagSocket(41) failed with errno -22
I/Gmail   ( 6355): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6355): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6355): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/MusicStore( 6392): Database version: 120
,I/ActivityManager(  847): Process com.lge.sync (pid 6157) has died
,I/Gmail   ( 6355): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6392): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/jxcore-log( 5545): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5545): 
,W/ResourcesManager( 5939): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5939): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5939): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6392): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6392): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/Finsky  ( 5939): [1] DailyHygiene.access$600: Logging device features
,W/ResourcesManager( 6392): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6392): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/AlarmManager(  847): RTC_WAKEUP set : Alarm{1b00157f type 0 when 1454983589331 com.android.vending} when 1454983589331
,D/WearableService( 1734): callingUid 10006, callindPid: 1734
,D/DeviceConnectionService( 1734): client connected with version: 8296000
V/JNIHelp ( 6392): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/Finsky  ( 5939): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5939): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/AlertService( 6109): Beginning updateAlertNotification
,D/AlertService( 6109): No fired or scheduled alerts
I/NotificationManager( 6109): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(9) by com.android.calendar
,W/ActivityThread( 6392): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6392): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@358249b5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6392): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6392): GMSCore installation verified
I/NotificationManager( 6109): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(15) by com.android.calendar
,I/NotificationManager( 6109): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6109): com.android.calendar: cancel(20) by com.android.calendar
I/ConfigStore( 6392): Config Database version: 1
D/AlertService( 6109): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6109): No events found starting within 1 week.
,I/MediaRouter( 6392): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6392): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6392): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  847): Killing 6109:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10013/pid_6109/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6392): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  847): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6435 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6392): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6392): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  847): Killing 6250:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/ResourcesManager( 6435): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6435): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6435): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  847): failed to open /acct/uid_10069/pid_6250/cgroup.procs: No such file or directory
,I/NotificationManager( 6392): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6435): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6435): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,V/AlarmManager(  847): RTC_WAKEUP set : Alarm{3c8b40ae type 0 when 1454983590266 com.google.android.googlequicksearchbox} when 1454983590266
I/jxcore-log( 5545): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5545): 
,D/eas_req ( 6435): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/jxcore-log( 5545): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5545): 
I/jxcore-log( 5545): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5545): 
,I/ActivityManager(  847): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6471 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/jxcore-log( 5545): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5545): 
I/ActivityManager(  847): Process com.lge.qremote (pid 5079) has died
,D/UEI.SmartControl( 5838): Service.onUnbind: IControl
D/UEI.SmartControl( 5838): Service.onDestroy
D/UEI.SmartControl( 5838): Shutdown IRRCPlayer... 
,W/irrc_jni( 5838): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5838): ~IrrcClient ++ 
D/irrcClient( 5838): ~IrrcClient -- 
W/irrc_jni( 5838): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5838): Blaster closed
D/UEI.SmartControl( 5838): Blaster closed
D/UEI.SmartControl( 5838): Shut down QS...
,D/UEI.SmartControl( 5838): Stopped file observer...
I/HubEmail( 6435): JNI_OnLoad()
I/HubEmail( 6435): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6435): registerNatives()
I/HubEmail( 6435): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6435): registerNativeMethods()
I/HubEmail( 6435): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6435): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6435): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/UEI.SmartControl( 5838): QS lib stop result = true
D/UEI.SmartControl( 5838): QS shutdown complete
I/ActivityManager(  847): Killing 6012:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/jxcore-log( 5545): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5545): 
W/libprocessgroup(  847): failed to open /acct/uid_10038/pid_6012/cgroup.procs: No such file or directory
,D/LGDMClient( 6471): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6471): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6471): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,I/art     (  847): Explicit concurrent mark sweep GC freed 15060(715KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.052ms total 144.731ms
,W/ContextImpl( 6471): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6471): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6471): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6471): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6471): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6496 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  847): Process com.google.android.talk (pid 5791) has died
,W/ContextImpl( 6471): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6471): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6471): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6471): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6471): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6471): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/AppUp4:AppBoxCP( 6496): onCreate
,W/AppUp4:DB( 6496):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6496):  setFingerPrint start
,I/AppUp4:DB( 6496):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6496):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6496):  SDK version = 0
I/AppUp4:DB( 6496):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6496): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6496): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6496): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6496): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6496): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6496): onReceive
I/AppUp4:CustModeStarterReceiver( 6496): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6496): Context : android.app.ReceiverRestrictedContext@180dbbc9
D/AppUp4:CustFacade( 6496): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6496): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6496): begin check event
I/AppUp4:CustModeStarterReceiver( 6496): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6496): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6496): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6496): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6496): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  847): Killing 5838:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  847): failed to open /acct/uid_10089/pid_5838/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3223): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3223): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3223): networkInfo.isConnected() = false
,I/ActivityManager(  847): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6515 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6515): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6515): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6515): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  847): Killing 6333:com.android.providers.calendar/u0a14 (adj 15): empty #11
,D/PhoneMonitor( 6515): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6515): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6515): [parse] Load xml
V/TelephonyAutoProfiling( 6515): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6515): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6515): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  847): failed to open /acct/uid_10014/pid_6333/cgroup.procs: No such file or directory
,I/CheckinService( 5587): Checkin interval check for package: unspecified last checkin: 1454983570908 min interval config: 0 actual interval: 20859
,I/CheckinService( 5587): Checking schedule, now: 1454983591774 next: 1454983600824
I/CheckinService( 5587): active receiver: disabled
V/DownloadManager( 3202): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3202): DownloadService onCreate
,I/DownloadManager( 3202): in removeSpuriousFiles
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@2860cd92 on behalf of 3202
I/NotificationManager( 3202): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3202): in trimDatabase
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@c63363 on behalf of 3202
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  847): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6546 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3202): DownloadService onStartCommand
V/DownloadManager( 3202): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@183a30de on behalf of 3202
,V/DownloadManager( 3202): DownloadService onDestroy
,I/ActivityManager(  847): Killing 6355:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10053/pid_6355/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2777): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:6:32
,D/UpdateThreadPoolManager( 2777): 2 : This is isUpdating : false
D/WeatherAncestor( 2777): connectivity changed - connection : true
D/Weather_cast( 2777): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2777): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:6:32
D/WeatherService( 2777): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6564 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2777): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2777): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,D/WeatherService( 2777): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6564): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6564): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6564): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6564): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6564): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6564): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6564): MmsConfig.loadFromResources
E/Babel_SMS( 6564): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6564): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6564): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6564): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6564): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6564): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6564): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6564): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6564): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6564): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6564): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6564): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6564): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6564): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6564): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6564): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6564): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6564): found sensor: Motion Accel, handle=46
,I/art     ( 6564): CheckpointMarkThreadRoots callback created = 0xb042d550
,W/Settings( 6564): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6564): startup - clean
I/art     ( 6564): CheckpointMarkThreadRoots callback created = 0xb042d520
I/Babel   ( 6564): deleted: false for 0
,I/ActivityManager(  847): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6595 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 6564): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6564): Unsupported mime audio/adpcm
W/AudioCapabilities( 6564): Unsupported mime audio/g726
,W/AudioCapabilities( 6564): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6564): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6564): Unsupported mime video/mjpg
W/VideoCapabilities( 6564): Unsupported mime video/theora
,W/AudioCapabilities( 6564): Unsupported mime audio/evrc
,W/AudioCapabilities( 6564): Unsupported mime audio/qcelp
W/VideoCapabilities( 6564): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6564): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6564): Unsupported mime audio/qcelp
W/AudioCapabilities( 6564): Unsupported mime audio/evrc
,W/VideoCapabilities( 6564): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6564): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6564): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6564): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6564): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6564): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6564): onServiceConnected
,W/Babel   ( 6564): Attempted to change video mute state without an active call.
I/NotificationManager( 6564): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6564): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6564): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6564): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6564): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  271): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 6564): propertyValue:false
,I/Babel   ( 6564): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  847): Killing 6298:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10006/pid_6298/cgroup.procs: No such file or directory
W/ActivityManager(  847): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6595): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6595): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6595): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6595): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6595): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6595):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6595):   adb logcat -s GAv4
,W/GAv4    ( 6595): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6595): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6595): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6595): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6595): Time to load native libraries: 2 ms (timestamps 594-596)
I/LibraryLoader( 6595): Expected native library version number "",actual native library version number ""
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/WebViewChromiumFactoryProvider( 6595): Binding Chromium to main looper Looper (main, tid 1) {2233bf42}
I/LibraryLoader( 6595): Expected native library version number "",actual native library version number ""
I/chromium( 6595): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6595): Initializing chromium process, singleProcess=true
W/art     ( 6595): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6595): ApplicationContext is null in ApplicationStatus
,W/chromium( 6595): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6595): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6595): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6595): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6595): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6595): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6595): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6595): Remote Branch: 
I/Adreno-EGL( 6595): Local Patches: 
I/Adreno-EGL( 6595): Reconstruct Branch: 
,V/AudioPolicyService(  275): registerClient() client 0xb4027160, uid 10079
,W/AudioManagerAndroid( 6595): Requires BLUETOOTH permission
I/NSApplication( 6595): Starting up...
,I/ActivityManager(  847): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6660 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  847): Killing 5939:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10036/pid_5939/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6682 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  847): Killing 6392:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10081/pid_6392/cgroup.procs: No such file or directory
,W/ResourcesManager( 6682): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 5587): SYNC; picasa accounts
,D/NetworkLogImpl( 5587): Loaded NetworkSpeedPredictor
I/iu.Environment( 5587): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  847): Killing 6435:com.lge.email/u0a21 (adj 15): empty #11
I/iu.UploadsManager( 5587): num queued entries: 0
I/iu.UploadsManager( 5587): num updated entries: 0
I/iu.SyncManager( 5587): NEXT; no task
,W/libprocessgroup(  847): failed to open /acct/uid_10021/pid_6435/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6713 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6713): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6713): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6713): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6713): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6713): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6713): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6713): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/art     ( 6471): Suspending all threads took: 8.905ms
,W/ActivityThread( 6713): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6713): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@358249b5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6713): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6713): GMSCore installation verified
,I/ConfigStore( 6713): Config Database version: 1
,I/MediaRouter( 6713): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6713): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6713): type=WIFI subType= reason=null isConnected=true
,I/rmt_storage(  269): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  269): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  269): wakelock acquired: 1, error no: 42
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  847): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6743 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  269): 
I/rmt_storage(  269): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/art     (  303): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 297us total 23.625ms
I/art     (  303): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.654ms
,I/NetworkMonitor( 6713): type=WIFI subType= reason=null isConnected=true
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.113ms
,I/GHttpClientFactory( 6713): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/ResourcesManager( 6743): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6743): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6743): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/GoogleURLConnFactory( 6713): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  847): Killing 6471:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_6471/cgroup.procs: No such file or directory
,I/NotificationManager( 6713): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6743): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6743): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6743): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  847): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6772 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6743): JNI_OnLoad()
I/HubEmail( 6743): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6743): registerNatives()
I/HubEmail( 6743): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6743): registerNativeMethods()
I/HubEmail( 6743): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6743): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  847): Killing 6496:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10011/pid_6496/cgroup.procs: No such file or directory
,W/Settings( 6743): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6772): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6772): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6772): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6772): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6772): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6772): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6799 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6772): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6772): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6772): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6772): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6772): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6772): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  847): Killing 6515:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10038/pid_6515/cgroup.procs: No such file or directory
I/art     (  847): Explicit concurrent mark sweep GC freed 18839(896KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.214ms total 154.678ms
,I/AppUp4:AppBoxCP( 6799): onCreate
W/AppUp4:DB( 6799):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6799):  setFingerPrint start
I/AppUp4:DB( 6799):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6799):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6799):  SDK version = 0
I/AppUp4:DB( 6799):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6799): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6799): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6799): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6799): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6799): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6799): onReceive
I/AppUp4:CustModeStarterReceiver( 6799): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6799): Context : android.app.ReceiverRestrictedContext@180dbbc9
,D/AppUp4:CustFacade( 6799): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6799): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6799): begin check event
I/AppUp4:CustModeStarterReceiver( 6799): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6799): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6799): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6799): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6799): handleAsyncCustNotification do not startCustService
I/ActivityManager(  847): Killing 6546:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10051/pid_6546/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3223): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3223): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3223): networkInfo.isConnected() = false
,I/ActivityManager(  847): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6818 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6818): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6818): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6818): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  847): Killing 6564:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 6818): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6818): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6818): [parse] Load xml
V/TelephonyAutoProfiling( 6818): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6818): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6818): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  847): failed to open /acct/uid_10061/pid_6564/cgroup.procs: No such file or directory
,V/DownloadManager( 3202): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3202): DownloadService onCreate
I/NotificationManager( 3202): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3202): in removeSpuriousFiles
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@2071bcd5 on behalf of 3202
I/DownloadManager( 3202): in trimDatabase
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@19b47cea on behalf of 3202
,I/ActivityManager(  847): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6847 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3202): DownloadService onStartCommand
V/DownloadManager( 3202): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 5587): Checkin interval check for package: unspecified last checkin: 1454983570908 min interval config: 0 actual interval: 26810
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@121c1678 on behalf of 3202
I/CheckinService( 5587): Checking schedule, now: 1454983597732 next: 1454983600824
I/CheckinService( 5587): active receiver: disabled
,V/DownloadManager( 3202): DownloadService onDestroy
I/ActivityManager(  847): Killing 6595:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  847): failed to open /acct/uid_10079/pid_6595/cgroup.procs: No such file or directory
D/WeatherAncestor( 2777): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:6:38
,D/UpdateThreadPoolManager( 2777): 2 : This is isUpdating : false
D/WeatherAncestor( 2777): connectivity changed - connection : true
D/Weather_cast( 2777): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2777): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:6:38
D/WeatherService( 2777): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6868 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2777): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2777): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2777): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6868): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6868): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6868): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6868): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6868): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6868): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6868): MmsConfig.loadFromResources
E/Babel_SMS( 6868): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6868): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6868): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6868): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6868): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6868): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6868): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6868): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6868): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6868): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6868): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6868): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6868): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6868): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6868): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6868): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6868): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6868): found sensor: Motion Accel, handle=46
,W/Settings( 6868): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6868): startup - clean
I/Babel   ( 6868): deleted: false for 0
,I/art     ( 6868): CheckpointMarkThreadRoots callback created = 0xb042d920
I/art     ( 6868): CheckpointMarkThreadRoots callback created = 0xb042d900
,I/ActivityManager(  847): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6903 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 5587): Done disabling old GoogleServicesFramework version
,W/AudioCapabilities( 6868): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6868): Unsupported mime audio/adpcm
W/AudioCapabilities( 6868): Unsupported mime audio/g726
W/AudioCapabilities( 6868): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6868): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6868): Unsupported mime video/mjpg
W/VideoCapabilities( 6868): Unsupported mime video/theora
,W/AudioCapabilities( 6868): Unsupported mime audio/evrc
,W/AudioCapabilities( 6868): Unsupported mime audio/qcelp
W/VideoCapabilities( 6868): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6868): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6868): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6868): Unsupported mime audio/evrc
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/VideoCapabilities( 6868): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6868): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6868): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6868): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6868): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6868): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6868): onServiceConnected
W/Babel   ( 6868): Attempted to change video mute state without an active call.
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6903): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/NotificationManager( 6868): com.google.android.talk: cancel(10436) by com.google.android.talk
I/GAv4    ( 6903): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6903):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6903):   adb logcat -s GAv4
D/libc-netbsd( 6868): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6868): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6868): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6868): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  271): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6903): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/System.out( 6868): propertyValue:false
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6903): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6903): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6903): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6903): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 6868): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 6903): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  847): Killing 6660:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10048/pid_6660/cgroup.procs: No such file or directory
,I/WebViewFactory( 6903): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6903): Time to load native libraries: 2 ms (timestamps 6112-6114)
I/LibraryLoader( 6903): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6903): Binding Chromium to main looper Looper (main, tid 1) {2233bf42}
I/LibraryLoader( 6903): Expected native library version number "",actual native library version number ""
I/chromium( 6903): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6903): Initializing chromium process, singleProcess=true
,W/art     ( 6903): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6903): ApplicationContext is null in ApplicationStatus
W/chromium( 6903): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6903): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6903): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6903): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6903): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6903): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6903): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6903): Remote Branch: 
I/Adreno-EGL( 6903): Local Patches: 
I/Adreno-EGL( 6903): Reconstruct Branch: 
V/AudioPolicyService(  275): registerClient() client 0xb57ee060, uid 10079
,W/AudioManagerAndroid( 6903): Requires BLUETOOTH permission
I/NSApplication( 6903): Starting up...
,I/ActivityManager(  847): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6969 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  847): Killing 6682:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10086/pid_6682/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6988 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  847): Killing 6713:com.google.android.music:main/u0a81 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  847): failed to open /acct/uid_10081/pid_6713/cgroup.procs: No such file or directory
,W/ResourcesManager( 6988): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 5545): Test app app.js loaded
I/jxcore-log( 5545): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@23300925 added. We now have 1 listener(s)
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
I/jxcore-log( 5545): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5545): 
,I/chromium( 5545): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  847): Killing 6743:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10021/pid_6743/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=7014 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7014): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7014): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7014): Error finding the version of the Email provider.....
E/Gmail   ( 7014): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7014): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7014): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7014): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7014): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7014): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7014): We do not support migrating this version of the Email provider.
I/Gmail   ( 7014): getAccountsCursor
I/ActivityManager(  847): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7058 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  847): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  847): Killing 6772:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/Gmail   ( 7014): Observing account changes for notifications
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_6772/cgroup.procs: No such file or directory
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicStore( 7058): Database version: 120
,I/Gmail   ( 7014): notifyAccountChanged
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
I/Gmail   ( 7014): getAccountsCursor
W/ContextImpl( 7058): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Gmail   ( 7014): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7014): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7014): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7014): calculateUnknownSyncRationalesAndPurgeInBackground: running
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7058): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7058): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Gmail   ( 7014): getAccountsCursor
I/art     (  847): Explicit concurrent mark sweep GC freed 17729(899KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.197ms total 140.477ms
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 7058): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7058): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7058): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,W/ActivityThread( 7058): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7058): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@358249b5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7058): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7058): GMSCore installation verified
I/ConfigStore( 7058): Config Database version: 1
,I/art     ( 5479): Explicit concurrent mark sweep GC freed 2538(98KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 353us total 25.242ms
,I/MediaRouter( 7058): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7058): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7058): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7058): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  847): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7101 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 25.229ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.305ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 20.920ms
,I/GHttpClientFactory( 7058): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7058): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 7101): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7101): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7101): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  847): Killing 6799:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10011/pid_6799/cgroup.procs: No such file or directory
,I/NotificationManager( 7058): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7101): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7101): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7101): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  847): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7134 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7101): JNI_OnLoad()
I/HubEmail( 7101): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7101): registerNatives()
I/HubEmail( 7101): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7101): registerNativeMethods()
I/HubEmail( 7101): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7101): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  847): Killing 6818:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10038/pid_6818/cgroup.procs: No such file or directory
,W/Settings( 7101): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7134): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7134): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7134): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7134): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7134): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7134): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7164 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7134): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7134): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7134): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 7134): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7134): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7134): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  847): Killing 6847:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10051/pid_6847/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7164): onCreate
W/AppUp4:DB( 7164):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7164):  setFingerPrint start
I/AppUp4:DB( 7164):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7164):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7164):  SDK version = 0
I/AppUp4:DB( 7164):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7164): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7164): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7164): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7164): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7164): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7164): onReceive
I/AppUp4:CustModeStarterReceiver( 7164): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7164): Context : android.app.ReceiverRestrictedContext@180dbbc9
D/AppUp4:CustFacade( 7164): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7164): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7164): begin check event
I/AppUp4:CustModeStarterReceiver( 7164): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7164): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7164): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7164): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7164): handleAsyncCustNotification do not startCustService
I/ActivityManager(  847): Killing 6868:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10061/pid_6868/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3223): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3223): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3223): networkInfo.isConnected() = true
D/PhoneState( 3223): setPdpRejectCasuse : false
,I/ActivityManager(  847): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7187 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7187): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7187): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7187): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  847): Killing 6903:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
D/PhoneMonitor( 7187): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7187): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7187): [parse] Load xml
V/TelephonyAutoProfiling( 7187): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7187): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7187): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  847): failed to open /acct/uid_10079/pid_6903/cgroup.procs: No such file or directory
,V/DownloadManager( 3202): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3202): DownloadService onCreate
I/DownloadManager( 3202): in removeSpuriousFiles
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3202): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@ed57db6 on behalf of 3202
,I/DownloadManager( 3202): in trimDatabase
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@10382224 on behalf of 3202
I/ActivityManager(  847): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7210 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3202): DownloadService onStartCommand
V/DownloadManager( 3202): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@2233bf42 on behalf of 3202
I/CheckinService( 5587): Checkin interval check for package: unspecified last checkin: 1454983570908 min interval config: 0 actual interval: 31650
,I/CheckinService( 5587): Checking schedule, now: 1454983602573 next: 1454983600824
I/CheckinService( 5587): active receiver: enabled
,V/DownloadManager( 3202): DownloadService onDestroy
I/CheckinService( 5587): Preparing to send checkin request
,I/EventLogService( 5587): Accumulating logs since 1454983562469
,D/WeatherAncestor( 2777): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:6:42
,D/UpdateThreadPoolManager( 2777): 2 : This is isUpdating : false
D/WeatherAncestor( 2777): connectivity changed - connection : true
D/Weather_cast( 2777): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2777): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:6:42
D/WeatherService( 2777): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7230 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2777): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2777): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2777): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7230): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5587): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5587): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 7230): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7230): MmsConfig.loadMmsSettings
I/Babel_SMS( 7230): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7230): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7230): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7230): MmsConfig.loadFromResources
E/Babel_SMS( 7230): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7230): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7230): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7230): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7230): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7230): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 7230): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7230): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7230): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7230): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7230): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7230): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7230): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7230): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7230): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7230): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7230): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7230): found sensor: Motion Accel, handle=46
W/Settings( 7230): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7230): startup - clean
I/Babel   ( 7230): deleted: false for 0
,I/art     ( 7230): CheckpointMarkThreadRoots callback created = 0xaaf4fad0
I/art     ( 7230): CheckpointMarkThreadRoots callback created = 0xaaf4faa0
,I/ActivityManager(  847): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7266 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/ActivityManager(  847): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7283 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7230): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7230): Unsupported mime audio/adpcm
W/AudioCapabilities( 7230): Unsupported mime audio/g726
W/AudioCapabilities( 7230): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7230): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7230): Unsupported mime video/mjpg
W/VideoCapabilities( 7230): Unsupported mime video/theora
,W/ResourcesManager( 7266): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7266): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AudioCapabilities( 7230): Unsupported mime audio/evrc
,W/AudioCapabilities( 7230): Unsupported mime audio/qcelp
W/VideoCapabilities( 7230): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7230): Unsupported mime audio/amr-wb-plus
V/AlarmManager(  847): RTC_WAKEUP set : Alarm{9b38ab8 type 0 when 1454983600824 com.google.android.gms} when 1454983600824
,W/AudioCapabilities( 7230): Unsupported mime audio/qcelp
I/MultiDex( 7266): VM with version 2.1.0 has multidex support
I/MultiDex( 7266): install
I/MultiDex( 7266): VM has multidex support, MultiDex support library is disabled.
W/AudioCapabilities( 7230): Unsupported mime audio/evrc
,I/ActivityManager(  847): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7302 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  847): RTC_WAKEUP set : Alarm{18065091 type 0 when 1454983603374 com.android.vending} when 1454983603374
,W/VideoCapabilities( 7230): Unsupported mime video/mp4v-esdp
,V/JNIHelp ( 7266): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/VideoCapabilities( 7230): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 7230): Unrecognized profile 2130706433 for video/avc
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7283): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/VideoCapabilities( 7230): Unrecognized profile 2130706433 for video/avc
W/ContextImpl( 7283): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/VideoCapabilities( 7230): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7230): Unrecognized profile 2130706433 for video/avc
,I/GAv4    ( 7283): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7283):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7283):   adb logcat -s GAv4
I/vclib   ( 7230): onServiceConnected
W/Babel   ( 7230): Attempted to change video mute state without an active call.
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/GAv4    ( 7283): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/ActivityThread( 7266): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7266): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2860cd92: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7266): Installed default security provider GmsCore_OpenSSL
W/ContextImpl( 7283): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/NotificationManager( 7266): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7266): com.google.android.gms: cancel(39789) by com.google.android.gms
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7283): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/libc-netbsd( 7230): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
I/NotificationManager( 7230): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7230): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7230): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7230): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  271): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 7230): propertyValue:false
,W/GAv4    ( 7283): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7230): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 7283): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 7266): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7266): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/Finsky  ( 7302): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/NativeLibraryUtils( 7266): Install completed successfully. count=14 extracted=0
,I/art     (  847): Explicit concurrent mark sweep GC freed 17956(860KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 8.585ms total 172.209ms
D/Finsky  ( 7302): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7302): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7302): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7302): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@7e73c90 on behalf of 7302
,D/Finsky  ( 7302): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 7302): Skipping gmscore version check
,D/Finsky  ( 7302): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7302): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7302): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/WebViewFactory( 7283): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/WVCdm   (  275): Instantiating CDM.
I/WVCdm   (  275): CdmEngine::OpenSession
I/WVCdm   (  275): Level3 Library Dec 11 2014 16:13:16
I/LibraryLoader( 7283): Time to load native libraries: 4 ms (timestamps 956-960)
,I/LibraryLoader( 7283): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7283): Binding Chromium to main looper Looper (main, tid 1) {2233bf42}
I/LibraryLoader( 7283): Expected native library version number "",actual native library version number ""
I/chromium( 7283): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
W/WVCdm   (  275): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  275): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  275): L1 library not specified. Falling Back to L3
,I/BrowserStartupController( 7283): Initializing chromium process, singleProcess=true
W/art     ( 7283): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7283): ApplicationContext is null in ApplicationStatus
,W/chromium( 7283): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7283): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7283): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7283): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7283): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7283): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7283): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7283): Remote Branch: 
I/Adreno-EGL( 7283): Local Patches: 
I/Adreno-EGL( 7283): Reconstruct Branch: 
I/WVCdm   (  275): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  275): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  275): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  275): CdmEngine::GenerateKeyRequest
D/WVCdm   (  275): PrepareKeyRequest: nonce=3738514815
,I/NSApplication( 7283): Starting up...
V/AudioPolicyService(  275): registerClient() client 0xb57ee0a0, uid 10079
,W/AudioManagerAndroid( 7283): Requires BLUETOOTH permission
I/ActivityManager(  847): Killing 6988:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/Finsky  ( 7302): [940] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7302): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
W/libprocessgroup(  847): failed to open /acct/uid_10086/pid_6988/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7389 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  847): Killing 7014:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10053/pid_7014/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Killing 7058:com.google.android.music:main/u0a81 (adj 15): empty #11
W/ResourcesManager( 7389): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/dex2oat ( 7406): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/libprocessgroup(  847): failed to open /acct/uid_10081/pid_7058/cgroup.procs: No such file or directory
,I/dex2oat ( 7406): dex2oat took 113.476ms (threads: 4)
,I/art     ( 7266): CheckpointMarkThreadRoots callback created = 0xb04d3e30
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Adreno-EGL( 7266): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7266): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7266): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7266): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7266): Remote Branch: 
I/Adreno-EGL( 7266): Local Patches: 
I/Adreno-EGL( 7266): Reconstruct Branch: 
I/art     ( 7266): CheckpointMarkThreadRoots callback created = 0xb04d3e10
,I/ActivityManager(  847): Killing 7101:com.lge.email/u0a21 (adj 15): empty #11
,I/Adreno-EGL( 7266): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7266): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7266): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7266): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7266): Remote Branch: 
I/Adreno-EGL( 7266): Local Patches: 
I/Adreno-EGL( 7266): Reconstruct Branch: 
,W/libprocessgroup(  847): failed to open /acct/uid_10021/pid_7101/cgroup.procs: No such file or directory
,I/ActivityManager(  847): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7420 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7420): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  847): Message: 20
,D/BluetoothManagerService(  847): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a45a448:true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
,D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
I/Adreno-EGL( 7266): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7266): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7266): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7266): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7266): Remote Branch: 
I/Adreno-EGL( 7266): Local Patches: 
I/Adreno-EGL( 7266): Reconstruct Branch: 
,I/AudioManager( 7420): getMode name:com.lge.qremote
I/AudioManager( 7420): getMode name:com.lge.qremote
,D/WearableService( 1734): callingUid 10006, callindPid: 1734
,E/MDM     ( 1734): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5587): Restart initialization of location
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
I/WVCdm   (  275): CdmEngine::OpenSession
,I/ActivityManager(  847): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7451 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.768ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.301ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 22.092ms
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7451): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7451): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7451): Error finding the version of the Email provider.....
E/Gmail   ( 7451): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7451): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7451): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7451): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7451): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7451): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7451): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7451): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7451): We do not support migrating this version of the Email provider.
W/ActivityManager(  847): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 7451): getAccountsCursor
D/Finsky  ( 7302): [945] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/NotificationManager(  847): android: cancelAsUser(2) by android
I/Gmail   ( 7451): Observing account changes for notifications
,W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 5587): Checkin interval check for package: unspecified last checkin: 1454983570908 min interval config: 0 actual interval: 35110
,E/MDM     ( 1734): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1734): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5587): Restart initialization of location
D/libc-netbsd( 7302): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7302): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7302): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7302): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  271): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  271): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1734): No location to return for getLastLocation()
W/FusedLocationProvider( 1734): location=null
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 7302): propertyValue:false
W/ContextImpl( 3597): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/Gmail   ( 7451): notifyAccountChanged
,I/ActivityManager(  847): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7514 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7420): Create singleton instance
,I/Gmail   ( 7451): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7451): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/UEI.SmartControl( 7514): Quickset Services start...
,I/AudioManager( 7420): getMode name:com.lge.qremote
I/UEI.SmartControl( 7514): Manufacture = LGE
D/UEI.SmartControl( 7514): File observer start...
I/Gmail   ( 7451): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
E/UEI.SmartControl( 7514): IR Port is disabled: false
D/UEI.SmartControl( 7514): Starting file observer...
D/UEI.SmartControl( 7514): Extracting JNI libs...
D/UEI.SmartControl( 7514): --- this system supports 32-bit or 64-bit only
,I/Gmail   ( 7451): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7451): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/WVCdm   (  275): CdmEngine::CloseSession
I/WVCdm   (  275): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  275): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  275): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  275): CdmEngine::GenerateKeyRequest
D/WVCdm   (  275): PrepareKeyRequest: nonce=579165418
I/Gmail   ( 7451): getAccountsCursor
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7514): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7514): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7514): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  847): Killing 7134:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/UEI.SmartControl( 7514): --- Selecting new region: 2
,I/UEI.SmartControl( 7514): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7514): Platform has CIR...
D/UEI.SmartControl( 7514): NO CIR support, need to check package...
I/UEI.SmartControl( 7514): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7514): QS Service created
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_7134/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 7514): QS start get config
,D/UEI.SmartControl( 7514): Loading JNI Libs...
,D/UEI.SmartControl( 7514):  configuring local db...
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/UEI.SmartControl( 7514):  ---- Has DB8: true
,D/UEI.SmartControl( 7514): QS start statue = true Error code = 0
D/UEI.SmartControl( 7514): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7514): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7514): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7514): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7514): IrrcClient ++ 
D/irrcClient( 7514): getIrrcService ++ 
D/irrcClient( 7514): getIrrcService -- 
D/irrcClient( 7514): IrrcClient -- 
W/irrc_jni( 7514): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7514): Services init done
,D/UEI.SmartControl( 7514): QS Service init finished
D/UEI.SmartControl( 7514): QS Service version name: 0.1.73
D/UEI.SmartControl( 7514): QS Service version code: 1073
D/UEI.SmartControl( 7514): Service requested: Control
I/UEI.SmartControl( 7514): Device manager: loading config....
D/UEI.SmartControl( 7514): Config is loaded...
,D/UEI.SmartControl( 7514): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7514): Internal service binding...
D/UEI.SmartControl( 7514):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7514): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7514): -----IControl: 11
D/UEI.SmartControl( 7514): Caller: com.lge.qremote
D/UEI.SmartControl( 7514): ------------ IControl registerCallback...
I/UEI.SmartControl( 7514): Registering callback...
D/UEI.SmartControl( 7514): -----IControl: 19
D/UEI.SmartControl( 7514): Caller: com.lge.qremote
I/UEI.SmartControl( 7514): Registering Services Ready callback...
I/UEI.SmartControl( 7514): Notify client services are ready...
,D/UEI.SmartControl( 7514): -----IControl: 8
D/UEI.SmartControl( 7514): Caller: com.lge.qremote
I/AudioManager( 7420): getMode name:com.lge.qremote
I/ActivityManager(  847): Killing 7210:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/ActivityManager(  847): Killing 7164:com.lge.appbox.client/u0a11 (adj 15): empty #12
,I/art     (  847): Explicit concurrent mark sweep GC freed 17136(762KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.692ms total 162.214ms
,W/libprocessgroup(  847): failed to open /acct/uid_10051/pid_7210/cgroup.procs: No such file or directory
,W/libprocessgroup(  847): failed to open /acct/uid_10011/pid_7164/cgroup.procs: No such file or directory
I/AudioManager( 7420): getMode name:com.lge.qremote
I/AudioManager( 7420): getMode name:com.lge.qremote
I/WVCdm   (  275): CdmEngine::CloseSession
,I/WVCdm   (  275): L3 Terminate.
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 115690917044; DSPS: 3882331; Offset : -2798667347
,I/MusicWidget( 2679): mDelayedStopHandler : unbind
,I/MusicBrowser( 2787): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2787): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2787): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2787): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2787): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2787): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2787): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2787): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  847):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1ccb48dfcom.lge.music.MediaPlaybackService$6@2e3c292c
,D/MusicBrowser( 2787): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2787): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2787): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2787): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2787): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@42d4b85
,I/MusicBrowser( 2787): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2787): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2787): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2787): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2787): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2787): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2787): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2787): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2787): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2787): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2787): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2787): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2787): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2787): reset
V/MediaPlayer[Native]( 2787): setListener
V/MediaPlayer[Native]( 2787): disconnect
V/MediaPlayer[Native]( 2787): destructor
,V/AudioFlinger(  275): releasing 18 from 2787 for -1
V/AudioFlinger(  275):  decremented refcount to 0
V/AudioFlinger(  275): purging stale effects
V/MediaPlayer[Native]( 2787): disconnect
D/MusicBrowser( 2787): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2787): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2787): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2787): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2787): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2787): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2787): [SmartShareManagerClient] unregisterListener: 137437173
W/SmartShareClient( 2787): [SmartShareManagerClient] unregisterListener invalid listener: 137437173
I/SmartShareClient( 2787): [SmartShareManagerClient] terminate service: 2787/MediaPlaybackService/586007443
E/HomeCloudIF( 2787): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2787): [SmartShareManagerClient] unbindService context:android.app.Application@2125718a
,V/CloudHub( 2787): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2787): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2787): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2787): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2787): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  847): Killing 7230:com.google.android.talk/u0a61 (adj 15): empty #11
,I/CloudHub( 2787): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29985
W/libprocessgroup(  847): failed to open /acct/uid_10061/pid_7230/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 5587): Classify the device as Phone.
,D/libc-netbsd( 5587): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5587): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5587): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5587): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 5587): propertyValue:false
D/libc-netbsd( 5587): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5587): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5587): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5587): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5587): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5587): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5587): Sending checkin request (9743 bytes)
,I/CheckinRequestBuilder( 5587): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5587): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 5479): Explicit concurrent mark sweep GC freed 3197(129KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.187ms total 29.234ms
,I/GAV2    ( 7451): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 5587): Google Analytics 8.4.89 is starting up.
,I/CheckinRequestBuilder( 5587): Classify the device as Phone.
,I/CheckinTask( 5587): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5587): Checking schedule, now: 1454983610965 next: 1455510859959
I/CheckinService( 5587): active receiver: disabled
,I/CheckinService( 5587): Checking schedule, now: 1454983611012 next: 1455510859959
I/CheckinService( 5587): active receiver: disabled
,D/CheckinService( 5587): Recording last checkin time for package unspecified as 1454983611021
,V/SetupWizard( 7187): Connected to Gservices successfully
,D/GCM     ( 1734): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  847): Killing 6969:com.android.chrome/u0a48 (adj 15): empty #11
I/ActivityManager(  847): Killing 7283:com.google.android.apps.magazines/u0a79 (adj 15): empty #12
,W/libprocessgroup(  847): failed to open /acct/uid_10048/pid_6969/cgroup.procs: No such file or directory
,W/libprocessgroup(  847): failed to open /acct/uid_10079/pid_7283/cgroup.procs: No such file or directory
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7514): Internal timer expired: 1
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1368): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  847): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7597 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1368): onReceive = android.intent.action.PACKAGE_CHANGED
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
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/administrator(  847): Handling package changes for user 0
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 7597): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  847): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  847): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  847): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  847): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/BackupManagerService(  847): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  847): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@15fd01d1
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Babel_SMS( 7597): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7597): MmsConfig.loadMmsSettings
I/Babel_SMS( 7597): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7597): MmsConfig.loadFromDatabase
W/ResourceType(  847): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  847): Process com.google.android.apps.plus (pid 7389) has died
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
,E/Babel_SMS( 7597): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7597): MmsConfig.loadFromResources
D/LocationProviderProxy(  847): applying state to connected service
E/Babel_SMS( 7597): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7597): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7597): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7597): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7597): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7597): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7597): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7597): found sensor: LGE Linear Acceleration Sensor, handle=30
,D/SensorManager( 7597): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7597): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7597): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7597): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7597): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7597): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7597): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7597): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7597): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7597): found sensor: Motion Accel, handle=46
I/art     ( 7597): CheckpointMarkThreadRoots callback created = 0xaaf39460
,W/Settings( 7597): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7597): startup - clean
,I/art     ( 7597): CheckpointMarkThreadRoots callback created = 0xaaf39440
,I/Babel   ( 7597): deleted: false for 0
,W/AudioCapabilities( 7597): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7597): Unsupported mime audio/adpcm
W/AudioCapabilities( 7597): Unsupported mime audio/g726
W/AudioCapabilities( 7597): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7597): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7597): Unsupported mime video/mjpg
W/VideoCapabilities( 7597): Unsupported mime video/theora
I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7637 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 7597): Unsupported mime audio/evrc
,W/AudioCapabilities( 7597): Unsupported mime audio/qcelp
W/VideoCapabilities( 7597): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7597): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7597): Unsupported mime audio/qcelp
W/AudioCapabilities( 7597): Unsupported mime audio/evrc
I/AppUp4:AppBoxCP( 7637): onCreate
,W/AppUp4:DB( 7637):  [AppBoxDatabaseHelper] construct
W/VideoCapabilities( 7597): Unsupported mime video/mp4v-esdp
I/AppUp4:DB( 7637):  setFingerPrint start
,I/AppUp4:DB( 7637):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7637):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7637):  SDK version = 0
I/AppUp4:DB( 7637):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7637): AppBoxApplication onCreate()
I/VideoCapabilities( 7597): Unsupported profile 4 for video/mp4v-es
I/AppUp4:CustModeStarterReceiver( 7637): onReceive
I/AppUp4:CustModeStarterReceiver( 7637): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7637): Context : android.app.ReceiverRestrictedContext@608c082
D/AppUp4:CustFacade( 7637): isCustomizationCompleted : false
W/VideoCapabilities( 7597): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 7637): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7637): begin check event
I/AppUp4:CustModeStarterReceiver( 7637): Event For Nothing, skip.
W/VideoCapabilities( 7597): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7597): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7597): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  847): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7657 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  847): Process com.android.vending (pid 7302) has died
,W/ResourcesManager( 7657): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7657): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7657): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/vclib   ( 7597): onServiceConnected
,W/Babel   ( 7597): Attempted to change video mute state without an active call.
I/NotificationManager( 7597): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7597): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7597): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7597): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppConfig( 7657): Total System Memory = 906309632
,I/GalleryUtils( 7657): Application Heap = 96 MB
,I/AppConfig( 7657): App Tier : NOT_DEF
D/SystemHelper( 7657): region [EU], country [EU], operator [OPEN], sub-operator []
,W/System  ( 7597): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7597): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  847): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7680 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/NotificationManager( 7597): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 7680): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7680): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7680): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7680): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7680): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7680): BUILD Country: EU
,I/SystemConfig( 7680): BUILD Operator: OPEN
I/ActivityManager(  847): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7706 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  847): Killing 7451:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  847): failed to open /acct/uid_10053/pid_7451/cgroup.procs: No such file or directory
I/SystemConfig( 7680): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7680): existFile = false
I/SystemConfig( 7680): canReadFile = false
I/SystemConfig( 7680): systemFeature RCS result false
D/SystemConfig( 7680): refreshRcsSupport() :false
,I/LockScreenSettings( 7706): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7706): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7706): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7706): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7706): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7706): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  847): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7723 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  847): Killing 2787:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  275): 2787 died, releasing its sessions
V/AudioFlinger(  275):  pid 1747 @ 0
V/AudioFlinger(  275):  pid 3223 @ 1
V/AudioFlinger(  275):  pid 3223 @ 2
,W/libprocessgroup(  847): failed to open /acct/uid_10028/pid_2787/cgroup.procs: No such file or directory
,W/ResourcesManager( 7723): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1942): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  847): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7748 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  847): Killing 7187:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1942): UpdateCorporaTask done [took 78 ms] updated apps [took 78 ms] 
,W/libprocessgroup(  847): failed to open /acct/uid_10038/pid_7187/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/Finsky  ( 7748): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7748): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7748): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7748): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7748): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@3948d989 on behalf of 7748
D/Finsky  ( 7748): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7748): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7748): Skipping gmscore version check
D/Finsky  ( 7748): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5587): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5587): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7748): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5587): updateResources: need to parse f{com.google.android.gms}
,I/art     (  847): Explicit concurrent mark sweep GC freed 29902(1487KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.357ms total 151.512ms
,I/art     ( 1734): Explicit concurrent mark sweep GC freed 28287(2001KB) AllocSpace objects, 31(496KB) LOS objects, 40% free, 13MB/22MB, paused 1.143ms total 89.145ms
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/Icing   ( 5587): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5587): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  847): Killing 7266:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  847): failed to open /acct/uid_10006/pid_7266/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  847): Killing 7514:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7420): android.os.DeadObjectException
,W/System.err( 7420): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7420): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7420): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7420): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7420): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7420): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7420): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7420): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7420): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7420): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7420): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7420): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7420): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7420): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7420): android.os.DeadObjectException
W/System.err( 7420): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7420): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7420): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7420): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7420): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7420): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7420): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7420): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7420): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7420): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7420): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7420): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7420): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7420): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7420): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  847): failed to open /acct/uid_10089/pid_7514/cgroup.procs: No such file or directory
W/ActivityManager(  847): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  847): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7836 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7836): Quickset Services start...
,I/UEI.SmartControl( 7836): Manufacture = LGE
D/UEI.SmartControl( 7836): File observer start...
E/UEI.SmartControl( 7836): IR Port is disabled: false
D/UEI.SmartControl( 7836): Starting file observer...
D/UEI.SmartControl( 7836): Extracting JNI libs...
D/UEI.SmartControl( 7836): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 7836): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7836): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7836): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7836): --- Selecting new region: 2
I/UEI.SmartControl( 7836): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7836): Platform has CIR...
D/UEI.SmartControl( 7836): NO CIR support, need to check package...
I/UEI.SmartControl( 7836): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7836): QS Service created
E/UEI.SmartControl( 7836): QS start get config
,D/UEI.SmartControl( 7836): Loading JNI Libs...
,D/UEI.SmartControl( 7836):  configuring local db...
D/UEI.SmartControl( 7836):  ---- Has DB8: true
D/UEI.SmartControl( 7836): QS start statue = true Error code = 0
D/UEI.SmartControl( 7836): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7836): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7836): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7836): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7836): IrrcClient ++ 
D/irrcClient( 7836): getIrrcService ++ 
D/irrcClient( 7836): getIrrcService -- 
D/irrcClient( 7836): IrrcClient -- 
W/irrc_jni( 7836): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7836): Services init done
,I/UEI.SmartControl( 7836): Device manager: loading config....
D/UEI.SmartControl( 7836): QS Service init finished
D/UEI.SmartControl( 7836): Config is loaded...
D/UEI.SmartControl( 7836): QS Service version name: 0.1.73
D/UEI.SmartControl( 7836): QS Service version code: 1073
D/UEI.SmartControl( 7836): Service requested: Control
I/ActivityManager(  847): Killing 7420:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7836):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7836): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7836): Internal service binding...
W/libprocessgroup(  847): failed to open /acct/uid_10106/pid_7420/cgroup.procs: No such file or directory
D/PowerManagerServiceEx(  847): acquireWakeLockInternal: lock=950332939, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=847
,D/WeatherService( 2777): 2 : TimeTick Intent has been received, Time(hour:min:sec) 3:7:0
,D/WeatherService( 2777): 2 : TimeTick Intent And Screen On
D/WeatherService( 2777): 2 : SDK version : 21
W/ActivityManager(  847): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2777): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2777): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2777): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2777): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2777): 2 : This is isUpdating : false
D/WeatherService( 2777): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2777): 2 : buildUpdate, appWidgetId: 2
I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
D/WeatherTheme( 2777): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2777): 2 : Fixed theme : optimus
,I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
D/WeatherReflect( 2777): 2 : Map key string is -2
,I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
,D/lim     ( 2777): 2 : time = 03:07
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/WeatherReflect( 2777): Model Name : LG-D722
D/WeatherTheme( 2777): 2 : Different view - status_min_formatted : 06 != 07
D/WeatherTheme( 2777): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2777): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2777): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2777): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2777): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2777): forecast size is 0
,D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2777): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2777): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2777): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2777): url is : null
D/Theme   ( 2777): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2777): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2777): 2 : update view, appWidgetId: 2
D/WeatherService( 2777): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 3:7:0
D/PowerManagerServiceEx(  847): releaseWakeLockInternal: lock=950332939 [*alarm*], flags=0x0
,D/charger_monitor(  487): init target 500000
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
D/charger_monitor(  487): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7836): Internal timer expired: 1
,D/UEI.SmartControl( 7836): Service.onUnbind: IControl
D/UEI.SmartControl( 7836): Service.onDestroy
W/System.err( 7836): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@2fc688fc
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
E/UEI.SmartControl( 7836): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@2fc688fc
D/UEI.SmartControl( 7836): Shutdown IRRCPlayer... 
,W/irrc_jni( 7836): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7836): ~IrrcClient ++ 
D/irrcClient( 7836): ~IrrcClient -- 
W/irrc_jni( 7836): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7836): Blaster closed
D/UEI.SmartControl( 7836): Blaster closed
,D/UEI.SmartControl( 7836): Shut down QS...
D/UEI.SmartControl( 7836): Stopped file observer...
I/UEI.SmartControl( 7836): QS lib stop result = true
D/UEI.SmartControl( 7836): QS shutdown complete
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 135691623286; DSPS: 4537714; Offset : -2798663191
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{642e4e8 type 2 when 145238 com.google.android.gms} when 145238
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1734): Vacuum at: now=1454983638677 tag=VacuumService
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PhenotypeConfigurator( 1734): Scheduling Phenotype for one-off execution 217 seconds from now (1454983639158)
,D/GetConfigurationSnapshotOperation( 1734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1734): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1734): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 1734): propertyValue:false
D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1734): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1734): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  847): android: cancelAsUser(2) by android
,I/NotificationManager( 1734): com.google.android.gms: cancel(0) by com.google.android.gms
D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  847): ALS enabled for SRE
,D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29189 ms ago)
D/qdlights(  847): set_light_backlight: 252
,D/qdlights(  847): set_light_backlight: 248
D/qdlights(  847): set_light_backlight: 245
,D/qdlights(  847): set_light_backlight: 242
,D/qdlights(  847): set_light_backlight: 238
,D/qdlights(  847): set_light_backlight: 235
,D/qdlights(  847): set_light_backlight: 232
,D/qdlights(  847): set_light_backlight: 228
,D/qdlights(  847): set_light_backlight: 225
,D/qdlights(  847): set_light_backlight: 222
,D/qdlights(  847): set_light_backlight: 218
,D/qdlights(  847): set_light_backlight: 215
,D/qdlights(  847): set_light_backlight: 212
,D/qdlights(  847): set_light_backlight: 208
,D/qdlights(  847): set_light_backlight: 205
,D/qdlights(  847): set_light_backlight: 202
,D/qdlights(  847): set_light_backlight: 198
,D/qdlights(  847): set_light_backlight: 195
,D/qdlights(  847): set_light_backlight: 192
,D/qdlights(  847): set_light_backlight: 188
,D/qdlights(  847): set_light_backlight: 185
,D/qdlights(  847): set_light_backlight: 182
,D/qdlights(  847): set_light_backlight: 178
,D/qdlights(  847): set_light_backlight: 175
,D/qdlights(  847): set_light_backlight: 172
,D/qdlights(  847): set_light_backlight: 168
,D/qdlights(  847): set_light_backlight: 165
,D/qdlights(  847): set_light_backlight: 162
,D/qdlights(  847): set_light_backlight: 158
,D/qdlights(  847): set_light_backlight: 155
,D/qdlights(  847): set_light_backlight: 152
,D/qdlights(  847): set_light_backlight: 148
,D/qdlights(  847): set_light_backlight: 145
,D/qdlights(  847): set_light_backlight: 142
,D/qdlights(  847): set_light_backlight: 138
,D/qdlights(  847): set_light_backlight: 135
,D/qdlights(  847): set_light_backlight: 132
,D/qdlights(  847): set_light_backlight: 128
,D/qdlights(  847): set_light_backlight: 125
,D/qdlights(  847): set_light_backlight: 122
,D/qdlights(  847): set_light_backlight: 118
,D/qdlights(  847): set_light_backlight: 115
,D/qdlights(  847): set_light_backlight: 112
,D/qdlights(  847): set_light_backlight: 108
,D/qdlights(  847): set_light_backlight: 105
,D/qdlights(  847): set_light_backlight: 102
,D/qdlights(  847): set_light_backlight: 98
,D/qdlights(  847): set_light_backlight: 95
,D/qdlights(  847): set_light_backlight: 92
,D/qdlights(  847): set_light_backlight: 88
,D/qdlights(  847): set_light_backlight: 85
,D/qdlights(  847): set_light_backlight: 82
,D/qdlights(  847): set_light_backlight: 78
,D/qdlights(  847): set_light_backlight: 75
,D/qdlights(  847): set_light_backlight: 72
,D/qdlights(  847): set_light_backlight: 68
,D/qdlights(  847): set_light_backlight: 65
,D/qdlights(  847): set_light_backlight: 62
,D/qdlights(  847): set_light_backlight: 58
,D/qdlights(  847): set_light_backlight: 55
,D/qdlights(  847): set_light_backlight: 52
,D/qdlights(  847): set_light_backlight: 48
,D/qdlights(  847): set_light_backlight: 45
,D/qdlights(  847): set_light_backlight: 42
,D/qdlights(  847): set_light_backlight: 38
,D/qdlights(  847): set_light_backlight: 35
,D/qdlights(  847): set_light_backlight: 32
,D/qdlights(  847): set_light_backlight: 28
,D/qdlights(  847): set_light_backlight: 25
,D/qdlights(  847): set_light_backlight: 22
,D/qdlights(  847): set_light_backlight: 18
,D/qdlights(  847): set_light_backlight: 15
,D/qdlights(  847): set_light_backlight: 12
,D/qdlights(  847): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 155692364112; DSPS: 5193098; Offset : -2798654656
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  847): ALS enabled for SRE
D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36175 ms ago)
I/PowerManagerService(  847): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  847): ALS enabled for SRE
D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36193 ms ago)
,W/ContextImpl(  847): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  847): Sleeping (uid 1000)...
D/LPWGController(  847): [updateScreenState] screen on = false
,D/LPWGController(  847): disable proximity sensor
D/LPWGController(  847): enable proximity sensor
,I/SensorManager(  847): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@34ab1230] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  847): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  847): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  847): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  847): activate: handle is 48, enable
,V/sensors_hal_Ctx(  847): activate sensors is 1400000000000
D/sensors_hal_Thresh(  847): enable: handle=48
I/sensors_hal_SAM(  847): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  847): waitForResponse: timeout=1000
V/sensors_hal_SAM(  847): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  847): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  847): enable: Received response: 0
D/PowerManagerServiceEx(  847): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36255 ms ago)
I/Adreno-EGL(  847): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  847): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  847): Build Date: 03/02/15 Mon
I/Adreno-EGL(  847): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  847): Remote Branch: 
I/Adreno-EGL(  847): Local Patches: 
I/Adreno-EGL(  847): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (595 us)
,I/Sensors (  426): sns_pwr.c(273):acquiring wakelock
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
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/SensorManager(  847): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  847): activate: handle is 46, disable
V/sensors_hal_Ctx(  847): activate sensors is 1000000000000
D/sensors_hal_LP2(  847): enable: handle=46
,D/sensors_hal_LP2(  847): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  847): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  847): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  847): Display changed displayId=0
,V/sensors_hal_SAM(  847): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  847): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1747): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  847): Excessive delay in setPowerMode(): 231ms
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  847): Got set_interactive hint
D/KeyguardViewMediator( 1368): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1368): notifyScreenOffLocked
D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
D/KeyguardViewMediator( 1368): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1368): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1368): unregisterProximitySensor
D/StatusBarWindowView( 1368): onScreenTurnedOff why = 3
,I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1368): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/WifiServerServiceExt(  847): sendKtScanInterval  mRtspPlay : false
I/WifiServerServiceExt(  847): set CMD_KT_SCAN_INTERVAL
,V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=on, calling pid 847
D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=on
V/voice   (  275): voice_set_parameters: enter: screen_state=on
V/compress_voip(  275): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  275): voice_extn_compress_voip_set_parameters: exit
V/voice   (  275): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  275): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  275): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  275): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  275): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  275): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/GpsLocationProvider(  847): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1804): stopPatternFlashing()
,D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1804): lockStatus = 0
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1787): action : android.intent.action.SCREEN_ON
I/LEDService( 1804): updateLightsLocked : turn off led
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1804): RESTART MSG
D/NfcServiceNXP( 1787): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1787): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
,D/LNfcService( 1787): isRequireNfcCRouting() return true
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
D/Ulp_jni (  847): JNI:system_update. Event-0
D/SplitWindow(  847): check instance of lgWin Window{26c343cf u0 SearchPanel}
,D/InputDispatcher(  847): Window went away: Window{22d025ed u0 SearchPanel}
,I/[SystemUI]Clock( 1368): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1368): time changed, timezoneChanged : false
,V/PhoneApp( 1747): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): ACTION_SCREEN_ON
,D/WeatherService( 2777): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:7:31
D/WeatherService( 2777): 2 : ACTION screen on
D/WeatherService( 2777): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2777): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2777): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:7:31
D/AppCleanupService( 4052): android.intent.action.SCREEN_ON
,V/AudioFlinger(  275): setParameters(): io 0, keyvalue screen_state=off, calling pid 847
,D/audio_hw_primary(  275): adev_set_parameters: enter: screen_state=off
V/voice   (  275): voice_set_parameters: enter: screen_state=off
V/compress_voip(  275): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  275): voice_extn_compress_voip_set_parameters: exit
V/voice   (  275): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  275): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  275): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  275): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  275): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  275): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  275): adev_set_parameters: exit with code(0)
I/Sensors (  426): sns_pwr.c(301):releasing wakelock
D/WifiController(  847): CMD_SCREEN_OFF 
D/WifiController(  847): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  847): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1804): clear
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1787): action : android.intent.action.SCREEN_OFF
I/LEDService( 1804): updateLightsLocked : turn on led
E/LEDService( 1804): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1804): Can't handle this request of patternId:0
D/LEDHandler( 1804): RESTART MSG
D/NfcServiceNXP( 1787): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1747): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  847): ACTION_SCREEN_OFF
D/WeatherService( 2777): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:7:31
D/WeatherService( 2777): 2 : ACTION screen off
D/WeatherService( 2777): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2777): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:7:31
D/AppCleanupService( 4052): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4052): AppUsageStatsSaveTask
,E/NxpNfcJni( 1787): getReconnectState = 0x0
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1787): getDefaultRoute
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
D/NfcService( 1787): screenState= 1
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,E/NxpNfcJni( 1787): getReconnectState = 0x0
,D/KeyguardViewMediator( 1368): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{e7215c type 2 when 162148 com.android.systemui} when 162148
,D/PhoneUtils( 1747): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
,V/TelecomServiceImpl( 1747): getCallState : 0
D/PhoneUtils( 1747): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1747): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1368): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1368): doKeyguard: not showing because lockscreen is off
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 175693107750; DSPS: 5848483; Offset : -2798674219
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{37bb6c65 type 2 when 181740 android} when 181740
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1734): disconnect managed GoogleApiClient
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
D/PowerManagerServiceEx(  847): acquireWakeLockInternal: lock=950332939, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=847
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{10f21d3a type 2 when 188086 com.google.android.gms} when 188086
,D/PowerManagerServiceEx(  847): releaseWakeLockInternal: lock=950332939 [*alarm*], flags=0x0
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 195693828107; DSPS: 6503866; Offset : -2798655584
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 215694511901; DSPS: 7159249; Offset : -2798673720
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 235695329446; DSPS: 7814635; Offset : -2798649658
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 255696094594; DSPS: 8470020; Offset : -2798647346
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 275696771097; DSPS: 9125403; Offset : -2798672694
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5545): TAP version 13
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # multiplex can send data
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 1 String should be length:200
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # enqueue and run in order
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 2 firstPromise setTimeout
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 3 firstPromise result
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 4 firstPromise testValue
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 5 secondPromise setTimeout
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 6 secondPromise result
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 7 secondPromise testValue
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 8 thirdPromise in promise
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 9 thirdPromise result
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 10 thirdPromise testValue
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # basic
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 11 sane
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # another
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 12 sane
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 13 should be equal
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 14 null
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 15 (unnamed assert)
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 16 should be equal
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 17 should not throw
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 18 (unnamed assert)
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 19 (unnamed assert)
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 20 should not throw
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 21 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 22 should be equal
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 23 should be equal
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # failed to get mobile documents path
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 24 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 25 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 26 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 27 should be equal
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # #init should register the networkChanged event
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 28 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # #startBroadcasting should throw on null device name
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 29 should throw
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 30 should throw
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 31 should throw
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 32 should throw
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # #startBroadcasting should throw on negative port
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 33 should throw
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # #startBroadcasting should throw on too large port
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 34 should throw
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 35 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 36 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 37 should be equal
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
I/jxcore-log( 5545): ok 38 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 39 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 40 should be equal
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 41 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 42 should be equal
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 43 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 44 should be equal
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 45 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 46 should be equal
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 47 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 48 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 49 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 50 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 51 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): ok 52 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): ok 53 should be equal
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15db5afa added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983781959.5545
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983781959.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983781959.5545, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983781959.5545","ra":"F8:95:C7:87:85:54"}
,D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5545): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: {"pi":"F8:95:C7:87:85:54","pn":"1454983781959.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454983781959.5545","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,I/bt-btif ( 1970): BTA_JvCreateRecordByUser
,I/bt-btif ( 1970): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1970): [BTUI] createSocketChannel FD=87 mFd=85
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Waiting for incoming connections...
,D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@dbf77dfa target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@dbf77dfa target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState add service
D/LGWifiP2pService(  847): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983781959.5545, mode: WIFI
,D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast true
I/jxcore-log( 5545): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 5545): 
I/io.jxcore.node.ConnectionHelper( 5545): stop
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Exiting thread
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): onServerStopped
I/bt-btif ( 1970): BTA_JvDeleteRecord
I/bt-btif ( 1970): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5545): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): stop: Stopping services
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): release: No more listeners, de-initializing...
,I/wpa_supplicant( 2717): p2p0: CTRL-EVENT-SCAN-STARTED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5545): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5545): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 5545): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29f42cc6 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
,D/LGWifiP2pService(  847): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local services cleared successfully
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
D/LGWifiP2pService(  847): InactiveState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-2ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): P2pEnabledState clear service request
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/LGWifiP2pService(  847): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5545): Service requests cleared successfully
D/LGWifiP2pService(  847): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast false
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782169.5545
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
,D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782169.5545","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782169.5545, mode: WIFI
W/BluetoothAdapter( 5545): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/bt-btif ( 1970): BTA_JvCreateRecordByUser
,I/bt-btif ( 1970): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Waiting for incoming connections...
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782169.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: {"pi":"F8:95:C7:87:85:54","pn":"1454983782169.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454983782169.5545","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e2be8086 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@e2be8086 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState add service
D/LGWifiP2pService(  847): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Starting P2P device discovery...
,D/LGWifiP2pService(  847): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  847): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782169.5545, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5545): start: OK
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5545): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 5545): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): onServerStopped
I/wpa_supplicant( 2717): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
I/bt-btif ( 1970): BTA_JvDeleteRecord
I/bt-btif ( 1970): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5545): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): stop: Stopping services
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): stop: Stopping P2P device discovery...
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): release: No more listeners, de-initializing...
D/LGWifiP2pService(  847): InactiveState{ when=-4ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: No more listeners, de-initializing...
D/LGWifiP2pService(  847): P2pEnabledState{ when=-4ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5545): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: NOT_STARTED
,D/LGWifiP2pService(  847): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local services cleared successfully
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5545): Service requests cleared successfully
I/jxcore-log( 5545): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 5545): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22764f52 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782236.5545
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782236.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5545): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1970): BTA_JvCreateRecordByUser
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782236.5545, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): bind: Binding a new listener
I/bt-btif ( 1970): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782236.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: {"pi":"F8:95:C7:87:85:54","pn":"1454983782236.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454983782236.5545","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@774649d0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@774649d0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState add service
D/LGWifiP2pService(  847): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Starting P2P device discovery...
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: RUNNING_WIFI
I/wpa_supplicant( 2717): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782236.5545, mode: WIFI
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
,D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 5545): start: OK
D/LGWifiP2pService(  847): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 5545): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 5545): 
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5545): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: 1 listener(s) left
I/bt-btif ( 1970): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: NOT_STARTED
I/bt-btif ( 1970): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopForRestart
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5545): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPe,erDiscoverer( 5545): stop: Stopping services
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: false
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): release: No more listeners, de-initializing...
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5545): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: NOT_STARTED
D/LGWifiP2pService(  847): remove client information from framework
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local services cleared successfully
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5545): Service requests cleared successfully
I/jxcore-log( 5545): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 5545): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	,Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29860e9e added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782294.5545
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782294.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5545): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1970): BTA_JvCreateRecordByUser
,I/bt-btif ( 1970): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782294.5545, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782294.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: {"pi":"F8:95:C7:87:85:54","pn":"1454983782294.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454983782294.5545","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@be6761c8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@be6761c8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState add service
D/LGWifiP2pService(  847): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: RUNNING_WIFI
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782294.5545, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5545): start: OK
I/wpa_supplicant( 2717): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  847): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5545): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 5545): 
I/wpa_supplicant( 2717): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 5545): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThr,ead( 5545): shutdown
D/LGWifiP2pService(  847): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast false
I/bt-btif ( 1970): BTA_JvDeleteRecord
I/bt-btif ( 1970): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopForRestart
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5545): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): onServerStopped
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: No more listeners, de-initializing...
D/LGWifiP2pService(  847): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5545): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local services cleared successfully
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5545): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 5545): 
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5545): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@154076aa added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState(), - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782351.5545
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782351.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5545): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782351.5545, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): bind: Binding a new listener
I/bt-btif ( 1970): BTA_JvCreateRecordByUser
I/bt-btif ( 1970): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782351.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: {"pi":"F8:95:C7:87:85:54","pn":"1454983782351.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454983782351.5545","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  847): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@44303954 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@44303954 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState add service
D/LGWifiP2pService(  847): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782351.5545, mode: WIFI
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  847): discovery change broadcast true
I/jxcore-log( 5545): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 5545): 
I/io.jxcore.node.ConnectionHelper( 5545): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): onServerStopped
I/bt-btif ( 1970): BTA_JvDeleteRecord
I/bt-btif ( 1970): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5545): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.int,ernal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): stop: Stopping P2P device discovery...
,D/LGWifiP2pService(  847): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local services cleared successfully
D/LGWifiP2pService(  847): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): P2P-FIND-STOPPED 
,D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast false
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): release: No more listeners, de-initializing...
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5545): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5545): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5545): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 5545): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e875376 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi ,supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782409.5545
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782409.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: OK
,I/io.jxcore.node.ConnectionHelper( 5545): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5545): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1970): BTA_JvCreateRecordByUser
I/bt-btif ( 1970): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782409.5545, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782409.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: {"pi":"F8:95:C7:87:85:54","pn":"1454983782409.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454983782409.5545","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Starting P2P device discovery...
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9aa144cc target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: true
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9aa144cc target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService(  847): P2pEnabledState add service
D/LGWifiP2pService(  847): add a new client
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782409.5545, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5545): start: OK
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  847): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 5545): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 5545): 
D/LGWifiP2pService(  847): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast false
I/io.jxcore.node.Co,nnectionHelper( 5545): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: NOT_STARTED
I/bt-btif ( 1970): BTA_JvDeleteRecord
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopForRestart
I/bt-btif ( 1970): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5545): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): onServerStopped
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): release: No more listeners, de-initializing...
D/LGWifiP2pService(  847): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: No more listeners, de-initializing...
,D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5545): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService(  847): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5545): Service requests cleared successfully
,I/jxcore-log( 5545): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 5545): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@188d3102 added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: t,rue
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782461.5545
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782461.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5545): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782461.5545, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): bind: Binding a new listener
I/bt-btif ( 1970): BTA_JvCreateRecordByUser
I/bt-btif ( 1970): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Waiting for incoming connections...
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782461.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: {"pi":"F8:95:C7:87:85:54","pn":"1454983782461.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454983782461.5545","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@adb8a550 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@adb8a550 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState add service
D/LGWifiP2pService(  847): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782461.5545, mode: WIFI
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  847): discovery change broadcast true
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
,I/jxcore-log( 5545): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 5545): 
I/io.jxcore.node.ConnectionHelper( 5545): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): shutdown
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: 1 listener(s) left
I/bt-btif ( 1970): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: NOT_STARTED
I/bt-btif ( 1970): BTA_JvRfcommStopServer
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): onServerStopped
I/wpa_supplicant( 2717): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5545): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): stop: Stopping services
D/LGWifiP2pService(  847): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: NOT_INITIALIZED
D/LGWifiP2pService(  847): remove client information from framework
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: No more listeners, de-initializing...
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5545): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: NOT_STARTED
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5545): Service requests cleared successfully
I/jxcore-log( 5545): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 5545): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5215b4e added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true,
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32,
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782504.5545
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782504.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): setConnectionTimeout: 15000
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782504.5545, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5545): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1970): BTA_JvCreateRecordByUser
I/bt-btif ( 1970): BTA_JvRfcommStartServer
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782504.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: {"pi":"F8:95:C7:87:85:54","pn":"1454983782504.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454983782504.5545","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4a0d50d4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@4a0d50d4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState add service
D/LGWifiP2pService(  847): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782504.5545, mode: WIFI
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 5545): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 5545): 
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 5545): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): shutdown
D/LGWifiP2pService(  847): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: 1 listener(s) left
I/bt-btif ( 1970): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: NOT_STARTED
I/bt-btif ( 1970): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopForRestart
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5545): stopProvideBluetoothMacAddressMode
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): stop: Stopping P2P device discovery...
I/wpa_supplicant( 2717): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDisco,veryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): release: No more listeners, de-initializing...
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): InactiveState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5545): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  847): remove client information from framework
I/jxcore-log( 5545): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 5545): 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local services cleared successfully
D/LGWifiP2pService(  847): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21bbde5a added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
D/LGWifiP2pService(  847): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnab,ledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5545): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782546.5545
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782546.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5545): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1970): BTA_JvCreateRecordByUser
I/bt-btif ( 1970): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782546.5545, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782546.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: {"pi":"F8:95:C7:87:85:54","pn":"1454983782546.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454983782546.5545","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9661aa48 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9661aa48 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  847): P2pEnabledState add service
D/LGWifiP2pService(  847): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782546.5545, mode: WIFI
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5545): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 5545): 
I/io.jxcore.node.ConnectionHelper( 5545): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): onServerStopped
I/bt-btif ( 1970): BTA_JvDeleteRecord
I/bt-btif ( 1970): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: 1 listener(s) left
D/LGWifiP2pService(  847): InactiveState{ when=-2ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: NOT_STARTED
D/LGWifiP2pService(  847): P2pEnabledState{ when=-2ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): p2p0: P2P: Reject scan trigger since one is already pending
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5545): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: STARTED
D/LGWifiP2pService(  847): discovery change broadcast true
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: false
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): InactiveState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5545): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  847): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local services cleared successfully
D/LGWifiP2pService(  847): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast false
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service request
I/jxcore-log( 5545): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 5545): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5545): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29498626 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782597.5545
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782597.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782597.5545, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): bind: Binding a new listener
W/BluetoothAdapter( 5545): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1970): BTA_JvCreateRecordByUser
I/bt-btif ( 1970): BTA_JvRfcommStartServer
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983782597.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: {"pi":"F8:95:C7:87:85:54","pn":"1454983782597.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454983782597.5545","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@68c8ac3c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@68c8ac3c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState add service
D/LGWifiP2pService(  847): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983782597.5545, mode: WIFI
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 5545): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 5545): 
D/LGWifiP2pService(  847): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5545): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
I/bt-btif ( 1970): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: 1 listener(s) left
I/bt-btif ( 1970): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5545): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): stop: Stopping P2P device discovery...
I/wpa_supplicant( 2717): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): release: No more listeners, de-initializing...
D/LGWifiP2pService(  847): remove client information from framework
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: No more listeners, de-initializing...
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local services cleared successfully
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5545): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5545): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5545): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 4,
,I/jxcore-log( 5545): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b7deb2 added. We now have 12 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDi,scoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983783215.5545
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983783215.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983783215.5545, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
W/BluetoothAdapter( 5545): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1970): BTA_JvCreateRecordByUser
I/bt-btif ( 1970): BTA_JvRfcommStartServer
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983783215.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: {"pi":"F8:95:C7:87:85:54","pn":"1454983783215.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454983783215.5545","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9f6fffd4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9f6fffd4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState add service
D/LGWifiP2pService(  847): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983783215.5545, mode: WIFI
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5545): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 5545): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5545): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 5545): 
I/io.jxcore.node.ConnectionHelper( 5545): stop
I/org.thalipr,oject.p2p.btconnectorlib.ConnectionManager( 5545): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5545): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): stop: Stopping services
I/bt-btif ( 1970): BTA_JvDeleteRecord
I/bt-btif ( 1970): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): stop: Stopping P2P device discovery...
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): release: No more listeners, de-initializing...
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local service added successfully
I/wpa_supplicant( 2717): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1804): Event [CTRL-EVENT-SCAN-STARTED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: STARTED
D/LGWifiP2pService(  847): discovery change broadcast true
D/LGWifiP2pService(  847): InactiveState{ when=-6ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast false
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service
D/LGWifiP2pService(  847): remove client information from framework
D/LGWifiP2pService(  847): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): InactiveState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5545): clear
D/LGWifiP2pService(  847): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5545): Service requests cleared successfully
I/jxcore-log( 5545): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 5545): 
I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 5545): 
,I/jxcore-log( 5545): # teardown
I/jxcore-log( 5545): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5545): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@344133fe added. We now have 13 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(801540348)( 1970): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17f64e32
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5545): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983783396.5545
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983783396.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): start: OK
I/io.jxcore.node.ConnectionHelper( 5545): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5545): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1970): BTA_JvCreateRecordByUser
I/bt-btif ( 1970): BTA_JvRfcommStartServer
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983783396.5545, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5545): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454983783396.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: {"pi":"F8:95:C7:87:85:54","pn":"1454983783396.5545","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454983783396.5545","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f8dd5140 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f8dd5140 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState add service
D/LGWifiP2pService(  847): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454983783396.5545, mode: WIFI
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  847): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5545): start: OK
D/BluetoothManagerService(  847): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5545): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 5545): 
I/io.jxcore.node.ConnectionHelper( 5545): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 5545): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceD,iscoverer( 5545): setState: RESTARTING
E/io.jxcore.node.ConnectionHelper( 5545): connect: Invalid Bluetooth address: foobar
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2717): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: RESTARTING
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5545): ok 78 Should not connect to a bad peer
I/jxcore-log( 5545): 
I/io.jxcore.node.ConnectionHelper( 5545): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5545): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5545): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: 1 listener(s) left
I/bt-btif ( 1970): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5545): setState: NOT_STARTED
I/bt-btif ( 1970): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5545): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5545): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 5545): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5545): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5545): release: No more listeners, de-initializing...
D/LGWifiP2pService(  847): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5545): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5545): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5545): Local services cleared successfully
I/io.jxcore.node.ConnectionHelper( 5545): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  847): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5545): ok 79 Should, be able to call stopBroadcasting without error
I/jxcore-log( 5545): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): P2P device discovery stopped successfully
D/LGWifiP2pService(  847): InactiveState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  847): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5545): Service requests cleared successfully
,I/jxcore-log( 5545): # setup
I/jxcore-log( 5545): 
I/Netd    (  271): M: Get netlink event, ifname: p2p0 action: 4
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5545): start: Cannot start, because not initialized
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 295697461193; DSPS: 9780785; Offset : -2798654115
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 315698200144; DSPS: 10436169; Offset : -2798647821
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/charger_monitor(  487): init target 500000
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 335698888105; DSPS: 11091552; Offset : -2798662441
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  847): remove 3c16d4a4
D/LocationManagerService(  847): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  847): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  847): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  847): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  847): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  847): acquireWakeLockInternal: lock=950332939, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=847
,D/PowerManagerServiceEx(  847): releaseWakeLockInternal: lock=950332939 [*alarm*], flags=0x0
,W/art     ( 3597): Suspending all threads took: 5.598ms
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 355699694920; DSPS: 11746938; Offset : -2798648406
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  847): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 375700475590; DSPS: 12402324; Offset : -2798660880
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 395701236677; DSPS: 13057709; Offset : -2798663150
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 415702026044; DSPS: 13713095; Offset : -2798668698
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 435702790411; DSPS: 14368480; Offset : -2798665369
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 455703515352; DSPS: 15023863; Offset : -2798642801
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 475704166802; DSPS: 15679245; Offset : -2798662452
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 495704858409; DSPS: 16334628; Offset : -2798672775
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 515705518714; DSPS: 16990009; Offset : -2798653417
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 535706248081; DSPS: 17645393; Offset : -2798656472
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 555706997917; DSPS: 18300778; Offset : -2798669758
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 575707658482; DSPS: 18956160; Offset : -2798680294
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 595708423787; DSPS: 19611545; Offset : -2798678111
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 615709101228; DSPS: 20266927; Offset : -2798671874
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 635709770803; DSPS: 20922309; Offset : -2798673398
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 655710813556; DSPS: 21577703; Offset : -2798668321
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 675711493549; DSPS: 22233085; Offset : -2798660028
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 695712258385; DSPS: 22888470; Offset : -2798658026
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 715713039159; DSPS: 23543856; Offset : -2798670710
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/WifiController(  847): battery changed pluggedType: 2
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 735713769880; DSPS: 24199240; Offset : -2798672046
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 755714424247; DSPS: 24854621; Offset : -2798658990
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 775715175229; DSPS: 25510006; Offset : -2798671026
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 795715859805; DSPS: 26165388; Offset : -2798657862
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 815716516568; DSPS: 26820770; Offset : -2798672513
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 835717331613; DSPS: 27476156; Offset : -2798650690
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 855718090459; DSPS: 28131541; Offset : -2798654446
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 875718752222; DSPS: 28786923; Offset : -2798664251
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 895719572058; DSPS: 29442310; Offset : -2798668416
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 915720539655; DSPS: 30097701; Offset : -2798646942
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 935721208346; DSPS: 30753083; Offset : -2798649665
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  847): acquireWakeLockInternal: lock=950332939, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=847
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{50c8bb0 type 2 when 951794 com.android.bluetooth} when 951794
I/ActivityManager(  847): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8119 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,W/bt-smp  ( 1970): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1970): Plain text(LSB ~ MSB) = 5c 12 4c 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1970): Encrypted text(LSB ~ MSB) = bd 49 7f c1 6b 0b b9 e4 57 18 18 74 5c ce 28 2e 
,W/bt-btm  ( 1970): Stopping oneshot timer
,I/DigitalAppWidgetProvider( 8119): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8119): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@608c082
I/ActivityManager(  847): Killing 7637:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/PowerManagerServiceEx(  847): releaseWakeLockInternal: lock=950332939 [*alarm*], flags=0x0
,W/libprocessgroup(  847): failed to open /acct/uid_10011/pid_7637/cgroup.procs: No such file or directory
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 955721924640; DSPS: 31408467; Offset : -2798665688
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 975722688122; DSPS: 32063852; Offset : -2798665119
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  847): acquireWakeLockInternal: lock=950332939, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=847
,V/AlarmManager(  847): ELAPSED_WAKEUP set : Alarm{33074a29 type 2 when 990021 com.google.android.gms} when 990021
D/PowerManagerServiceEx(  847): releaseWakeLockInternal: lock=950332939 [*alarm*], flags=0x0
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 995723381396; DSPS: 32719235; Offset : -2798674114
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1015724115086; DSPS: 33374619; Offset : -2798672690
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1035724864973; DSPS: 34030003; Offset : -2798655173
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1055725524289; DSPS: 34685385; Offset : -2798667582
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1075726329906; DSPS: 35340771; Offset : -2798655214
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1095727084795; DSPS: 35996156; Offset : -2798662899
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1115727746245; DSPS: 36651538; Offset : -2798673227
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1135728521602; DSPS: 37306923; Offset : -2798660731
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1155729255397; DSPS: 37962307; Offset : -2798659592
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1175729919660; DSPS: 38617689; Offset : -2798666326
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1195730856371; DSPS: 39273080; Offset : -2798675555
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1215731617614; DSPS: 39928464; Offset : -2798646968
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  847): User[0] Flushing usage stats to disk
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1235732277085; DSPS: 40583846; Offset : -2798659196
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1255732970827; DSPS: 41239229; Offset : -2798666917
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1368): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1368): called onTimeUpdated()
I/[SystemUI]Clock( 1368): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
I/[SystemUI]DateView( 1368): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1368): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1368): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1368): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1368): On Skip Timer : true
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1368): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1368): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1368): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1970): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1368): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  847): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  847): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  847): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  847): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  847): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  847): tsOffsetIs: Apps: 1275733743789; DSPS: 41894614; Offset : -2798657232
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 8197): 
D/AndroidRuntime( 8197): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8197): CheckJNI is OFF
D/AndroidRuntime( 8197): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  847): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  847): Killing 5545:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  847): WIN DEATH: Window{2e99a541 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  847): Skipping PackageSetting{231d062 com.example.hello/10317} due to missing metadata
D/InputDispatcher(  847): Focus left window: Window{2e99a541 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  847): Window went away: Window{2e99a541 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  847):   Force finishing activity ActivityRecord{31aef044 u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  847): Display changed displayId=0
D/DSDPConnection( 1747): Display #0 changed.
W/ActivityManager(  847): Spurious death for ProcessRecord{376941ae 5545:com.test.thalitest/u0a316}, curProc for 5545: null
I/ActivityManager(  847): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
D/KeyguardModel( 1368): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  847): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1734): Ignoring removeGeofence because network location is disabled.
W/System.err( 3597): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3597): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3597): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3597): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3597): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3597): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3597): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3597): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3597): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3597): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3597): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3597): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 5587): Explicit concurrent mark sweep GC freed 14259(802KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/17MB, paused 911us total 123.882ms
I/ActivityManager(  847): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8230 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     ( 1942): Explicit concurrent mark sweep GC freed 22090(1280KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 1.271ms total 128.694ms
I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/art     (  303): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 23.781ms
I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
I/Activity( 1878): Activity.onPostResume() called 
I/art     (  303): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 21.330ms
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.799ms
D/KeyguardModel( 1368): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1368): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
I/[SystemUI]QSlideListController( 1368): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1368): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1368): createShortcutInfo...
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
W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1368): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1368): createShortcutInfo...
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1cb9f889,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  847): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  847): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  847): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  847): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1cb9f889,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  847): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  847): Focus entered window: Window{36713c96 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/art     (  847): Explicit concurrent mark sweep GC freed 80543(4MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 23MB/35MB, paused 4.789ms total 247.019ms
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1368): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1368): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1368): handleShortcutListChanged...
I/art     (  847): WaitForGcToComplete blocked for 75.668ms for cause Explicit
W/ResourcesManager( 8230): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8230): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8230): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/administrator(  847): Handling package changes for user 0
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1368): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1368): createShortcutInfo...
D/KeyguardModel( 1368): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1368): createShortcutInfo...
W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
D/KeyguardModel( 1368): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1368): createShortcutInfo...
I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1368): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1368): createShortcutInfo...
W/ResourceType( 1368): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1368): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/InputMethodManagerService(  847): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
D/KeyguardModel( 1368): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1368): createShortcutInfo...
W/InputMethodManagerService(  847): Got RemoteException sending setActive(false) notification to pid 5545 uid 10316
D/KeyguardModel( 1368): handleShortcutListChanged...
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  847): Timeline: Activity_windows_visible id: ActivityRecord{ff0ebab u0 com.lge.launcher2/.Launcher t221} time:1294184
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/LGEmail ( 8230): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
D/LGEmail ( 8230): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1585): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/NotificationService(  847): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  847): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  847): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1368): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/TaskPersister(  847): removeObsoleteFile: deleting file=222_task.xml
D/PhoneStatusBar( 1368): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1368): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1368):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1368): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1878): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
I/art     (  847): Explicit concurrent mark sweep GC freed 9600(552KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.459ms total 353.519ms
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
D/AndroidRuntime( 8197): Shutting down VM
I/PackageChangeReceiver( 8230): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  847): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8257 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  847): Killing 7657:com.android.gallery3d/u0a23 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  847): failed to open /acct/uid_10023/pid_7657/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/AppUp4:AppBoxCP( 8257): onCreate
W/AppUp4:DB( 8257):  [AppBoxDatabaseHelper] construct
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppUp4:DB( 8257):  setFingerPrint start
I/AppUp4:DB( 8257):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8257):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8257):  SDK version = 0
I/AppUp4:DB( 8257):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8257): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 8257): added Exclude : com.test.thalitest
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  847): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8274 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  847): Killing 7597:com.google.android.talk/u0a61 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  847): failed to open /acct/uid_10061/pid_7597/cgroup.procs: No such file or directory
E/SharedPreferencesImpl( 1878): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
I/Timeline( 1878): Timeline: Activity_idle id: android.os.BinderProxy@3733763e time:1294850
I/art     ( 1878): Explicit concurrent mark sweep GC freed 28025(1521KB) AllocSpace objects, 19(2MB) LOS objects, 40% free, 15MB/25MB, paused 1.061ms total 51.677ms

```
