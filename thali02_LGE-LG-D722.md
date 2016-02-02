#### Test 579720943a29850_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
W/libprocessgroup(  839): failed to open /acct/uid_10009/pid_5176/cgroup.procs: No such file or directory
W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_4160/cgroup.procs: No such file or directory
--------- beginning of main
D/NativeLibraryUtils( 5343): Install completed successfully. count=14 extracted=0
I/ActivityManager(  839): Killing 5196:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_5196/cgroup.procs: No such file or directory
I/ActivityManager(  839): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5413 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1944): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 1944): UpdateCorporaTask done [took 160 ms] updated apps [took 160 ms] 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/AndroidRuntime( 5410): 
D/AndroidRuntime( 5410): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5410): CheckJNI is OFF
D/Finsky  ( 5413): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/Finsky  ( 5413): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
D/AndroidRuntime( 5410): Calling main entry com.android.commands.am.Am
I/ActivityManager(  839): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/Settings( 5413): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5413): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5413): com.android.vending: cancel(-1050172287) by com.android.vending
D/ActivityManager(  839): setTaskToReturnTo : TaskRecord{2976413e #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  839): setTaskToReturnTo : TaskRecord{2976413e #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  839): AppWindowTokenEx init.. 
D/ContextHelper(  839): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  839): Focus left window: Window{a934b14 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5410): Shutting down VM
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@feb7859 on behalf of 5413
D/SplitWindow(  839): check instance of lgWin Window{3198a3d8 u0 Starting com.test.thalitest}
I/ActivityManager(  839): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5467 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/NotificationManager( 5413): com.android.vending: cancel(1003285959) by com.android.vending
I/HotwordDetector( 1944): Closing mic
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
I/MicrophoneInputStream( 1944): mic_close com.google.android.apps.gsa.speech.audio.u@1aabcfc0
V/AudioRecord( 1944): stop()
D/AudioRecord( 1944): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
D/Ads     ( 5413): Skipping gmscore version check
I/WindowStateAnimator(  839): Starting window displayed
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
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb384d000
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
I/SystemUI[Framework](  839): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1373): draw background and invalidate : color = 10000000
W/PhoneWindowManagerEx(  839): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  839): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  839): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2bf28e3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BarTransitions( 1373): draw background and invalidate : color = 16161616
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
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb384d000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioRecord( 1944): stop()
V/AudioRecord( 1944): stop()
V/AudioRecord( 1944): stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 17
V/AudioPolicyManager(  279): closeInput(17)
,V/AudioFlinger(  279): closeInput() 17
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): ThreadBase::exit
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): RecordThread 0xb384d000 exiting
V/AudioSystem( 3157): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): releasing 16 from 1944 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioSystem(  839): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1754): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1944): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1988): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2051): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  279): removeClient_l() pid 1944, calling pid 279
I/HotwordRecognitionRnr( 1944): Hotword detection finished
I/HotwordRecognitionRnr( 1944): Stopping hotword detection.
I/ActivityManager(  839): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=5490 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/Finsky  ( 5413): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5413): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 5413): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 5413): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5413): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  839): Killing 5213:com.android.gallery3d/u0a23 (adj 15): empty #11
D/ContextHelper( 5467): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
W/ResourcesManager( 5490): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5490): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  839): failed to open /acct/uid_10023/pid_5213/cgroup.procs: No such file or directory
I/MultiDex( 5490): VM with version 2.1.0 has multidex support
I/MultiDex( 5490): install
I/MultiDex( 5490): VM has multidex support, MultiDex support library is disabled.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/WebViewFactory( 5467): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5467): Time to load native libraries: 2 ms (timestamps 2394-2396)
I/LibraryLoader( 5467): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5467): Binding Chromium to main looper Looper (main, tid 1) {1ebd4a28}
I/LibraryLoader( 5467): Expected native library version number "",actual native library version number ""
I/chromium( 5467): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5467): Initializing chromium process, singleProcess=true
W/art     ( 5467): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5467): ApplicationContext is null in ApplicationStatus
W/chromium( 5467): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5467): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5467): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5467): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5467): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5467): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5467): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5467): Remote Branch: 
I/Adreno-EGL( 5467): Local Patches: 
I/Adreno-EGL( 5467): Reconstruct Branch: 
V/JNIHelp ( 5490): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
V/AudioPolicyService(  279): registerClient() client 0xb4027040, uid 10316
D/BluetoothManagerService(  839): Message: 20
D/BluetoothManagerService(  839): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29f8db20:true
D/BluetoothAdapterService(900784340)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1240a0ca
W/ActivityThread( 5490): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5490): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@201b2300: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5490): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5490): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5490): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5490): Reading stored module config
D/PackageBroadcastService( 5490): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 5490): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5490): Loading module APK com.google.android.play.games
D/NativeLibraryUtils( 5490): Install completed successfully. count=14 extracted=0
,W/art     ( 5467): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5467): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5467): CordovaWebView is running on device made by: LGE
,W/art     ( 5467): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5467): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 5467): Activity.onPostResume() called 
,D/OpenGLRenderer( 5467): Render dirty regions requested: true
,I/OpenGLRenderer( 5467): Initialized EGL, version 1.4
D/OpenGLRenderer( 5467): Enabling debug mode 0
D/Atlas   ( 5467): Validating map...
,D/SplitWindow(  839): check instance of lgWin Window{2fda5568 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5467): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/art     ( 5490): CheckpointMarkThreadRoots callback created = 0xb042d420
,D/InputDispatcher(  839): Focus entered window: Window{2fda5568 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/art     ( 5490): CheckpointMarkThreadRoots callback created = 0xb042d400
,W/art     ( 5490): Suspending all threads took: 5.755ms
,W/InputMethodManagerService(  839): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  839): Displayed com.test.thalitest/.MainActivity: +1s293ms
I/Timeline(  839): Timeline: Activity_windows_visible id: ActivityRecord{232edb9f u0 com.test.thalitest/.MainActivity t222} time:83153
I/Timeline( 5467): Timeline: Activity_idle id: android.os.BinderProxy@2153b717 time:83163
,D/ChimeraCfgMgr( 5490): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5490): Module APK com.google.android.play.games already loaded
,W/BindingManager( 5467): Cannot call determinedVisibility() - never saw a connection for the pid: 5467
,D/ChimeraCfgMgr( 5490): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5490): Submit a task: k
,I/art     ( 3890): Explicit concurrent mark sweep GC freed 3430(132KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 433us total 51.409ms
D/ChimeraCfgMgr( 5490): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 5490): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 5490): Processing package: com.test.thalitest
,D/GassUtils( 5490): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5490): Found info for package com.test.thalitest in db.
,I/Icing   ( 5490): Storage manager: low false usage 1.74MB avail 2.37GB capacity 4.06GB
,D/WearableService( 1735): callingUid 10006, callindPid: 1735
E/MDM     ( 1735): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/JsMessageQueue( 5467): Set native->JS mode to OnlineEventsBridgeMode
I/PeopleDatabaseHelper( 5490): cleanUpNonGplusAccounts done.
,I/art     ( 5490): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5490): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/BaseAppContext( 5490): Using Auth Proxy for data requests.
E/BaseAppContext( 5490): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5490): Using Auth Proxy for data requests.
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5490): Restart initialization of location
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  839): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5591 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,E/Icing   ( 5490): Array storage bad crc 3335449343 vs 958217509
,W/BaseAppContext( 5490): Using Auth Proxy for data requests.
E/Icing   ( 5490): Array storage bad crc 3893200270 vs 931206394
,W/BaseAppContext( 5490): Using Auth Proxy for data requests.
,W/BaseAppContext( 5490): Using Auth Proxy for data requests.
W/BaseAppContext( 5490): Using Auth Proxy for data requests.
,E/Icing   ( 5490): Array storage bad crc 54704369 vs 807274555
E/Icing   ( 5490): Trie mmap suffix failed
,W/BaseAppContext( 5490): Using Auth Proxy for data requests.
,W/IcingInternalCorpora( 5490): getNumBytesRead when not calculated.
,W/Icing   ( 5490): Docstore bad crc 0x30447924 vs 0xea3423a8
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
D/jxcore_app_log( 5467): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622895104
,I/chromium( 5467): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/art     ( 5467): CheckpointMarkThreadRoots callback created = 0x9a93d490
,I/art     ( 5467): CheckpointMarkThreadRoots callback created = 0x9a93d460
,E/Icing   ( 5490): Flash bitmap /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.lite.lexicon.prop.13 is dirty
,E/Icing   ( 5490): Init of /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.lite.lexicon.prop.13 failed
E/Icing   ( 5490): Open prop bitmap failed: /data/data/com.google.android.gms/files/AppDataSearch/main/cur/idx.lite.lexicon.prop.13
W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5591): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5591): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ChimeraCfgMgr( 5490): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5490): Module APK com.google.android.play.games already loaded
,W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  839): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5591): getAccountsCursor
,E/Gmail   ( 5591): Error finding the version of the Email provider.....
E/Gmail   ( 5591): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5591): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5591): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5591): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5591): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5591): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5591): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5591): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5591): We do not support migrating this version of the Email provider.
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  839): Killing 5232:com.android.contacts/u0a18 (adj 15): empty #11
I/Gmail   ( 5591): Observing account changes for notifications
,I/Icing   ( 5490): updateResources: need to parse f{com.google.android.gms}
,I/art     (  839): Explicit concurrent mark sweep GC freed 24535(1158KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 7.748ms total 246.071ms
,W/libprocessgroup(  839): failed to open /acct/uid_10018/pid_5232/cgroup.procs: No such file or directory
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@33c38c1e on behalf of 5490
I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5647 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 34.794ms
,W/InstanceID/Rpc( 5490): Found 10006
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 23.110ms
D/InitAlarmsService( 3741): Clearing and rescheduling alarms.
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 389us total 24.900ms
,D/CalendarProvider2( 5360): Scheduling check of next Alarm
,I/art     ( 5490): Background sticky concurrent mark sweep GC freed 13222(1027KB) AllocSpace objects, 11(176KB) LOS objects, 6% free, 13MB/14MB, paused 16.927ms total 111.110ms
D/CalendarProvider2( 5360): SCHEDULE_ALARM_REMOVE
I/Gmail   ( 5591): notifyAccountChanged
,I/Gmail   ( 5591): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5591): getAccountsCursor
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5591): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@1c27fcff on behalf of 5490
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@18569acc on behalf of 5490
I/Gmail   ( 5591): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5591): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PhoneMonitor( 5647): Register our PhoneStateListener
,I/Gmail   ( 5591): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PhoneMonitor( 5647): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 5647): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5647): [parse] Load xml
,V/TelephonyAutoProfiling( 5647): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
I/ActivityManager(  839): Killing 3741:com.android.calendar/u0a13 (adj 15): empty #11
V/TelephonyAutoProfiling( 5647): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5647): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  839): failed to open /acct/uid_10013/pid_3741/cgroup.procs: No such file or directory
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 5490): Checkin interval check for package: unspecified last checkin: 1454414797102 min interval config: 0 actual interval: 6737
,I/CheckinService( 5490): Disabling old GoogleServicesFramework version
,I/art     ( 5490): Background sticky concurrent mark sweep GC freed 7186(556KB) AllocSpace objects, 11(176KB) LOS objects, 5% free, 13MB/14MB, paused 13.716ms total 60.195ms
,I/Icing   ( 5490): Internal init done: storage state 0
I/NotificationManager( 5490): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Icing   ( 5490): 22 corpora need re-polling
,I/Icing   ( 5490): Post-init done
,I/CheckinService( 5490): Checking schedule, now: 1454414804010 next: 1454414827068
,I/CheckinService( 5490): active receiver: disabled
I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5676 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/Icing   ( 5490): Indexing 1612944C7007A012B1C904336C8580EC6DBD4F91 from com.google.android.music
,I/ActivityManager(  839): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=5694 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5676): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/jxcore-log( 5467): Initializing JXcore engine
,W/jxcore-log( 5467): JXcore engine is ready
I/CalendarProvider2( 5360): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5360): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  839): Killing 5251:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/MusicStore( 5694): Database version: 120
,W/Thread-666( 5614): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6327]" dev="sockfs" ino=6327 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-666( 5614): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-666( 5614): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5900]" dev="sockfs" ino=5900 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-666( 5614): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-666( 5614): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-666( 5614): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[24161]" dev="sockfs" ino=24161 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/libprocessgroup(  839): failed to open /acct/uid_10069/pid_5251/cgroup.procs: No such file or directory
,W/jxcore-log( 5467): Starting JXcore engine
,I/art     ( 3890): Explicit concurrent mark sweep GC freed 3074(121KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.203ms total 31.267ms
,I/Babel_SMS( 5676): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5676): MmsConfig.loadMmsSettings
I/Babel_SMS( 5676): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5676): MmsConfig.loadFromDatabase
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5694): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/Babel_SMS( 5676): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5676): MmsConfig.loadFromResources
E/Babel_SMS( 5676): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5676): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 5676): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5676): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5676): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5676): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5676): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5676): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5676): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5676): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5676): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5676): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5676): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5676): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5676): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5676): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5676): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5676): found sensor: Motion Accel, handle=46
,W/jxcore-log( 5467): Platform android
W/jxcore-log( 5467): 
W/jxcore-log( 5467): Process ARCH arm
W/jxcore-log( 5467): 
,W/Settings( 5676): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5676): startup - clean
I/Babel   ( 5676): deleted: false for 0
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5694): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5694): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/art     ( 5676): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,W/ResourcesManager( 5694): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5694): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 5676): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,V/JNIHelp ( 5694): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5694): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5694): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31ee6ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5694): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5694): GMSCore installation verified
W/art     ( 5676): Suspending all threads took: 14.084ms
I/ConfigStore( 5694): Config Database version: 1
,I/art     ( 5694): Background sticky concurrent mark sweep GC freed 22990(1142KB) AllocSpace objects, 4(64KB) LOS objects, 9% free, 10MB/11MB, paused 6.843ms total 59.049ms
,W/AudioCapabilities( 5676): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5676): Unsupported mime audio/adpcm
W/AudioCapabilities( 5676): Unsupported mime audio/g726
W/AudioCapabilities( 5676): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5676): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5676): Unsupported mime video/mjpg
W/VideoCapabilities( 5676): Unsupported mime video/theora
,W/AudioCapabilities( 5676): Unsupported mime audio/evrc
,W/AudioCapabilities( 5676): Unsupported mime audio/qcelp
W/VideoCapabilities( 5676): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5676): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5676): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5676): Unsupported mime audio/evrc
I/Icing   ( 5490): Indexing done 1612944C7007A012B1C904336C8580EC6DBD4F91
,I/Icing   ( 5490): Indexing 1F53EECCEBEB5877C2973BC154C132777EB605A6 from com.google.android.apps.books
W/ActivityManager(  839): Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{176e5bfe 5490:com.google.android.gms/u0a6} (pid=5490, uid=10006) that is not exported from uid 10046
W/VideoCapabilities( 5676): Unsupported mime video/mp4v-esdp
,E/Icing   ( 5490): Cursor call threw an exception: Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{176e5bfe 5490:com.google.android.gms/u0a6} (pid=5490, uid=10006) that is not exported from uid 10046
I/Icing   ( 5490): Indexing done 1F53EECCEBEB5877C2973BC154C132777EB605A6
E/Icing   ( 5490): Aborting indexing of corpus volumes__id
,I/Icing   ( 5490): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/MediaRouter( 5694): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/VideoCapabilities( 5676): Unsupported profile 4 for video/mp4v-es
I/NetworkMonitor( 5694): type=WIFI subType= reason=null isConnected=true
,W/VideoCapabilities( 5676): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5676): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5676): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5676): Unrecognized profile 2130706433 for video/avc
,V/AlarmManager(  839): RTC_WAKEUP set : Alarm{2fb37985 type 0 when 1454414805226 com.google.android.googlequicksearchbox} when 1454414805226
,I/NetworkMonitor( 5694): type=WIFI subType= reason=null isConnected=true
,I/vclib   ( 5676): onServiceConnected
,W/Babel   ( 5676): Attempted to change video mute state without an active call.
I/art     ( 5490): WaitForGcToComplete blocked for 26.546ms for cause HeapTrim
,I/ActivityManager(  839): Process com.google.android.apps.docs (pid 5292) has died
,I/GHttpClientFactory( 5694): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5694): Using platform SSLCertificateSocketFactory
,I/jxcore-log( 5467): JXcore Cordova bridge is ready!
I/jxcore-log( 5467): 
W/jxcore-log( 5467): JXcore engine is started
,I/NotificationManager( 5676): com.google.android.talk: cancel(10436) by com.google.android.talk
W/ResourcesManager( 5676): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5676): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  839): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5747 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AudioManager( 4954): getMode name:com.lge.qremote
,I/NotificationManager( 5694): com.google.android.music: cancel(1061) by com.google.android.music
,I/AudioManager( 4954): getMode name:com.lge.qremote
,D/Icing   ( 5490): Loaded CLD2 Version V2.0 - 20141016
,I/AudioManager( 4954): getMode name:com.lge.qremote
I/AudioManager( 4954): getMode name:com.lge.qremote
,I/Icing   ( 5490): Indexing B2F716F68058802BDD4E913C0921699984AB1871 from com.google.android.videos
V/JNIHelp ( 5676): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AudioManager( 4954): getMode name:com.lge.qremote
D/UEI.SmartControl( 5747): Quickset Services start...
I/UEI.SmartControl( 5747): Manufacture = LGE
,D/UEI.SmartControl( 5747): File observer start...
E/UEI.SmartControl( 5747): IR Port is disabled: false
D/UEI.SmartControl( 5747): Starting file observer...
D/UEI.SmartControl( 5747): Extracting JNI libs...
I/ActivityManager(  839): Start proc com.google.android.videos for content provider com.google.android.videos/.search.IcingContentProvider: pid=5764 uid=10099 gids={50099, 9997, 3003, 1028, 1015, 3002} abi=armeabi
D/UEI.SmartControl( 5747): --- this system supports 32-bit or 64-bit only
I/jxcore-log( 5467): Toggling radios to true
I/jxcore-log( 5467): 
,D/BluetoothAdapter( 5467): enable(): BT is already enabled..!
W/System  ( 5676): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5676): Installed default security provider GmsCore_OpenSSL
,D/WifiServiceImplEx(  839): setWifiEnabled: true pid=5467, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  839): setWifiEnabled: true pid=5467, uid=10316
,D/WifiServiceImplEx(  839): disconnect pid=5467, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  839): reconnect pid=5467, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5467): Radios toggled
I/jxcore-log( 5467): 
E/MDM     ( 1735): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/jxcore-log( 5467): My device name is: LGE-LG-D722
I/jxcore-log( 5467): 
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2779): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2779): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  839): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  839): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  839): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdsMonitor( 1806): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/DhcpStateMachine(  839): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  273): Clearing all IP addresses on wlan0
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1735): Read error: ssl=0xb045be00: I/O error during system call, Connection timed out
V/NativeCrypto( 1735): SSL shutdown failed: ssl=0xb045be00: I/O error during system call, Broken pipe
,D/ConnectivityService(  839): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 7
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): ValidatedState{ when=-4ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): DefaultState{ when=-12ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Forcing reevaluation
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  839): Default network via Wi-Fi disconnect. stop DSQN
,D/DSQN    (  839): disableDataServiceNotify
D/DSQN    (  839): stop dsqn bin
D/ConnectivityService(  839): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  839): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  839): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Disconnected - quitting
D/CSLegacyTypeTracker(  839): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  839): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/art     (  839): Explicit concurrent mark sweep GC freed 19218(893KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 14.177ms total 266.608ms
D/DhcpStateMachine(  839): StoppedState
,D/UEI.SmartControl( 5747): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5747): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5747): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  839): Process com.lge.bnr (pid 5044) has died
D/ConnectivityService(  839): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiHS20(  839): hidePasspointNotification off =false
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:46.144 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/QCNEJ   ( 1842): |CORE| No family connected
V/NetworkPolicy(  839): [LG_RESTRICTED] !!!isConnected  type  :1
,D/Tethering(  839): MasterInitialState.processMessage what=3
,E/WifiStateMachine(  839): Start Disconnecting Watchdog 1
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
D/LocationInitializer( 5490): Restart initialization of location
D/ConnectivityService(  839): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
I/wpa_supplicant( 2779): wlan0: CTRL-EVENT-SCAN-STARTED 
D/ConnectivityService(  839): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  839): Removing idletimer
D/TelephonyNetworkFactory-1( 1754): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1754):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiHS20(  839): hidePasspointNotification off =false
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:46.169 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/Tethering(  839): MasterInitialState.processMessage what=3
V/NetworkPolicy(  839): [LG_RESTRICTED] !!!isConnected  type  :1
D/LGWifiP2pService(  839): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  839): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  273): Clearing all IP addresses on wlan0
D/DhcpStateMachine(  839): StoppedState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
W/QCNEJ   ( 1842): |CORE| No family connected
I/QCNEJ   ( 1842): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
W/Settings(  839): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiHS20(  839): hidePasspointNotification off =false
E/ConnectivityService(  839): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
I/QCNEJ   ( 1842): |CORE| sendDefaultNwMsg: default = -1
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:46.182 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/UEI.SmartControl( 5747): --- Selecting new region: 2
I/UEI.SmartControl( 5747): -- Running on KitKat(19) and above! JNI will be used.
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNetworkAgent(  839): NetworkAgent: NetworkAgent channel lost
D/UEI.SmartControl( 5747): Platform has CIR...
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/UEI.SmartControl( 5747): NO CIR support, need to check package...
I/UEI.SmartControl( 5747): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5747): QS Service created
,D/WifiHS20(  839): hidePasspointNotification off =false
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:46.213 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WIFI    (  839): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  839):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/GCoreFlp( 1735): No location to return for getLastLocation()
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/FusedLocationProvider( 1735): location=null
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:46.218 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WifiServerServiceExt(  839): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateSCANNING
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,W/ResourcesManager( 5764): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 4954): getMode name:com.lge.qremote
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
I/AudioManager( 4954): getMode name:com.lge.qremote
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
E/UEI.SmartControl( 5747): QS start get config
I/NotificationManager( 5676): com.google.android.talk: cancel(8) by com.google.android.talk
,D/UEI.SmartControl( 5747): Loading JNI Libs...
D/UEI.SmartControl( 5747):  configuring local db...
,I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5796 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
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
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawabl,e/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,I/AppUp4:AppBoxCP( 5796): onCreate
,W/AppUp4:DB( 5796):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5796):  setFingerPrint start
I/AppUp4:DB( 5796):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5796):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5796):  SDK version = 0
I/AppUp4:DB( 5796):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5796): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5796): onReceive
,I/AppUp4:CustModeStarterReceiver( 5796): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5796): Context : android.app.ReceiverRestrictedContext@2faebd1a
D/AppUp4:CustFacade( 5796): isCustomizationCompleted : false
,D/UEI.SmartControl( 5747):  ---- Has DB8: true
,D/UEI.SmartControl( 5747): QS start statue = true Error code = 0
D/UEI.SmartControl( 5747): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5747): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{1d93be1 type 2 when 88553 com.google.android.gms} when 88553
,D/UEI.SmartControl( 5747): IRRCDataComm has AudioManager!!!!.
,I/ActivityManager(  839): Process com.google.android.gms.unstable (pid 5343) has died
,D/AppUp4:CustFacade( 5796): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5796): begin check event
I/AppUp4:CustModeStarterReceiver( 5796): Event For Nothing, skip.
W/irrc_jni( 5747): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 5747): IrrcClient ++ 
D/irrcClient( 5747): getIrrcService ++ 
D/irrcClient( 5747): getIrrcService -- 
D/irrcClient( 5747): IrrcClient -- 
W/irrc_jni( 5747): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 5747): Services init done
I/UEI.SmartControl( 5747): Device manager: loading config....
D/UEI.SmartControl( 5747): Config is loaded...
,I/ActivityManager(  839): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5834 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/UEI.SmartControl( 5747): QS Service init finished
D/UEI.SmartControl( 5747):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5747): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5747): QS Service version name: 0.1.73
,D/UEI.SmartControl( 5747): QS Service version code: 1073
D/UEI.SmartControl( 5747): Service requested: Control
D/UEI.SmartControl( 5747): Internal service binding...
D/UEI.SmartControl( 5747): -----IControl: 11
,D/UEI.SmartControl( 5747): Caller: com.lge.qremote
D/UEI.SmartControl( 5747): ------------ IControl registerCallback...
I/UEI.SmartControl( 5747): Registering callback...
D/UEI.SmartControl( 5747): -----IControl: 19
D/UEI.SmartControl( 5747): Caller: com.lge.qremote
I/UEI.SmartControl( 5747): Registering Services Ready callback...
I/UEI.SmartControl( 5747): Notify client services are ready...
D/UEI.SmartControl( 5747): -----IControl: 8
,D/UEI.SmartControl( 5747): Caller: com.lge.qremote
I/ActivityManager(  839): Killing 5268:com.lge.eula/1000 (adj 15): empty #11
,W/ResourcesManager( 5834): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5834): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5834): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
I/Icing   ( 5490): Indexing done B2F716F68058802BDD4E913C0921699984AB1871
,I/Icing   ( 5490): Indexing FC5805F301A6400196925772B79FE617968B1409 from com.google.android.videos
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_5268/cgroup.procs: No such file or directory
I/ActivityManager(  839): Killing 5326:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10086/pid_5326/cgroup.procs: No such file or directory
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/AppConfig( 5834): Total System Memory = 906309632
I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
I/GalleryUtils( 5834): Application Heap = 96 MB
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2779): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/AppConfig( 5834): App Tier : NOT_DEF
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/SystemHelper( 5834): region [EU], country [EU], operator [OPEN], sub-operator []
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/PlayMovies( 5764): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 5764): 
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:47.342 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2779): wlan0: Associated with c0:ff:d4:d3:aa:48
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:47.357 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:47.387 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:47.389 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2779): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2779): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/administrator(  839): Handling package changes for user 0
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/WifiServiceExtension(  839): setVHTCapabilityType  : false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
,W/PlayMovies( 5764): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 5764): 
I/WifiServerServiceExt(  839): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  839): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,I/WifiServiceExtension(  839): setSecurityType  : 2
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:47.485 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:47.49 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
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
,I/Icing   ( 5490): Indexing done FC5805F301A6400196925772B79FE617968B1409
I/Icing   ( 5490): Indexing 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9 from com.google.android.gms
,D/ConnectivityService(  839): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  839): Got NetworkAgent Messenger
D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  839): NetworkAgent connected
D/PlayMovies( 5764): PersistentCache.cleanup:94 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/PlayMovies( 5764): 
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
E/WifiConfigStore(  839): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/PlayMovies( 5764): TransferService.onCreate:60 creating transfer service
D/PlayMovies( 5764): 
,W/AudioCapabilities( 5764): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5764): Unsupported mime audio/adpcm
E/WifiConfigStore(  839): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/AudioCapabilities( 5764): Unsupported mime audio/g726
I/Icing   ( 5490): Indexing done 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9
I/Icing   ( 5490): Indexing 261F31C44790DA98645222D6E4244392E5409193 from com.google.android.gms
W/AudioCapabilities( 5764): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5764): Unsupported mime audio/wma-voice
,I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 9
W/VideoCapabilities( 5764): Unsupported mime video/mjpg
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  273): Setting iface cfg
,E/WifiStateMachine(  839): Start Dhcp Watchdog 2
D/DhcpStateMachine(  839): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  839): WaitBeforeStartState
W/VideoCapabilities( 5764): Unsupported mime video/theora
I/Icing   ( 5490): Indexing done 261F31C44790DA98645222D6E4244392E5409193
I/Icing   ( 5490): Indexing AC7CA1348821615DDDE9D587591668A8B8E68A6F from com.google.android.googlequicksearchbox
,I/ActivityManager(  839): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5876 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,W/AudioCapabilities( 5764): Unsupported mime audio/evrc
W/AudioCapabilities( 5764): Unsupported mime audio/qcelp
W/VideoCapabilities( 5764): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5764): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5764): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5764): Unsupported mime audio/evrc
W/VideoCapabilities( 5764): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5764): Unsupported profile 4 for video/mp4v-es
E/WifiStateMachine(  839): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  839): Current State is mWaitBeforeStartState.
,D/LGWifiP2pService(  839): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@305e4691 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@305e4691 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  839): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  839): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  839): DHCP Start wake lock is acquired.
D/CommandListener(  273): Setting iface cfg
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  273): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  839): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  839): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  839): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  839): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  839): ignoring duplicate network state non-change
D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): CdmEngine::QueryStatus
I/NotificationService(  839): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  839): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:47.791 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  839): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  839): Adding iface wlan0 to network 101
I/BackupManagerService(  839): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:47.81 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
E/WifiStateMachine(  839): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = false, mWifiLevel = 0
E/ConnectivityService(  839): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  839): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:47.822 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  839): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  273): netlink response contains error (File exists)
D/ConnectivityService(  839): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  839): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  839): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  839): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkControl,ler.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
W/ResourcesManager( 5876): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/QCNEJ   ( 1842): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:47.858 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1842): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
,D/Nat464Xlat(  839): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  839): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839): rematching NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  839):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Connected
D/ConnectivityService(  839):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
I/[SystemUI]StatusBar.NetworkController( 1373): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  839):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  839):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  839): currentScore = 0, newScore = 20
D/ConnectivityService(  839):    accepting network in place of null
D/ConnectivityService(  839): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  839): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  839):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] Start DNSResolver start to wait
D/TelephonyNetworkFactory-1( 1754): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1754):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
E/ConnectivityService(  839): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  839): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/ResourcesManager( 5876): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5876): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
D/ConnectivityService(  839): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  839): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  839): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1842): |CORE| No family connected
I/QCNEJ   ( 1842): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  839): validation of new default Network = false
D/ConnectivityService(  839): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  839): enableDataServiceNotify 
D/DSQN    (  839): start dsqn bin
I/QCNEJ   ( 1842): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] wait 500ms before dns check
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1373): Remote
W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
I/WVCdm   (  279): L3 Terminate.
,D/LocSvc_java(  839): onReceive
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateASSOCIATED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateFOUR_WAY_HANDSHAKE
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateGROUP_HANDSHAKE
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  839): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  839): setSupplicantStateCOMPLETED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,D/WifiHS20(  839): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  839): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Tethering(  839): MasterInitialState.processMessage what=3
V/BackupManagerService(  839): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager( 5876): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
V/BackupManagerService(  839): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@235977bd
D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
W/ResourcesManager( 5876): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,D/ConnectivityService(  839): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
I/DSQN    ( 5897): DSQN samuel.seo ver 141203
E/DSQN    ( 5897): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5897): created command queue thread
I/DSQN    ( 5897): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5897): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,V/NetworkPolicy(  839): [LG_RESTRICTED] checkMobilePolicy_type()
D/DhcpStateMachine(  839): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  839): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  839): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5901): version 5.5.6 starting
I/CheckinService( 5490): Checkin interval check for package: unspecified last checkin: 1454414797102 min interval config: 0 actual interval: 10876
,E/dhcpcd  ( 5901): get_duid: Read-only file system
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
D/Finsky  ( 5413): [640] SignatureUtils.faultInOtherSignatures: Will not allow first-party apps signed by test keys
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
D/Finsky  ( 5413): [640] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.videos
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/CheckinService( 5490): Checking schedule, now: 1454414808007 next: 1454414827068
I/CheckinService( 5490): active receiver: disabled
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
,I/GAv4-SVC( 5490): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 5591): Thread[GAThread,5,main]: No campaign data found.
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5764): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5764): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
I/dhcpcd  ( 5901): wlan0: rebinding lease of 192.168.1.134
I/ActivityManager(  839): Process com.google.android.gm (pid 5591) has died
,I/Icing   ( 5490): Indexing done AC7CA1348821615DDDE9D587591668A8B8E68A6F
,I/Icing   ( 5490): Indexing 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652 from com.google.android.googlequicksearchbox
I/SystemConfig( 5876): BUILD Country: EU
,I/SystemConfig( 5876): BUILD Operator: OPEN
I/Icing   ( 5490): Indexing done 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652
I/Icing   ( 5490): Indexing 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D from com.google.android.gm
I/ActivityManager(  839): Start proc com.google.android.gm for content provider com.google.android.gm/.provider.SearchQuery$Provider: pid=5914 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] DNSResolver start dns
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{ae414f3 type 2 when 90295 com.android.providers.calendar} when 90295
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out(  839): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5897): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5897): restart monitoring
D/LGDataListener(  273): argv[0]=dsqncommand
,D/LGDataListener(  273): argv[1]=wlan0
D/LGDataListener(  273): argv[2]=1
D/LGDataListener(  273): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5897): dsqn report finish
D/DSQN    (  839): DSQM DsqnNotification wlan0  1
D/DSQN    (  839): start to monitor internet connection
I/ActivityManager(  839): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5936 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 5647:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 12:06:48 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454414808520], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454414808499]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1806): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  839): Validated
D/ConnectivityService(  839): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  839):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  839): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  839): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  839): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  839):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1754): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1754):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_5647/cgroup.procs: No such file or directory
,W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/WifiDataContinuityService(  839): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
,I/WifiServerServiceExt(  839): set CMD_CAPTIVE_CHECK_COMPLETED
I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/SystemConfig( 5876): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5876): existFile = false
I/SystemConfig( 5876): canReadFile = false
I/SystemConfig( 5876): systemFeature RCS result false
,D/SystemConfig( 5876): refreshRcsSupport() :false
D/TelephonyIcons( 1373): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1373): updateLGTelephonySignalStrength : !hasService()
,I/LockScreenSettings( 5936): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/LocationProviderProxy(  839): applying state to connected service
D/LockScreenSettings( 5936): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5936): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5936): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5936): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5936): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/Gmail   ( 5914): getAccountsCursor
I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5961 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5914): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Icing   ( 5490): Indexing done 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D
I/ActivityManager(  839): Killing 5694:com.google.android.music:main/u0a81 (adj 15): empty #11
I/Icing   ( 5490): Indexing 59716A40DEE00805E4208F1709FD830CA906A723 from com.google.android.music
W/ResourcesManager( 5961): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  839): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  839): Killing 5360:com.android.providers.calendar/u0a14 (adj 15): empty #12
,E/lowmemorykiller(  241): Error opening /proc/5694/oom_score_adj; errno=2
,I/ActivityThread( 5490): Removing dead content provider:android.content.ContentProviderProxy@31768cdc
W/libprocessgroup(  839): failed to open /acct/uid_10081/pid_5694/cgroup.procs: No such file or directory
W/ActivityManager(  839): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/libprocessgroup(  839): failed to open /acct/uid_10014/pid_5360/cgroup.procs: No such file or directory
E/Icing   ( 5490): Cursor call threw an exception: null
E/Icing   ( 5490): Indexing content provider failed; will retry 3 times
W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Icing   ( 5490): Indexing done 59716A40DEE00805E4208F1709FD830CA906A723
E/Icing   ( 5490): Aborting indexing of corpus albums
I/Icing   ( 5490): Retrying indexing in 300000ms
I/Gmail   ( 5914): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Gmail   ( 5914): Error finding the version of the Email provider.....
E/Gmail   ( 5914): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5914): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5914): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5914): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5914): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5914): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5914): We do not support migrating this version of the Email provider.
I/Gmail   ( 5914): Observing account changes for notifications
W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Icing   ( 5490): Not indexing corpus from package com.android.chrome as it has never connected
E/Icing   ( 5490): Aborting indexing of corpus omnibox
I/Icing   ( 5490): Indexing 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3 from com.google.android.gms
I/Icing   ( 5490): Indexing done 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3
I/Icing   ( 5490): Indexing F200CD067697391E5BA8387C554D1EADCF480F28 from com.google.android.gms
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  839): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/Icing   ( 5490): Indexing done F200CD067697391E5BA8387C554D1EADCF480F28
D/GpsLocationProvider(  839): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/Icing   ( 5490): Indexing 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5 from com.google.android.music
,D/LocSvc_java(  839): onReceive
D/LocSvc_java(  839): got connectivity action
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GpsLocationProvider(  839): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LocSvc_java(  839): broadcast - no network connections
D/LocSvc_java(  839): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  839): Sending msg: 4 arg1:0 arg2:1
I/Netd    (  273): M: Get netlink event, ifname: wlan0 action: 6
D/LocSvc_java(  839): onReceive
D/LocSvc_java(  839): got connectivity action
D/LocSvc_java(  839): broadcast - no network connections
D/LocSvc_java(  839): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  839): Sending msg: 4 arg1:0 arg2:1
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocSvc_java(  839): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  839): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  839): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  839): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  839): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  839): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  839): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  839): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  839): identical MTU - not setting
D/Nat464Xlat(  839): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  839): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  839):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  839): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  839): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  839): enableDataServiceNotify 
D/DSQN    (  839): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1373): CM callback handler got msg 524295
D/DSQN    (  839): dsqn is running restart
I/ActivityManager(  839): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=5991 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DSQN    ( 5997): DSQN samuel.seo ver 141203
E/DSQN    ( 5997): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5997): created command queue thread
I/DSQN    ( 5997): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5997): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 383us total 33.870ms
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 23.282ms
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:49.288 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 310us total 31.317ms
,I/UpdateIcingCorporaServi( 1944): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1944): UpdateCorporaTask done [took 74 ms] updated apps [took 74 ms] 
,D/PackageBroadcastService( 5490): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 5490): Null package name or gms related package.  Ignoreing.
,I/AudioManager( 4954): getMode name:com.lge.qremote
I/art     (  839): Explicit concurrent mark sweep GC freed 77805(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.327ms total 183.579ms
,I/Gmail   ( 5914): notifyAccountChanged
I/Gmail   ( 5914): getAccountsCursor
I/MusicStore( 5991): Database version: 120
I/Gmail   ( 5914): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5914): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5914): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5914): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6032 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 5796:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/dhcpcd  ( 5901): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5901): wlan0: leased 192.168.1.134 for 86400 seconds
,W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_5796/cgroup.procs: No such file or directory
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5991): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/PhoneMonitor( 6032): Register our PhoneStateListener
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5991): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5991): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/art     ( 3890): Explicit concurrent mark sweep GC freed 2876(113KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 774us total 37.797ms
,V/SetupWizard( 6032): Connected to Gservices successfully
W/ResourcesManager( 5991): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5991): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/PhoneMonitor( 6032): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/Gmail   ( 5914): getAccountsCursor
V/TelephonyAutoProfiling( 6032): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6032): [parse] Load xml
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5490): Indexing done 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5
I/Icing   ( 5490): Indexing 98E736199A4D0A3DAA0BBDB44355DD80A1943A96 from com.google.android.googlequicksearchbox
,V/TelephonyAutoProfiling( 6032): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6032): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/JNIHelp ( 5991): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PhoneMonitor( 6032): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  839): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  839): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  839): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  839): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  839): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  839): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  839): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  839): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  839): RunningState
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
I/Icing   ( 5490): Indexing done 98E736199A4D0A3DAA0BBDB44355DD80A1943A96
I/Icing   ( 5490): Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5490): Restart initialization of location
,E/MDM     ( 1735): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 1735): propertyValue:false
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityThread( 5991): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5991): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5c6c573: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5991): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5991): GMSCore installation verified
I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ConfigStore( 5991): Config Database version: 1
W/GCoreFlp( 1735): No location to return for getLastLocation()
,W/FusedLocationProvider( 1735): location=null
I/DSQN    ( 5997): first global connection report this to start monitoring at DSQM.
E/MDM     ( 1735): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/DSQN    ( 5997): restart monitoring
D/LGDataListener(  273): argv[0]=dsqncommand
D/LGDataListener(  273): argv[1]=wlan0
D/LGDataListener(  273): argv[2]=1
D/LGDataListener(  273): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5997): dsqn report finish
D/DSQN    (  839): DSQM DsqnNotification wlan0  1
D/DSQN    (  839): start to monitor internet connection
D/LocationInitializer( 5490): Restart initialization of location
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5490): Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
I/Icing   ( 5490): Indexing 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4 from com.google.android.googlequicksearchbox
I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/MediaRouter( 5991): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 5991): type=WIFI subType= reason=null isConnected=true
,I/art     ( 1735): Explicit concurrent mark sweep GC freed 30488(1867KB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 13MB/22MB, paused 1.529ms total 174.401ms
I/NotificationManager( 1944): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  839): Killing 5834:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10023/pid_5834/cgroup.procs: No such file or directory
,I/NetworkMonitor( 5991): type=WIFI subType= reason=null isConnected=true
I/GCM     ( 1735): Ack for not saved message 45
,I/Icing   ( 5490): Indexing done 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4
I/Icing   ( 5490): Indexing BC9EFFA8FB4EBD74F2B7898FFA6492656D342420 from com.google.android.music
I/GHttpClientFactory( 5991): Using our fixed implementation of GMSCore's GoogleHttpClient
,W/GCoreFlp( 1735): No location to return for getLastLocation()
,W/FusedLocationProvider( 1735): location=null
I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 13:06:50.659 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/GoogleURLConnFactory( 5991): Using platform SSLCertificateSocketFactory
I/Icing   ( 5490): Indexing done BC9EFFA8FB4EBD74F2B7898FFA6492656D342420
,I/Icing   ( 5490): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
I/ActivityManager(  839): Killing 5764:com.google.android.videos/u0a99 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10099/pid_5764/cgroup.procs: No such file or directory
,I/NotificationManager( 5991): com.google.android.music: cancel(1061) by com.google.android.music
I/Icing   ( 5490): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Icing   ( 5490): Indexing B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839 from com.google.android.gms
I/Icing   ( 5490): Indexing done B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839
I/Icing   ( 5490): Indexing 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15 from com.google.android.googlequicksearchbox
D/ConnectivityService(  839): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  839): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6106 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/WifiInternetCheck(  839): Single check msg out of sync, ignoring.
,D/GpsLocationProvider(  839): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1373): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  839): onReceive
D/LocSvc_java(  839): got connectivity action
D/LocSvc_java(  839): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  839): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  839): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  839): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  839): ignore wifi update if we are not in OPENING or CLOSING
,I/NetworkMonitor( 5991): type=WIFI subType= reason=null isConnected=true
D/GpsLocationProvider(  839): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Icing   ( 5490): Indexing done 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15
,W/ResourcesManager( 6106): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Icing   ( 5490): updateResources: need to parse f{com.google.android.gms}
,D/CalendarApplication( 6106): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6106): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6106): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@7c91fc5, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2faebd1a, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2720a04b, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1ebd4a28, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@620f341, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@b6b90e6, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1ad6f627, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@35b0e0d4, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@38c8827d, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2ecfd572, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@9b2cdc3, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3a53640, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@195fc979, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@9c1d6be, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@bea831f, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@fc7766c, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@18a8435, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1240a0ca, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1cbe323b, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@4eb8d58, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@76c2eb1, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2d2fff96, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2153b717, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@25382704, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@25e404ed, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@17e47f22, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@152adb3, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@c92af70, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2c8902e9, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1e6f6b6e, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2d40720f, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2dcb529c, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3365e4a5, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2aaad07a, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2e9c202b, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3688fc88, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@e752621, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@38057a46, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1dba9407, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@5f55934, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3cdd035d, lg_preferences_recent_tim,ezones=com.android.calendar.adaptation.PreferenceKey$KeyData@380ef4d2, lg_
D/GeneralPreferenceUtils( 6106): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6106): [init]
,I/Config  ( 6106): LGCalendar ver.4.40.17
I/Config  ( 6106): start check model
I/Config  ( 6106): start check native_ca
I/Config  ( 6106): Config Operator=OPEN, Country=EU
D/Config  ( 6106): [setDefaultValuesToPref]
D/Config  ( 6106): [parseProfiles]
D/ProfilesParser( 6106): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6106): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6106): [updateProfiletoCountryInfo]
D/GeneralPreference( 6106): [checkAndMigrateOldPreference]
D/AlertReceiver( 6106): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6106): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6106): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/Icing   ( 5490): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/AlertUtils( 6106): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6106): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6106): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/AlertUtils( 6106): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6106): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6106): onHandleIntent
,D/HolidayDataLoader( 6106): readJsonAsset : holiday.json
D/AlertService( 6106): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6106): [updateWidgets] 
D/MonthWidgetProvider( 6106): [onReceive]
D/CalendarWidgetProvider( 6106): [onReceive]
D/CalendarWidgetProvider( 6106): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6106): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6106): [onReceive]
,D/CalendarWidgetProvider( 6106): [onReceive]
D/CalendarWidgetProvider( 6106): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6106): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6106): onHandleIntent:holiday data empty
,I/ActivityManager(  839): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6133 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  839): Killing 5676:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_5676/cgroup.procs: No such file or directory
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{20b392e1 type 0 when 1454414811716 com.android.vending} when 1454414811716
,D/Finsky  ( 5413): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
W/ResourcesManager( 6133): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6133): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6133): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6133): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6133): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5747): Internal timer expired: 1
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
I/IndexDatabaseHelper( 6133): Using schema version: 115
,I/IndexDatabaseHelper( 6133): Index is fine
D/libc-netbsd( 5413): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5413): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5413): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5413): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
,I/System.out( 5413): propertyValue:false
D/libc-netbsd( 5413): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5413): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/WiFiOffLoadBroadcast( 6133): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
,D/WiFiOffLoadBroadcast( 6133): MCCMNC not supported: null
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
,I/System.out(  839): propertyValue:false
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  839): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  839): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  273): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out(  839): propertyValue:false
D/libc-netbsd( 5413): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5413): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/WifiInternetCheck(  839): isHttpConnectionAvailable - We got a valid response : 204
,I/Icing   ( 5490): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 5490): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  839): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6163 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  839): Explicit concurrent mark sweep GC freed 25898(1291KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.059ms total 148.026ms
,I/ActivityManager(  839): Process com.google.android.apps.plus (pid 5961) has died
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  839): android: cancelAsUser(2) by android
,I/PCSuite ( 6163): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6163): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6163): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/qtaguid ( 5413): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5413): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5413): untagSocket(41) failed with errno -22
,D/Finsky  ( 5413): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6187 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,W/ResourcesManager( 6187): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  839): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6205 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6205): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6205): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6205): VM with version 2.1.0 has multidex support
I/MultiDex( 6205): install
I/MultiDex( 6205): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6205): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 5413): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5413): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5413): untagSocket(41) failed with errno -22
I/Babel_SMS( 6187): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6187): MmsConfig.loadMmsSettings
I/Babel_SMS( 6187): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6187): MmsConfig.loadFromDatabase
,W/ActivityThread( 6205): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6205): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35984c2a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6205): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6205): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6205): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6205): Reading stored module config
,D/ChimeraCfgMgr( 6205): Loading module com.google.android.gms.car from APK com.google.android.gms
,E/Babel_SMS( 6187): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6187): MmsConfig.loadFromResources
E/Babel_SMS( 6187): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6187): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/art     ( 6187): CheckpointMarkThreadRoots callback created = 0xb042d880
,D/SensorManager( 6187): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6187): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6187): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6187): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6187): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6187): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6187): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 6187): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6187): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6187): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6187): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6187): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6187): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6187): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6187): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6187): found sensor: Motion Accel, handle=46
I/art     ( 6187): CheckpointMarkThreadRoots callback created = 0xb042d870
,W/Settings( 6187): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6187): startup - clean
,I/Babel   ( 6187): deleted: false for 0
,D/NativeLibraryUtils( 6205): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6205): Connecting to CarCallService...
V/WiFiOffLoadBroadcast( 6133): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6133): MCCMNC not supported: null
I/PCSuite ( 6163): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6163): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6163): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6187): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6187): Unsupported mime audio/adpcm
W/AudioCapabilities( 6187): Unsupported mime audio/g726
V/WiFiOffLoadBroadcast( 6133): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6187): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6187): Unsupported mime audio/wma-voice
D/WiFiOffLoadBroadcast( 6133): MCCMNC not supported: null
W/VideoCapabilities( 6187): Unsupported mime video/mjpg
,W/VideoCapabilities( 6187): Unsupported mime video/theora
I/PCSuite ( 6163): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6163): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6163): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/art     ( 6205): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6205): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
V/WiFiOffLoadBroadcast( 6133): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6133): MCCMNC not supported: null
I/PCSuite ( 6163): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6163): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6163): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6133): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6133): MCCMNC not supported: null
,I/art     ( 5413): CheckpointMarkThreadRoots callback created = 0xb042d950
,I/AudioManager( 4954): getMode name:com.lge.qremote
W/AudioCapabilities( 6187): Unsupported mime audio/evrc
W/AudioCapabilities( 6187): Unsupported mime audio/qcelp
W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
,I/art     ( 5413): CheckpointMarkThreadRoots callback created = 0xb042d920
D/CAR.SERVICE( 6205): com.google.android.projection.gearhead isn't installed.
,W/AudioCapabilities( 6187): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6187): Unsupported mime audio/qcelp
W/AudioCapabilities( 6187): Unsupported mime audio/evrc
,D/CAR.TEL.Service( 6205): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6205): Creating a new PhoneAdapter instance
,W/ActivityManager(  839): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6205): setListener: com.google.android.gms.car.dn@191c4901
W/ActivityManager(  839): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6205): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6205): Starting CarCallService with initial phone null
W/VideoCapabilities( 6187): Unsupported mime video/mp4v-esdp
,I/NotificationManager( 6205): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/VideoCapabilities( 6187): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6187): Unrecognized profile 2130706433 for video/avc
,D/CAR.SERVICE( 6205): Package validated; name: com.android.vending
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  839): tsOffsetIs: Apps: 95694848457; DSPS: 3233764; Offset : -3002674939
I/ActivityManager(  839): Process com.google.android.music:main (pid 5991) has died
I/vclib   ( 6187): onServiceConnected
W/Babel   ( 6187): Attempted to change video mute state without an active call.
,I/NotificationManager( 5413): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5413): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,W/art     ( 5413): Suspending all threads took: 5.784ms
,I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6248 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/NotificationManager( 6187): com.google.android.talk: cancel(8) by com.google.android.talk
,I/NotificationManager( 6187): com.google.android.talk: cancel(10436) by com.google.android.talk
W/ResourcesManager( 6187): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6187): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GAV2    ( 5914): Thread[GAThread,5,main]: No campaign data found.
V/JNIHelp ( 6187): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 6248): onCreate
,W/AppUp4:DB( 6248):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6248):  setFingerPrint start
I/AppUp4:DB( 6248):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6248):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6248):  SDK version = 0
I/AppUp4:DB( 6248):  beforefinger == newfinger no write in DB
W/System  ( 6187): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6187): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  839): Process com.google.android.gm (pid 5914) has died
,D/AppUp4:AppBoxApplication( 6248): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6248): onReceive
I/AppUp4:CustModeStarterReceiver( 6248): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6248): Context : android.app.ReceiverRestrictedContext@2faebd1a
D/AppUp4:CustFacade( 6248): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6248): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6248): begin check event
I/AppUp4:CustModeStarterReceiver( 6248): Event For Nothing, skip.
I/ActivityManager(  839): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6273 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6273): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6273): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6273): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
I/AppConfig( 6273): Total System Memory = 906309632
,I/GalleryUtils( 6273): Application Heap = 96 MB
I/AppConfig( 6273): App Tier : NOT_DEF
,D/SystemHelper( 6273): region [EU], country [EU], operator [OPEN], sub-operator []
D/LockScreenSettings( 5936): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5936): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 5936): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5936): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5936): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6292 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/qtaguid ( 5413): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5413): Untagging socket 41 failed errno=-22
,W/NetworkManagementSocketTagger( 5413): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6292): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5413): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5413): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5413): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5413): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  839): RTC_WAKEUP set : Alarm{9980c9e type 0 when 1454414814922 com.android.vending} when 1454414814922
,D/DeviceConnectionService( 1735): client connected with version: 8296000
,D/Finsky  ( 5413): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5413): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  839): Killing 6133:com.android.settings/1000 (adj 15): empty #11
I/ActivityManager(  839): Killing 6032:com.google.android.setupwizard/u0a38 (adj 15): empty #12
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_6133/cgroup.procs: No such file or directory
,W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_6032/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 1944): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 5490): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 1944): UpdateCorporaTask done [took 49 ms] updated apps [took 49 ms] 
,I/ActivityManager(  839): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6323 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PackageBroadcastService( 5490): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5490): updateResources: need to parse f{com.google.android.gms}
,I/jxcore-log( 5467): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5467): 
I/ActivityManager(  839): Killing 5747:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 4954): android.os.DeadObjectException
,W/System.err( 4954): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4954): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4954): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4954): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4954): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4954): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4954): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4954): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4954): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4954): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4954): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4954): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4954): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4954): android.os.DeadObjectException
W/System.err( 4954): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4954): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4954): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4954): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4954): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4954): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4954): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4954): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4954): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4954): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4954): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4954): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4954): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,W/libprocessgroup(  839): failed to open /acct/uid_10089/pid_5747/cgroup.procs: No such file or directory
W/ActivityManager(  839): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  839): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6348 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6323): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6323): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6323): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6323): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6323): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 25.258ms
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 25.053ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.960ms
,I/IndexDatabaseHelper( 6323): Using schema version: 115
,I/IndexDatabaseHelper( 6323): Index is fine
D/UEI.SmartControl( 6348): Quickset Services start...
I/UEI.SmartControl( 6348): Manufacture = LGE
D/UEI.SmartControl( 6348): File observer start...
E/UEI.SmartControl( 6348): IR Port is disabled: false
D/UEI.SmartControl( 6348): Starting file observer...
D/UEI.SmartControl( 6348): Extracting JNI libs...
D/UEI.SmartControl( 6348): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6348): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6348): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6348): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6348): --- Selecting new region: 2
,I/UEI.SmartControl( 6348): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6348): Platform has CIR...
D/UEI.SmartControl( 6348): NO CIR support, need to check package...
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/UEI.SmartControl( 6348): Model: LG-D722 uses JNI
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 6348): QS Service created
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{4fc7a6f type 0 when 1454414815956 com.google.android.googlequicksearchbox} when 1454414815956
,E/UEI.SmartControl( 6348): QS start get config
D/WiFiOffLoadBroadcast( 6323): Not supported operator for automatic switch
,V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/UEI.SmartControl( 6348): Loading JNI Libs...
,D/UEI.SmartControl( 6348):  configuring local db...
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
I/PCSuite ( 6163): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6163): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6323): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6323): MCCMNC not supported: null
,I/PCSuite ( 6163): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6163): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6381 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  839): Killing 6248:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/UEI.SmartControl( 6348):  ---- Has DB8: true
D/UEI.SmartControl( 6348): QS start statue = true Error code = 0
D/UEI.SmartControl( 6348): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 6348): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6348): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6348): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 6348): IrrcClient ++ 
D/irrcClient( 6348): getIrrcService ++ 
D/irrcClient( 6348): getIrrcService -- 
D/irrcClient( 6348): IrrcClient -- 
W/irrc_jni( 6348): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6348): Services init done
I/UEI.SmartControl( 6348): Device manager: loading config....
D/UEI.SmartControl( 6348): Config is loaded...
,D/UEI.SmartControl( 6348):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6348): Notify AllClients services are ready: 0
D/AlertService( 6106): Beginning updateAlertNotification
W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_6248/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6348): QS Service init finished
D/UEI.SmartControl( 6348): QS Service version name: 0.1.73
D/UEI.SmartControl( 6348): QS Service version code: 1073
D/UEI.SmartControl( 6348): Service requested: Control
I/ActivityManager(  839): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6401 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PhoneMonitor( 6381): Register our PhoneStateListener
,D/UEI.SmartControl( 6348): Internal service binding...
D/UEI.SmartControl( 6348): -----IControl: 11
,D/UEI.SmartControl( 6348): Caller: com.lge.qremote
D/UEI.SmartControl( 6348): ------------ IControl registerCallback...
I/UEI.SmartControl( 6348): Registering callback...
D/UEI.SmartControl( 6348): -----IControl: 19
D/UEI.SmartControl( 6348): Caller: com.lge.qremote
I/UEI.SmartControl( 6348): Registering Services Ready callback...
I/UEI.SmartControl( 6348): Notify client services are ready...
D/UEI.SmartControl( 6348): -----IControl: 8
D/UEI.SmartControl( 6348): Caller: com.lge.qremote
,I/ActivityManager(  839): Process com.android.contacts (pid 5876) has died
,I/ActivityManager(  839): Killing 6273:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/ResourcesManager( 6401): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PhoneMonitor( 6381): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6381): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6381): [parse] Load xml
V/TelephonyAutoProfiling( 6381): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6381): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6381): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/CalendarProvider2( 6401): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2847302f
,I/jxcore-log( 5467): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5467): 
,W/libprocessgroup(  839): failed to open /acct/uid_10023/pid_6273/cgroup.procs: No such file or directory
D/CalendarProvider2( 6401): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6401): Created com.android.providers.calendar.CalendarAlarmManager@1ebd4a28(com.android.providers.calendar.CalendarProvider2@2847302f)
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 5490): Checkin interval check for package: unspecified last checkin: 1454414797102 min interval config: 0 actual interval: 19560
D/CalendarProviderBroadcastReceiver( 6401): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6401): [IntentService] WakeLock acquire, start IntentSerivce
,D/CalendarProvider2( 6401): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6401): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6401): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  839): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6427 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 5490): Checking schedule, now: 1454414816740 next: 1454414827068
I/CheckinService( 5490): active receiver: disabled
D/AlertService( 6106): No fired or scheduled alerts
,I/jxcore-log( 5467): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5467): 
,I/NotificationManager( 6106): com.android.calendar: cancel(0) by com.android.calendar
I/jxcore-log( 5467): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5467): 
I/NotificationManager( 6106): com.android.calendar: cancel(1) by com.android.calendar
,I/NotificationManager( 6106): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(4) by com.android.calendar
,I/Icing   ( 5490): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/NotificationManager( 6106): com.android.calendar: cancel(5) by com.android.calendar
,D/CalendarProvider2( 6401): [IntentService] Release Lock
,D/CalendarProvider2( 6401): CalendarProviderIntentService.onDestroy()
I/NotificationManager( 6106): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(7) by com.android.calendar
,I/NotificationManager( 6106): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6106): com.android.calendar: cancel(20) by com.android.calendar
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
I/jxcore-log( 5467): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5467): 
,I/Icing   ( 5490): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  839): Killing 5936:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/AlertService( 6106): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/jxcore-log( 5467): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5467): 
,I/jxcore-log( 5467): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5467): 
,I/jxcore-log( 5467): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5467): 
I/art     (  839): Explicit concurrent mark sweep GC freed 19473(899KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.352ms total 192.336ms
,I/ActivityManager(  839): Killing 6292:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10069/pid_5936/cgroup.procs: No such file or directory
,W/libprocessgroup(  839): failed to open /acct/uid_10086/pid_6292/cgroup.procs: No such file or directory
W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/AlarmScheduler( 6106): No events found starting within 1 week.
,I/Gmail   ( 6427): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6427): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  839): Killing 6106:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10013/pid_6106/cgroup.procs: No such file or directory
W/ActivityManager(  839): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 6427): Observing account changes for notifications
W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 6427): Error finding the version of the Email provider.....
E/Gmail   ( 6427): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6427): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6427): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6427): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6427): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6427): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6427): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6427): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 6427): We do not support migrating this version of the Email provider.
I/Gmail   ( 6427): getAccountsCursor
I/ActivityManager(  839): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6470 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  839): Killing 6323:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_6323/cgroup.procs: No such file or directory
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicStore( 6470): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6470): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Gmail   ( 6427): notifyAccountChanged
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Gmail   ( 6427): getAccountsCursor
,I/Gmail   ( 6427): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6427): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6427): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6427): calculateUnknownSyncRationalesAndPurgeInBackground: running
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6470): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6470): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Gmail   ( 6427): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6470): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6470): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6470): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6470): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6470): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31ee6ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6470): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6470): GMSCore installation verified
I/ConfigStore( 6470): Config Database version: 1
,I/MediaRouter( 6470): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6470): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6470): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6470): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6513 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6470): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6470): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  839): Killing 6348:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 4954): android.os.DeadObjectException
,W/System.err( 4954): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4954): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4954): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4954): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4954): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4954): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4954): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4954): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4954): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4954): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4954): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4954): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4954): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4954): android.os.DeadObjectException
W/System.err( 4954): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4954): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4954): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4954): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4954): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4954): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4954): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4954): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4954): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4954): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4954): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4954): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4954): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4954): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4954): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/ResourcesManager( 6513): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6513): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6513): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  839): failed to open /acct/uid_10089/pid_6348/cgroup.procs: No such file or directory
,W/ActivityManager(  839): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/NotificationManager( 6470): com.google.android.music: cancel(1061) by com.google.android.music
I/ActivityManager(  839): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6540 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/LGEmail ( 6513): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/CAR.SERVICE( 6205): mConnectedToCar = false, abort
E/ActivityThread( 6205): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@124e29c9 that was originally bound here
E/ActivityThread( 6205): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@124e29c9 that was originally bound here
E/ActivityThread( 6205): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6205): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6205): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6205): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6205): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6205): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6205): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6205): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6205): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6205): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6205): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6205): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6205): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6205): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6205): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6205): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6205): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6205): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6205): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6205): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6205): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6205): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6205): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6205): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@b5d5ee8 that was originally bound here
E/ActivityThread( 6205): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@b5d5ee8 that was originally bound here
E/ActivityThread( 6205): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6205): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6205): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6205): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6205): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6205): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6205): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6205): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6205): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6205): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6205): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6205): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6205): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6205): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6205): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6205): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6205): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6205): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6205): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6205): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6205): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6205): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  839): Unbind failed: could not find connection for android.os.BinderProxy@2fa9f89c
W/ProcessCpuTracker(  839): Skipping unknown process pid 6533
W/ProcessCpuTracker(  839): Skipping unknown process pid 6534
W/ProcessCpuTracker(  839): Skipping unknown process pid 6536
W/ProcessCpuTracker(  839): Skipping unknown process pid 6537
,D/LGEmail ( 6513): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/UEI.SmartControl( 6540): Quickset Services start...
,I/UEI.SmartControl( 6540): Manufacture = LGE
D/UEI.SmartControl( 6540): File observer start...
E/UEI.SmartControl( 6540): IR Port is disabled: false
D/UEI.SmartControl( 6540): Starting file observer...
D/UEI.SmartControl( 6540): Extracting JNI libs...
D/UEI.SmartControl( 6540): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6540): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6540): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 6540): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6540): --- Selecting new region: 2
I/UEI.SmartControl( 6540): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6540): Platform has CIR...
D/UEI.SmartControl( 6540): NO CIR support, need to check package...
I/UEI.SmartControl( 6540): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6540): QS Service created
E/UEI.SmartControl( 6540): QS start get config
,D/UEI.SmartControl( 6540): Loading JNI Libs...
D/UEI.SmartControl( 6540):  configuring local db...
,I/ActivityManager(  839): Killing 6187:com.google.android.talk/u0a61 (adj 15): empty #11
D/UEI.SmartControl( 6540):  ---- Has DB8: true
,W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_6187/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6540): QS start statue = true Error code = 0
D/UEI.SmartControl( 6540): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6540): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6540): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6540): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6540): IrrcClient ++ 
D/irrcClient( 6540): getIrrcService ++ 
D/irrcClient( 6540): getIrrcService -- 
D/irrcClient( 6540): IrrcClient -- 
W/irrc_jni( 6540): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6540): Services init done
,I/UEI.SmartControl( 6540): Device manager: loading config....
D/UEI.SmartControl( 6540): QS Service init finished
D/UEI.SmartControl( 6540): QS Service version name: 0.1.73
D/UEI.SmartControl( 6540): QS Service version code: 1073
D/UEI.SmartControl( 6540): Config is loaded...
D/UEI.SmartControl( 6540): Service requested: Control
I/ActivityManager(  839): Killing 6163:com.lge.sync/1000 (adj 15): empty #11
,D/UEI.SmartControl( 6540): -----IControl: 11
D/UEI.SmartControl( 6540): Caller: com.lge.qremote
D/UEI.SmartControl( 6540): ------------ IControl registerCallback...
I/UEI.SmartControl( 6540): Registering callback...
D/UEI.SmartControl( 6540): -----IControl: 19
D/UEI.SmartControl( 6540): Caller: com.lge.qremote
I/UEI.SmartControl( 6540): Registering Services Ready callback...
D/eas_req ( 6513): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/UEI.SmartControl( 6540):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6540): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6540): -----IControl: 8
,D/UEI.SmartControl( 6540): Caller: com.lge.qremote
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_6163/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6540): Internal service binding...
I/ActivityManager(  839): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6565 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6513): JNI_OnLoad()
I/HubEmail( 6513): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6513): registerNatives()
I/HubEmail( 6513): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6513): registerNativeMethods()
I/HubEmail( 6513): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6513): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  839): Killing 6205:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_6205/cgroup.procs: No such file or directory
,W/Settings( 6513): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6565): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6565): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6565): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6565): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6565): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6565): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6565): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6565): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6589 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6565): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6565): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6565): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6565): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6565): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6565): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  839): Killing 4954:com.lge.qremote/u0a106 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6589): onCreate
W/AppUp4:DB( 6589):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6589):  setFingerPrint start
I/AppUp4:DB( 6589):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6589):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6589):  SDK version = 0
I/AppUp4:DB( 6589):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  839): failed to open /acct/uid_10106/pid_4954/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6589): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6589): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6589): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6589): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6589): [onReceive] request level :IDLE....
D/WeatherService( 2681): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:7:0
,D/WeatherService( 2681): 2 : TimeTick Intent And Screen On
D/WeatherService( 2681): 2 : SDK version : 21
I/AppUp4:CustModeStarterReceiver( 6589): onReceive
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
I/AppUp4:CustModeStarterReceiver( 6589): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/Weather.Utils( 2681): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2681): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2681): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2681): 2 : requestRefreshAppWidget, isUpdateStart : false
D/AppUp4:CustFacade( 6589): Context : android.app.ReceiverRestrictedContext@620f341
D/UpdateThreadPoolManager( 2681): 2 : This is isUpdating : false
D/WeatherService( 2681): 2 : requestRefreshAppWidget, isUpdating : false
D/AppUp4:CustFacade( 6589): isCustomizationCompleted : false
D/WeatherAncestor( 2681): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2681): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2681): 2 : Fixed theme : optimus
D/AppUp4:CustFacade( 6589): isSimDevice : true
,D/WeatherReflect( 2681): 2 : Map key string is -2
D/AppUp4:CustModeStarterReceiver( 6589): begin check event
I/AppUp4:CustModeStarterReceiver( 6589): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6589): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6589): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6589): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6589): handleAsyncCustNotification do not startCustService
I/ActivityManager(  839): Killing 5413:com.android.vending/u0a36 (adj 15): empty #11
D/lim     ( 2681): 2 : time = 13:07
I/WeatherReflect( 2681): Model Name : LG-D722
D/WeatherTheme( 2681): 2 : Different view - status_min_formatted : 06 != 07
D/WeatherTheme( 2681): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2681): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2681): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2681): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2681): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2681): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2681): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2681): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2681): forecast size is 0
D/Theme   ( 2681): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2681): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2681): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2681): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2681): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2681): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2681): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2681): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2681): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2681): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2681): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2681): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2681): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2681): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2681): setTouchIntent, appWidgetId: 2
W/libprocessgroup(  839): failed to open /acct/uid_10036/pid_5413/cgroup.procs: No such file or directory
,D/Theme_WeatherAncestor_optimus( 2681): url is : null
D/Theme   ( 2681): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2681): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2681): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2681): 2 : update view, appWidgetId: 2
D/WeatherService( 2681): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:7:0
I/LgeMiscReceiver( 3157): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3157): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3157): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 6381): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6381): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3204): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3204): DownloadService onCreate
I/DownloadManager( 3204): in removeSpuriousFiles
I/NotificationManager( 3204): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@5d24115 on behalf of 3204
I/DownloadManager( 3204): in trimDatabase
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@35984c2a on behalf of 3204
I/ActivityManager(  839): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6611 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3204): DownloadService onStartCommand
V/DownloadManager( 3204): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@1422d991 on behalf of 3204
,V/DownloadManager( 3204): DownloadService onDestroy
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  839): Killing 6401:com.android.providers.calendar/u0a14 (adj 15): empty #11
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/libprocessgroup(  839): failed to open /acct/uid_10014/pid_6401/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2681): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:7:0
D/UpdateThreadPoolManager( 2681): 2 : This is isUpdating : false
D/WeatherAncestor( 2681): connectivity changed - connection : true
D/Weather_cast( 2681): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2681): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:7:0
D/WeatherService( 2681): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6628 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2681): 2 : Utils getTopActivity com.lge.launcher2 / true
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,D/WeatherService( 2681): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,D/WeatherService( 2681): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,W/ResourcesManager( 6628): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6628): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6628): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6628): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6628): MmsConfig.loadFromDatabase
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/Babel_SMS( 6628): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6628): MmsConfig.loadFromResources
E/Babel_SMS( 6628): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6628): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6628): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6628): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6628): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6628): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6628): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6628): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6628): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6628): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6628): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6628): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6628): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6628): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6628): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6628): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6628): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6628): found sensor: Motion Accel, handle=46
,I/art     (  839): Explicit concurrent mark sweep GC freed 14300(729KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.646ms total 159.547ms
,W/Settings( 6628): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/art     ( 6628): CheckpointMarkThreadRoots callback created = 0xaaf21430
,I/Babel_Crash( 6628): startup - clean
I/Babel   ( 6628): deleted: false for 0
,I/art     ( 6628): CheckpointMarkThreadRoots callback created = 0xaaf21410
I/ActivityManager(  839): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6661 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.157ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 30.574ms
,W/AudioCapabilities( 6628): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6628): Unsupported mime audio/adpcm
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 21.683ms
W/AudioCapabilities( 6628): Unsupported mime audio/g726
W/AudioCapabilities( 6628): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6628): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6628): Unsupported mime video/mjpg
,W/VideoCapabilities( 6628): Unsupported mime video/theora
W/AudioCapabilities( 6628): Unsupported mime audio/evrc
,W/AudioCapabilities( 6628): Unsupported mime audio/qcelp
W/VideoCapabilities( 6628): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6628): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6628): Unsupported mime audio/qcelp
W/AudioCapabilities( 6628): Unsupported mime audio/evrc
W/VideoCapabilities( 6628): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6628): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6628): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6628): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6628): Unrecognized profile 2130706433 for video/avc
,I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
W/VideoCapabilities( 6628): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6628): onServiceConnected
,W/Babel   ( 6628): Attempted to change video mute state without an active call.
,I/NotificationManager( 6628): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/libc-netbsd( 6628): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6628): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6628): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6628): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  273): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 6628): propertyValue:false
I/Babel   ( 6628): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  839): Killing 6427:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10053/pid_6427/cgroup.procs: No such file or directory
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6661): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6661): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6661): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6661): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6661): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6661):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6661):   adb logcat -s GAv4
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,W/GAv4    ( 6661): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6661): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6661): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6661): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6661): Time to load native libraries: 2 ms (timestamps 4196-4198)
,I/LibraryLoader( 6661): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6661): Binding Chromium to main looper Looper (main, tid 1) {307413da}
I/LibraryLoader( 6661): Expected native library version number "",actual native library version number ""
I/chromium( 6661): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6661): Initializing chromium process, singleProcess=true
W/art     ( 6661): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6661): ApplicationContext is null in ApplicationStatus
W/chromium( 6661): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6661): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6661): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6661): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6661): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6661): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6661): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6661): Remote Branch: 
I/Adreno-EGL( 6661): Local Patches: 
I/Adreno-EGL( 6661): Reconstruct Branch: 
V/AudioPolicyService(  279): registerClient() client 0xb3846ca0, uid 10079
,W/AudioManagerAndroid( 6661): Requires BLUETOOTH permission
I/NSApplication( 6661): Starting up...
,I/ActivityManager(  839): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6725 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6470:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10081/pid_6470/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6744 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 6540:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10089/pid_6540/cgroup.procs: No such file or directory
,W/ResourcesManager( 6744): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 5490): SYNC; picasa accounts
,D/NetworkLogImpl( 5490): Loaded NetworkSpeedPredictor
I/iu.Environment( 5490): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  839): Killing 6513:com.lge.email/u0a21 (adj 15): empty #11
I/iu.UploadsManager( 5490): num queued entries: 0
,I/iu.UploadsManager( 5490): num updated entries: 0
I/iu.SyncManager( 5490): NEXT; no task
W/libprocessgroup(  839): failed to open /acct/uid_10021/pid_6513/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6772 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MusicStore( 6772): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6772): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/CheckinService( 5490): Done disabling old GoogleServicesFramework version
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6772): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6772): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6772): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6772): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6772): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6772): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6772): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31ee6ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6772): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6772): GMSCore installation verified
I/ConfigStore( 6772): Config Database version: 1
,I/MediaRouter( 6772): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6772): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6772): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6772): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6812 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6772): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6772): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  839): Killing 6565:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 6812): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6812): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6812): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_6565/cgroup.procs: No such file or directory
,I/NotificationManager( 6772): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6812): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6812): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6812): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  839): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6838 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6812): JNI_OnLoad()
I/HubEmail( 6812): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6812): registerNatives()
I/HubEmail( 6812): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6812): registerNativeMethods()
I/HubEmail( 6812): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6812): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  839): Killing 6589:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_6589/cgroup.procs: No such file or directory
,W/Settings( 6812): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6838): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6838): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6838): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6838): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6838): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6838): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6863 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6838): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6838): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6838): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6838): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6838): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  839): Killing 6381:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_6381/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6863): onCreate
W/AppUp4:DB( 6863):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6863):  setFingerPrint start
I/AppUp4:DB( 6863):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6863):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6863):  SDK version = 0
I/AppUp4:DB( 6863):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6863): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6863): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6863): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6863): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6863): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6863): onReceive
I/AppUp4:CustModeStarterReceiver( 6863): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6863): Context : android.app.ReceiverRestrictedContext@620f341
D/AppUp4:CustFacade( 6863): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6863): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6863): begin check event
I/AppUp4:CustModeStarterReceiver( 6863): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6863): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6863): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6863): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6863): handleAsyncCustNotification do not startCustService
I/ActivityManager(  839): Killing 6611:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10051/pid_6611/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3157): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3157): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3157): networkInfo.isConnected() = false
I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6882 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6882): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6882): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6882): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  839): Killing 6628:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 6882): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6882): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6882): [parse] Load xml
V/TelephonyAutoProfiling( 6882): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6882): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6882): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_6628/cgroup.procs: No such file or directory
,V/DownloadManager( 3204): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3204): DownloadService onCreate
I/NotificationManager( 3204): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3204): in removeSpuriousFiles
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@373b7764 on behalf of 3204
I/DownloadManager( 3204): in trimDatabase
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@1e0a7dcd on behalf of 3204
I/ActivityManager(  839): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6904 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3204): DownloadService onStartCommand
V/DownloadManager( 3204): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 5490): Checkin interval check for package: unspecified last checkin: 1454414797102 min interval config: 0 actual interval: 28689
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@2b910193 on behalf of 3204
I/CheckinService( 5490): Checking schedule, now: 1454414825815 next: 1454414827068
I/CheckinService( 5490): active receiver: disabled
,V/DownloadManager( 3204): DownloadService onDestroy
,I/ActivityManager(  839): Killing 6661:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  839): failed to open /acct/uid_10079/pid_6661/cgroup.procs: No such file or directory
D/WeatherAncestor( 2681): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:7:6
,D/UpdateThreadPoolManager( 2681): 2 : This is isUpdating : false
D/WeatherAncestor( 2681): connectivity changed - connection : true
D/Weather_cast( 2681): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2681): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:7:6
D/WeatherService( 2681): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6927 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2681): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2681): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2681): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6927): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/jxcore-log( 5467): Test app app.js loaded
I/jxcore-log( 5467): 
,I/Babel_SMS( 6927): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6927): MmsConfig.loadMmsSettings
I/Babel_SMS( 6927): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6927): MmsConfig.loadFromDatabase
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5467): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5467): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5467): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5467): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5467): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5467): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5467): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5467): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5467): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5467): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ba4287d added. We now have 1 listener(s)
,D/BluetoothAdapterService(900784340)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1240a0ca
E/Babel_SMS( 6927): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6927): MmsConfig.loadFromResources
E/Babel_SMS( 6927): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6927): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/jxcore-log( 5467): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5467): 
D/SensorManager( 6927): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6927): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6927): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6927): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6927): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6927): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6927): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6927): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6927): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6927): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6927): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6927): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6927): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6927): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6927): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6927): found sensor: Motion Accel, handle=46
,W/Settings( 6927): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6927): startup - clean
I/Babel   ( 6927): deleted: false for 0
,I/chromium( 5467): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/art     ( 6927): CheckpointMarkThreadRoots callback created = 0xb042d590
,I/ActivityManager(  839): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6970 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6927): CheckpointMarkThreadRoots callback created = 0xb042d560
W/AudioCapabilities( 6927): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6927): Unsupported mime audio/adpcm
W/AudioCapabilities( 6927): Unsupported mime audio/g726
W/AudioCapabilities( 6927): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6927): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6927): Unsupported mime video/mjpg
W/VideoCapabilities( 6927): Unsupported mime video/theora
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
W/AudioCapabilities( 6927): Unsupported mime audio/evrc
,W/AudioCapabilities( 6927): Unsupported mime audio/qcelp
W/VideoCapabilities( 6927): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6927): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6927): Unsupported mime audio/qcelp
W/AudioCapabilities( 6927): Unsupported mime audio/evrc
W/VideoCapabilities( 6927): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6927): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6927): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6927): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6927): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6927): Unrecognized profile 2130706433 for video/avc
I/art     (  839): Explicit concurrent mark sweep GC freed 19416(976KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.587ms total 150.487ms
,I/vclib   ( 6927): onServiceConnected
W/Babel   ( 6927): Attempted to change video mute state without an active call.
,D/libc-netbsd( 6927): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6927): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6927): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6927): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  273): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 6927): propertyValue:false
I/NotificationManager( 6927): com.google.android.talk: cancel(10436) by com.google.android.talk
I/Babel   ( 6927): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  839): Killing 6725:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10048/pid_6725/cgroup.procs: No such file or directory
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6970): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6970): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6970): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6970):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6970):   adb logcat -s GAv4
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6970): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6970): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6970): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6970): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6970): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6970): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6970): Time to load native libraries: 2 ms (timestamps 9439-9441)
,I/LibraryLoader( 6970): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6970): Binding Chromium to main looper Looper (main, tid 1) {307413da}
I/LibraryLoader( 6970): Expected native library version number "",actual native library version number ""
I/chromium( 6970): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6970): Initializing chromium process, singleProcess=true
,W/art     ( 6970): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6970): ApplicationContext is null in ApplicationStatus
W/chromium( 6970): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6970): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6970): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6970): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6970): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6970): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6970): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6970): Remote Branch: 
I/Adreno-EGL( 6970): Local Patches: 
I/Adreno-EGL( 6970): Reconstruct Branch: 
V/AudioPolicyService(  279): registerClient() client 0xb3846da0, uid 10079
,W/AudioManagerAndroid( 6970): Requires BLUETOOTH permission
I/NSApplication( 6970): Starting up...
,I/ActivityManager(  839): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7035 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6744:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 357us total 23.268ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 335us total 25.506ms
,W/libprocessgroup(  839): failed to open /acct/uid_10086/pid_6744/cgroup.procs: No such file or directory
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 363us total 25.222ms
,I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7058 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 6772:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10081/pid_6772/cgroup.procs: No such file or directory
,W/ResourcesManager( 7058): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  839): Killing 6812:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10021/pid_6812/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7089 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7089): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  839): Message: 20
D/BluetoothManagerService(  839): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28d3cbf8:true
,D/BluetoothAdapterService(900784340)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1240a0ca
D/BluetoothAdapterService(900784340)( 1988): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1240a0ca
I/AudioManager( 7089): getMode name:com.lge.qremote
,I/AudioManager( 7089): getMode name:com.lge.qremote
,I/ActivityManager(  839): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7107 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7107): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7107): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7107): Error finding the version of the Email provider.....
E/Gmail   ( 7107): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7107): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7107): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7107): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7107): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7107): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7107): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7107): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7107): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7107): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  839): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7107): Observing account changes for notifications
W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  839): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7153 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 6838:com.lge.lgdmsclient/1000 (adj 15): empty #11
,V/AlarmManager(  839): RTC_WAKEUP set : Alarm{d4377d type 0 when 1454414827068 com.google.android.gms} when 1454414827068
,I/Gmail   ( 7107): notifyAccountChanged
,I/Gmail   ( 7107): getAccountsCursor
I/Gmail   ( 7107): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7107): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  839): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7172 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{2b620ac3 type 0 when 1454414829183 com.android.vending} when 1454414829183
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_6838/cgroup.procs: No such file or directory
,I/Gmail   ( 7107): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7107): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicStore( 7153): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7153): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Gmail   ( 7107): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7153): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7153): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/Finsky  ( 7172): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/ResourcesManager( 7153): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7153): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7153): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7153): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7153): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31ee6ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7153): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7153): GMSCore installation verified
I/ConfigStore( 7153): Config Database version: 1
,D/Finsky  ( 7172): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7172): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7172): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7172): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@124e29c9 on behalf of 7172
D/Finsky  ( 7172): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7172): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7172): Skipping gmscore version check
I/art     ( 3890): Explicit concurrent mark sweep GC freed 2529(96KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 470us total 35.420ms
D/Finsky  ( 7172): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7172): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/Finsky  ( 7172): [925] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7172): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/art     (  839): Explicit concurrent mark sweep GC freed 21736(1021KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.199ms total 158.332ms
I/MediaRouter( 7153): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7153): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7153): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  839): Killing 6863:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_6863/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7153): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7237 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7153): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7153): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  839): Killing 6882:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/ResourcesManager( 7237): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7237): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7237): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_6882/cgroup.procs: No such file or directory
,I/NotificationManager( 7153): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7237): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7237): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7237): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  839): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7263 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7237): JNI_OnLoad()
I/HubEmail( 7237): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7237): registerNatives()
I/HubEmail( 7237): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7237): registerNativeMethods()
I/HubEmail( 7237): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7237): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 7237): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  839): Killing 6904:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10051/pid_6904/cgroup.procs: No such file or directory
,D/LGDMClient( 7263): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7263): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7263): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7263): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7263): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7263): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 7263): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7263): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7287 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7263): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7263): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7263): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7263): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7263): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 7263): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  839): Killing 6970:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/AppUp4:AppBoxCP( 7287): onCreate
,W/AppUp4:DB( 7287):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7287):  setFingerPrint start
I/AppUp4:DB( 7287):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7287):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7287):  SDK version = 0
I/AppUp4:DB( 7287):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  839): failed to open /acct/uid_10079/pid_6970/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 7287): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7287): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7287): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7287): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7287): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7287): onReceive
I/AppUp4:CustModeStarterReceiver( 7287): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7287): Context : android.app.ReceiverRestrictedContext@620f341
D/AppUp4:CustFacade( 7287): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7287): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7287): begin check event
I/AppUp4:CustModeStarterReceiver( 7287): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7287): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7287): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7287): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7287): handleAsyncCustNotification do not startCustService
I/ActivityManager(  839): Killing 7035:com.android.chrome/u0a48 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  839): failed to open /acct/uid_10048/pid_7035/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3157): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3157): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3157): networkInfo.isConnected() = true
D/PhoneState( 3157): setPdpRejectCasuse : false
I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7309 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7309): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7309): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7309): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  839): Killing 7058:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/PhoneMonitor( 7309): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7309): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7309): [parse] Load xml
V/TelephonyAutoProfiling( 7309): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 7309): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7309): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  839): failed to open /acct/uid_10086/pid_7058/cgroup.procs: No such file or directory
V/DownloadManager( 3204): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3204): DownloadService onCreate
I/NotificationManager( 3204): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3204): in removeSpuriousFiles
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@367938ce on behalf of 3204
I/DownloadManager( 3204): in trimDatabase
V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@261c4efc on behalf of 3204
I/ActivityManager(  839): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7331 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3204): DownloadService onStartCommand
V/DownloadManager( 3204): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 5490): Checkin interval check for package: unspecified last checkin: 1454414797102 min interval config: 0 actual interval: 34127
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@307413da on behalf of 3204
,I/CheckinService( 5490): Checking schedule, now: 1454414831268 next: 1454414827068
,I/CheckinService( 5490): active receiver: enabled
,V/DownloadManager( 3204): DownloadService onDestroy
,I/CheckinService( 5490): Preparing to send checkin request
I/EventLogService( 5490): Accumulating logs since 1454414788066
,D/WeatherAncestor( 2681): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:7:11
D/UpdateThreadPoolManager( 2681): 2 : This is isUpdating : false
D/WeatherAncestor( 2681): connectivity changed - connection : true
D/Weather_cast( 2681): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2681): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 13:7:11
D/WeatherService( 2681): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2681): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2681): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2681): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  839): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7357 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 22.182ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.305ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.680ms
,I/CheckinRequestBuilder( 5490): Checkin reason type: 8 attempt count: 1
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7357): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7357): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7357): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7357):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7357):   adb logcat -s GAv4
E/ActivityThread( 5490): Failed to find provider info for com.google.android.wearable.settings
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7357): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7357): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7357): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7357): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7357): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/ActivityManager(  839): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7404 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/WebViewFactory( 7357): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/ResourcesManager( 7404): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7404): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/LibraryLoader( 7357): Time to load native libraries: 2 ms (timestamps 3815-3817)
I/LibraryLoader( 7357): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7357): Binding Chromium to main looper Looper (main, tid 1) {307413da}
,I/LibraryLoader( 7357): Expected native library version number "",actual native library version number ""
I/chromium( 7357): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7357): Initializing chromium process, singleProcess=true
,W/art     ( 7357): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7357): ApplicationContext is null in ApplicationStatus
I/MultiDex( 7404): VM with version 2.1.0 has multidex support
I/MultiDex( 7404): install
I/MultiDex( 7404): VM has multidex support, MultiDex support library is disabled.
W/chromium( 7357): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7357): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7357): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7357): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7357): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7357): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7357): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7357): Remote Branch: 
I/Adreno-EGL( 7357): Local Patches: 
I/Adreno-EGL( 7357): Reconstruct Branch: 
V/JNIHelp ( 7404): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/AudioPolicyService(  279): registerClient() client 0xb3846ce0, uid 10079
,W/ActivityThread( 7404): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7404): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35984c2a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
W/AudioManagerAndroid( 7357): Requires BLUETOOTH permission
I/ProviderInstaller( 7404): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7404): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7404): com.google.android.gms: cancel(39789) by com.google.android.gms
I/NSApplication( 7357): Starting up...
,I/ActivityManager(  839): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7446 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 7404): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7404): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  839): Killing 7107:com.google.android.gm/u0a53 (adj 15): empty #11
,D/NativeLibraryUtils( 7404): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  839): failed to open /acct/uid_10053/pid_7107/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7471 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 7172:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10036/pid_7172/cgroup.procs: No such file or directory
,D/WVCdm   (  279): Instantiating CDM.
I/WVCdm   (  279): CdmEngine::OpenSession
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
,W/ResourcesManager( 7471): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=2056508347
,I/ActivityManager(  839): Killing 7153:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/art     ( 7404): CheckpointMarkThreadRoots callback created = 0xb04cbeb0
I/art     ( 7404): CheckpointMarkThreadRoots callback created = 0xb04cbea0
,W/libprocessgroup(  839): failed to open /acct/uid_10081/pid_7153/cgroup.procs: No such file or directory
,D/WearableService( 1735): callingUid 10006, callindPid: 1735
,E/MDM     ( 1735): [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5490): Restart initialization of location
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/WVCdm   (  279): CdmEngine::OpenSession
,I/art     (  839): Explicit concurrent mark sweep GC freed 18005(849KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.269ms total 155.410ms
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AudioManager( 7089): getMode name:com.lge.qremote
I/AudioManager( 7089): getMode name:com.lge.qremote
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
I/ActivityManager(  839): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7512 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 7512): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7512): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7512): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7512): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7512): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@b5d5ee8 on behalf of 7512
D/Finsky  ( 7512): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7512): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7512): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 7512): [979] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Ads     ( 7512): Skipping gmscore version check
D/Finsky  ( 7512): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,D/libc-netbsd( 7512): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7512): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7512): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7512): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  273): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  839): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7565 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7089): Create singleton instance
,D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 7512): propertyValue:false
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 115695539126; DSPS: 3889146; Offset : -3002656490
,D/UEI.SmartControl( 7565): Quickset Services start...
,I/UEI.SmartControl( 7565): Manufacture = LGE
D/UEI.SmartControl( 7565): File observer start...
E/UEI.SmartControl( 7565): IR Port is disabled: false
D/UEI.SmartControl( 7565): Starting file observer...
D/UEI.SmartControl( 7565): Extracting JNI libs...
D/UEI.SmartControl( 7565): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7089): getMode name:com.lge.qremote
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7565): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7565): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7565): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  839): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7585 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UEI.SmartControl( 7565): --- Selecting new region: 2
,I/UEI.SmartControl( 7565): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7565): Platform has CIR...
D/UEI.SmartControl( 7565): NO CIR support, need to check package...
I/UEI.SmartControl( 7565): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7565): QS Service created
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/UEI.SmartControl( 7565): QS start get config
D/UEI.SmartControl( 7565): Loading JNI Libs...
,D/UEI.SmartControl( 7565):  configuring local db...
I/ActivityManager(  839): Killing 7237:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10021/pid_7237/cgroup.procs: No such file or directory
W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/MusicWidget( 2584): mDelayedStopHandler : unbind
,I/Gmail   ( 7585): getAccountsCursor
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicBrowser( 2051): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2051): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
D/UEI.SmartControl( 7565):  ---- Has DB8: true
I/MusicBrowser( 2051): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2051): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2051): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2051): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
W/GAV2    ( 7585): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/UEI.SmartControl( 7565): QS start statue = true Error code = 0
I/MusicBrowser( 2051): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,D/UEI.SmartControl( 7565): QS version = v2.7.11.1_RC1
I/MusicBrowser( 2051): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
D/UEI.SmartControl( 7565): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7565): IRRCDataComm has AudioManager!!!!.
I/MediaFocusControl(  839):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2d2fff96com.lge.music.MediaPlaybackService$6@2153b717
D/MusicBrowser( 2051): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,W/irrc_jni( 7565): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7565): IrrcClient ++ 
D/irrcClient( 7565): getIrrcService ++ 
D/irrcClient( 7565): getIrrcService -- 
D/irrcClient( 7565): IrrcClient -- 
W/irrc_jni( 7565): IRRCPlayer_nativeInit -- 
I/MusicBrowser( 2051): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2051): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2051): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2051): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@38c8827d
I/MusicBrowser( 2051): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/UEI.SmartControl( 7565): Services init done
,I/UEI.SmartControl( 7565): Device manager: loading config....
I/MusicBrowser( 2051): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2051): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/UEI.SmartControl( 7565): QS Service init finished
D/UEI.SmartControl( 7565): QS Service version name: 0.1.73
W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/UEI.SmartControl( 7565): QS Service version code: 1073
I/MusicBrowser( 2051): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2051): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2051): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/UEI.SmartControl( 7565): Service requested: Control
I/MusicBrowser( 2051): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2051): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2051): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/UEI.SmartControl( 7565): Config is loaded...
I/MusicBrowser( 2051): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2051): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2051): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2051): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2051): reset
E/Gmail   ( 7585): Error finding the version of the Email provider.....
E/Gmail   ( 7585): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7585): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7585): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7585): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7585): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7585): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7585): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7585): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7585): We do not support migrating this version of the Email provider.
V/MediaPlayer[Native]( 2051): setListener
V/MediaPlayer[Native]( 2051): disconnect
V/MediaPlayer[Native]( 2051): destructor
I/Gmail   ( 7585): getAccountsCursor
V/AudioFlinger(  279): releasing 19 from 2051 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
D/UEI.SmartControl( 7565):  ----- QS SDK is ready!!!
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/MediaPlayer[Native]( 2051): disconnect
,D/MusicBrowser( 2051): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/UEI.SmartControl( 7565): Notify AllClients services are ready: 0
I/SmartShareClient( 2051): [SmartShareManagerClient] smartshare client supported version code: 305010
D/UEI.SmartControl( 7565): Request IControl service: devices are loaded...
I/SmartShareClient( 2051): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2051): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2051): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
,V/MusicBrowser( 2051): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
D/UEI.SmartControl( 7565): Internal service binding...
I/SmartShareClient( 2051): [SmartShareManagerClient] unregisterListener: 624436996
W/SmartShareClient( 2051): [SmartShareManagerClient] unregisterListener invalid listener: 624436996
D/UEI.SmartControl( 7565): -----IControl: 11
I/SmartShareClient( 2051): [SmartShareManagerClient] terminate service: 2051/MediaPlaybackService/656449611
D/UEI.SmartControl( 7565): Caller: com.lge.qremote
D/UEI.SmartControl( 7565): ------------ IControl registerCallback...
I/UEI.SmartControl( 7565): Registering callback...
D/UEI.SmartControl( 7565): -----IControl: 19
E/HomeCloudIF( 2051): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2051): [SmartShareManagerClient] unbindService context:android.app.Application@25e404ed
D/UEI.SmartControl( 7565): Caller: com.lge.qremote
I/UEI.SmartControl( 7565): Registering Services Ready callback...
W/ActivityManager(  839): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/UEI.SmartControl( 7565): Notify client services are ready...
I/AudioManager( 7089): getMode name:com.lge.qremote
,I/ActivityManager(  839): Killing 7263:com.lge.lgdmsclient/1000 (adj 15): empty #11
D/UEI.SmartControl( 7565): -----IControl: 8
D/UEI.SmartControl( 7565): Caller: com.lge.qremote
I/Gmail   ( 7585): Observing account changes for notifications
,V/CloudHub( 2051): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2051): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2051): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2051): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2051): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_7263/cgroup.procs: No such file or directory
,W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  839): Killing 7287:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/CloudHub( 2051): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29867
I/WVCdm   (  279): CdmEngine::CloseSession
,W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_7287/cgroup.procs: No such file or directory
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  839): Killing 6927:com.google.android.talk/u0a61 (adj 15): empty #11
I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=1294312319
I/ActivityManager(  839): Killing 7331:com.lge.drmservice/u0a51 (adj 15): empty #12
,W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_6927/cgroup.procs: No such file or directory
,W/libprocessgroup(  839): failed to open /acct/uid_10051/pid_7331/cgroup.procs: No such file or directory
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AudioManager( 7089): getMode name:com.lge.qremote
I/CheckinService( 5490): Checkin interval check for package: unspecified last checkin: 1454414797102 min interval config: 0 actual interval: 37730
,E/MDM     ( 1735): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5490): Restart initialization of location
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/ContextImpl( 3553): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,I/AudioManager( 7089): getMode name:com.lge.qremote
,I/AudioManager( 7089): getMode name:com.lge.qremote
,I/AudioManager( 7089): getMode name:com.lge.qremote
I/AudioManager( 7089): getMode name:com.lge.qremote
,I/AudioManager( 7089): getMode name:com.lge.qremote
,I/Gmail   ( 7585): notifyAccountChanged
I/Gmail   ( 7585): getAccountsCursor
I/Gmail   ( 7585): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7585): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7585): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7585): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7585): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/WVCdm   (  279): CdmEngine::CloseSession
I/WVCdm   (  279): L3 Terminate.
,I/dex2oat ( 7660): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/dex2oat ( 7660): dex2oat took 88.960ms (threads: 4)
I/Adreno-EGL( 7404): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7404): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7404): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7404): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7404): Remote Branch: 
I/Adreno-EGL( 7404): Local Patches: 
I/Adreno-EGL( 7404): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/Adreno-EGL( 7404): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7404): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7404): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7404): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7404): Remote Branch: 
I/Adreno-EGL( 7404): Local Patches: 
I/Adreno-EGL( 7404): Reconstruct Branch: 
,I/Adreno-EGL( 7404): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7404): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7404): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7404): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7404): Remote Branch: 
I/Adreno-EGL( 7404): Local Patches: 
I/Adreno-EGL( 7404): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5490): Classify the device as Phone.
,D/libc-netbsd( 5490): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5490): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5490): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5490): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 5490): propertyValue:false
D/libc-netbsd( 5490): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5490): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5490): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5490): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5490): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5490): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5490): Sending checkin request (9767 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 5490): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5490): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  839): Explicit concurrent mark sweep GC freed 19500(904KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.249ms total 145.225ms
,I/CheckinRequestBuilder( 5490): Classify the device as Phone.
,I/CheckinTask( 5490): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5490): Checking schedule, now: 1454414838707 next: 1454942087700
I/CheckinService( 5490): active receiver: disabled
,I/CheckinService( 5490): Checking schedule, now: 1454414838744 next: 1454942087700
I/CheckinService( 5490): active receiver: disabled
,D/CheckinService( 5490): Recording last checkin time for package unspecified as 1454414838754
,I/art     ( 3890): Explicit concurrent mark sweep GC freed 3297(136KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 367us total 25.420ms
,V/SetupWizard( 7309): Connected to Gservices successfully
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 7585): Thread[GAThread,5,main]: No campaign data found.
,D/UEI.SmartControl( 7565): Internal timer expired: 1
,I/ActivityManager(  839): Killing 7446:com.android.chrome/u0a48 (adj 15): empty #11
,I/ActivityManager(  839): Killing 7357:com.google.android.apps.magazines/u0a79 (adj 15): empty #12
,W/libprocessgroup(  839): failed to open /acct/uid_10048/pid_7446/cgroup.procs: No such file or directory
,W/libprocessgroup(  839): failed to open /acct/uid_10079/pid_7357/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7697 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,D/administrator(  839): Handling package changes for user 0
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
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7697): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  839): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  839): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  839): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  839): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  839): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1b5e00a0
,I/Babel_SMS( 7697): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7697): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7697): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7697): MmsConfig.loadFromDatabase
W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  839): Process com.google.android.apps.plus (pid 7471) has died
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
,E/Babel_SMS( 7697): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7697): MmsConfig.loadFromResources
,E/Babel_SMS( 7697): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7697): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
I/art     ( 7697): CheckpointMarkThreadRoots callback created = 0xaaf20e90
,W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/SensorManager( 7697): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7697): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7697): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7697): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7697): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7697): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7697): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7697): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7697): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7697): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7697): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7697): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7697): found sensor: LGE Tilt Detector Sensor, handle=55
,D/SensorManager( 7697): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7697): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7697): found sensor: Motion Accel, handle=46
I/art     ( 7697): CheckpointMarkThreadRoots callback created = 0xaaf20e80
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/Settings( 7697): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7697): startup - clean
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  839): applying state to connected service
,I/Babel   ( 7697): deleted: false for 0
,W/AudioCapabilities( 7697): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7697): Unsupported mime audio/adpcm
W/AudioCapabilities( 7697): Unsupported mime audio/g726
W/AudioCapabilities( 7697): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7697): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7697): Unsupported mime video/mjpg
,W/VideoCapabilities( 7697): Unsupported mime video/theora
I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7735 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 7697): Unsupported mime audio/evrc
,W/AudioCapabilities( 7697): Unsupported mime audio/qcelp
W/VideoCapabilities( 7697): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7697): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7697): Unsupported mime audio/qcelp
W/AudioCapabilities( 7697): Unsupported mime audio/evrc
W/VideoCapabilities( 7697): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7697): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7697): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7697): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7697): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7697): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 7735): onCreate
,W/AppUp4:DB( 7735):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7735):  setFingerPrint start
,I/AppUp4:DB( 7735):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7735):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7735):  SDK version = 0
I/AppUp4:DB( 7735):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7735): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7735): onReceive
,I/AppUp4:CustModeStarterReceiver( 7735): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7735): Context : android.app.ReceiverRestrictedContext@2faebd1a
D/AppUp4:CustFacade( 7735): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7735): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7735): begin check event
I/AppUp4:CustModeStarterReceiver( 7735): Event For Nothing, skip.
,I/ActivityManager(  839): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7756 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  839): Process com.android.vending (pid 7512) has died
,I/vclib   ( 7697): onServiceConnected
W/Babel   ( 7697): Attempted to change video mute state without an active call.
I/NotificationManager( 7697): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7756): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7756): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7756): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7697): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7697): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 7697): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7697): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7697): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7697): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 7756): Total System Memory = 906309632
,I/GalleryUtils( 7756): Application Heap = 96 MB
I/AppConfig( 7756): App Tier : NOT_DEF
D/SystemHelper( 7756): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  839): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7781 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7781): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7781): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7781): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7781): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7781): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7781): BUILD Country: EU
I/SystemConfig( 7781): BUILD Operator: OPEN
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  839): Process com.google.android.gm (pid 7585) has died
,I/ActivityManager(  839): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7803 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 24.264ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.150ms
I/SystemConfig( 7781): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7781): existFile = false
I/SystemConfig( 7781): canReadFile = false
I/SystemConfig( 7781): systemFeature RCS result false
D/SystemConfig( 7781): refreshRcsSupport() :false
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 377us total 22.273ms
,I/LockScreenSettings( 7803): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/LockScreenSettings( 7803): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7803): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 7803): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7803): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7803): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7820 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 2051:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  279): 2051 died, releasing its sessions
V/AudioFlinger(  279):  pid 1754 @ 0
V/AudioFlinger(  279):  pid 3157 @ 1
V/AudioFlinger(  279):  pid 3157 @ 2
,W/libprocessgroup(  839): failed to open /acct/uid_10028/pid_2051/cgroup.procs: No such file or directory
,W/ResourcesManager( 7820): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1944): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  839): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7846 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1944): UpdateCorporaTask done [took 74 ms] updated apps [took 74 ms] 
,I/ActivityManager(  839): Killing 7309:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_7309/cgroup.procs: No such file or directory
D/Finsky  ( 7846): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7846): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7846): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7846): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7846): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3204): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3204): created cursor android.database.sqlite.SQLiteCursor@191c4901 on behalf of 7846
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/Finsky  ( 7846): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7846): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7846): Skipping gmscore version check
,I/ActivityManager(  839): Killing 7404:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_7404/cgroup.procs: No such file or directory
,D/Finsky  ( 7846): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5490): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5490): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5490): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7846): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  479): init target 500000
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
,I/Icing   ( 5490): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
,W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  839): battery changed pluggedType: 2
,D/charger_monitor(  479): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/Icing   ( 5490): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  291): Sensor:pa_therm0:33000 mC
,I/ActivityManager(  839): Killing 7565:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7089): android.os.DeadObjectException
,W/System.err( 7089): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7089): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7089): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7089): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7089): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7089): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7089): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7089): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7089): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7089): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7089): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7089): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7089): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7089): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7089): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7089): android.os.DeadObjectException
W/System.err( 7089): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7089): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7089): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7089): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7089): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7089): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7089): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7089): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7089): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7089): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7089): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7089): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7089): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7089): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7089): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  839): failed to open /acct/uid_10089/pid_7565/cgroup.procs: No such file or directory
W/ActivityManager(  839): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  839): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7920 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7920): Quickset Services start...
,I/UEI.SmartControl( 7920): Manufacture = LGE
D/UEI.SmartControl( 7920): File observer start...
E/UEI.SmartControl( 7920): IR Port is disabled: false
D/UEI.SmartControl( 7920): Starting file observer...
D/UEI.SmartControl( 7920): Extracting JNI libs...
D/UEI.SmartControl( 7920): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7920): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7920): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7920): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7920): --- Selecting new region: 2
,I/UEI.SmartControl( 7920): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7920): Platform has CIR...
D/UEI.SmartControl( 7920): NO CIR support, need to check package...
I/UEI.SmartControl( 7920): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7920): QS Service created
E/UEI.SmartControl( 7920): QS start get config
,D/UEI.SmartControl( 7920): Loading JNI Libs...
,D/UEI.SmartControl( 7920):  configuring local db...
D/UEI.SmartControl( 7920):  ---- Has DB8: true
,D/UEI.SmartControl( 7920): QS start statue = true Error code = 0
D/UEI.SmartControl( 7920): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7920): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7920): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7920): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7920): IrrcClient ++ 
D/irrcClient( 7920): getIrrcService ++ 
,D/irrcClient( 7920): getIrrcService -- 
D/irrcClient( 7920): IrrcClient -- 
W/irrc_jni( 7920): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7920): Services init done
I/UEI.SmartControl( 7920): Device manager: loading config....
D/UEI.SmartControl( 7920): QS Service init finished
D/UEI.SmartControl( 7920): Config is loaded...
D/UEI.SmartControl( 7920): QS Service version name: 0.1.73
D/UEI.SmartControl( 7920): QS Service version code: 1073
,D/UEI.SmartControl( 7920): Service requested: Control
I/ActivityManager(  839): Killing 7089:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7920): Internal service binding...
W/libprocessgroup(  839): failed to open /acct/uid_10106/pid_7089/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7920):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7920): Notify AllClients services are ready: 0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7920): Internal timer expired: 1
,D/UEI.SmartControl( 7920): Service.onUnbind: IControl
D/UEI.SmartControl( 7920): Service.onDestroy
D/UEI.SmartControl( 7920): Shutdown IRRCPlayer... 
,W/irrc_jni( 7920): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7920): ~IrrcClient ++ 
D/irrcClient( 7920): ~IrrcClient -- 
W/irrc_jni( 7920): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7920): Blaster closed
D/UEI.SmartControl( 7920): Blaster closed
D/UEI.SmartControl( 7920): Shut down QS...
,D/UEI.SmartControl( 7920): Stopped file observer...
I/UEI.SmartControl( 7920): QS lib stop result = true
D/UEI.SmartControl( 7920): QS shutdown complete
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 135696297504; DSPS: 4544531; Offset : -3002661677
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{3ad55553 type 2 when 145809 com.google.android.gms} when 145809
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1735): Vacuum at: now=1454414864162 tag=VacuumService
,I/art     (  839): Explicit concurrent mark sweep GC freed 36990(1820KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.373ms total 162.021ms
,I/art     ( 1735): Explicit concurrent mark sweep GC freed 45552(2MB) AllocSpace objects, 22(352KB) LOS objects, 40% free, 13MB/22MB, paused 1.835ms total 96.222ms
,I/PhenotypeConfigurator( 1735): Scheduling Phenotype for one-off execution 1645 seconds from now (1454414864765)
,D/GetConfigurationSnapshotOperation( 1735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1735): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
,I/System.out( 1735): propertyValue:false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  273): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  273): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  273): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  273): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  273): res_queryN name = xxxxx succeed
I/System.out( 1735): propertyValue:false
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  839): android: cancelAsUser(2) by android
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  839): ALS enabled for SRE
,D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29924 ms ago)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/qdlights(  839): set_light_backlight: 253
,D/qdlights(  839): set_light_backlight: 250
D/qdlights(  839): set_light_backlight: 247
,D/qdlights(  839): set_light_backlight: 243
,D/qdlights(  839): set_light_backlight: 240
,D/qdlights(  839): set_light_backlight: 237
,D/qdlights(  839): set_light_backlight: 233
,D/qdlights(  839): set_light_backlight: 230
,D/qdlights(  839): set_light_backlight: 227
,D/qdlights(  839): set_light_backlight: 223
,D/qdlights(  839): set_light_backlight: 220
,D/qdlights(  839): set_light_backlight: 217
,D/qdlights(  839): set_light_backlight: 213
,D/qdlights(  839): set_light_backlight: 210
,D/qdlights(  839): set_light_backlight: 207
,D/qdlights(  839): set_light_backlight: 203
,D/qdlights(  839): set_light_backlight: 200
,D/qdlights(  839): set_light_backlight: 197
,D/qdlights(  839): set_light_backlight: 193
,D/qdlights(  839): set_light_backlight: 190
,D/qdlights(  839): set_light_backlight: 187
,D/qdlights(  839): set_light_backlight: 183
,D/qdlights(  839): set_light_backlight: 180
,D/qdlights(  839): set_light_backlight: 177
,D/qdlights(  839): set_light_backlight: 173
,D/qdlights(  839): set_light_backlight: 170
,D/qdlights(  839): set_light_backlight: 167
,D/qdlights(  839): set_light_backlight: 163
,D/qdlights(  839): set_light_backlight: 160
,D/qdlights(  839): set_light_backlight: 157
,D/qdlights(  839): set_light_backlight: 153
,D/qdlights(  839): set_light_backlight: 150
,D/qdlights(  839): set_light_backlight: 147
,D/qdlights(  839): set_light_backlight: 143
,D/qdlights(  839): set_light_backlight: 140
,D/qdlights(  839): set_light_backlight: 137
,D/qdlights(  839): set_light_backlight: 133
,D/qdlights(  839): set_light_backlight: 130
,D/qdlights(  839): set_light_backlight: 127
,D/qdlights(  839): set_light_backlight: 123
,D/qdlights(  839): set_light_backlight: 120
,D/qdlights(  839): set_light_backlight: 117
,D/qdlights(  839): set_light_backlight: 113
,D/qdlights(  839): set_light_backlight: 110
,D/qdlights(  839): set_light_backlight: 107
,D/qdlights(  839): set_light_backlight: 103
,D/qdlights(  839): set_light_backlight: 100
,D/qdlights(  839): set_light_backlight: 97
,D/qdlights(  839): set_light_backlight: 93
,D/qdlights(  839): set_light_backlight: 90
,D/qdlights(  839): set_light_backlight: 87
,D/qdlights(  839): set_light_backlight: 83
,D/qdlights(  839): set_light_backlight: 80
,D/qdlights(  839): set_light_backlight: 77
,D/qdlights(  839): set_light_backlight: 73
D/qdlights(  839): set_light_backlight: 70
,D/qdlights(  839): set_light_backlight: 67
,D/qdlights(  839): set_light_backlight: 63
,D/qdlights(  839): set_light_backlight: 60
,D/qdlights(  839): set_light_backlight: 57
,D/qdlights(  839): set_light_backlight: 53
,D/qdlights(  839): set_light_backlight: 50
,D/qdlights(  839): set_light_backlight: 47
,D/qdlights(  839): set_light_backlight: 43
,D/qdlights(  839): set_light_backlight: 40
,D/qdlights(  839): set_light_backlight: 37
,D/qdlights(  839): set_light_backlight: 33
,D/qdlights(  839): set_light_backlight: 30
,D/qdlights(  839): set_light_backlight: 27
,D/qdlights(  839): set_light_backlight: 23
,D/qdlights(  839): set_light_backlight: 20
,D/qdlights(  839): set_light_backlight: 17
,D/qdlights(  839): set_light_backlight: 13
,D/qdlights(  839): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 155697048069; DSPS: 5199915; Offset : -3002642857
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  839): ALS enabled for SRE
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36912 ms ago)
I/PowerManagerService(  839): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  839): ALS enabled for SRE
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36926 ms ago)
,W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  839): Sleeping (uid 1000)...
D/LPWGController(  839): [updateScreenState] screen on = false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LPWGController(  839): disable proximity sensor
D/LPWGController(  839): enable proximity sensor
I/SensorManager(  839): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@33cb8dbb] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  839): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  839): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  839): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  839): activate: handle is 48, enable
,V/sensors_hal_Ctx(  839): activate sensors is 1400000000000
D/sensors_hal_Thresh(  839): enable: handle=48
I/sensors_hal_SAM(  839): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  839): waitForResponse: timeout=1000
V/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  839): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  839): enable: Received response: 0
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36997 ms ago)
I/Adreno-EGL(  839): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  839): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  839): Build Date: 03/02/15 Mon
I/Adreno-EGL(  839): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  839): Remote Branch: 
I/Adreno-EGL(  839): Local Patches: 
I/Adreno-EGL(  839): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1156 us)
,I/Sensors (  423): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  839): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  839): processInd: handle 48, count=1
V/sensors_hal_Thresh(  839): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  839): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  839): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  839): poll: count: 256
I/sensors_hal_Ctx(  839): poll: released wakelock sensor_ind
D/sensors_hal_Util(  839): waitForResponse: timeout=0
D/LPWGController(  839): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  839): current mode = 1  value = 1 1
I/LPWGController(  839): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  839): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  839): set_light_backlight: 0
,I/SensorManager(  839): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  839): activate: handle is 46, disable
,V/sensors_hal_Ctx(  839): activate sensors is 1000000000000
D/sensors_hal_LP2(  839): enable: handle=46
D/sensors_hal_LP2(  839): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  839): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  839): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  839): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  839): Display changed displayId=0
,D/DSDPConnection( 1754): Display #0 changed.
,D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
D/SurfaceControl(  839): Excessive delay in setPowerMode(): 207ms
I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  839): Got set_interactive hint
D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1373): notifyScreenOffLocked
,D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1373): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
,D/WifiServerServiceExt(  839): sendKtScanInterval  mRtspPlay : false
,D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 839
,I/WifiServerServiceExt(  839): set CMD_KT_SCAN_INTERVAL
D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=on
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
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
D/GpsLocationProvider(  839): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1842): |CORE| sendScreenState: state:true
,I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
D/LNfcService( 1789): action : android.intent.action.SCREEN_ON
,D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1806): lockStatus = 0
I/LEDService( 1806): updateLightsLocked : turn off led
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1806): RESTART MSG
,D/NfcServiceNXP( 1789): mScreenState : 3, mInProvisionMode : false
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
D/SplitWindow(  839): check instance of lgWin Window{3653b116 u0 SearchPanel}
,D/Ulp_jni (  839): JNI:system_update. Event-0
,D/InputDispatcher(  839): Window went away: Window{17107101 u0 SearchPanel}
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,V/PhoneApp( 1754): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2681): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:7:56
,D/WeatherService( 2681): 2 : ACTION screen on
D/WeatherService( 2681): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2681): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2681): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:7:56
,W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): ACTION_SCREEN_ON
D/AppCleanupService( 4003): android.intent.action.SCREEN_ON
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 839
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
D/WifiController(  839): CMD_SCREEN_OFF 
D/WifiController(  839): shouldWifiStayAwake TRUE
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
,D/GpsLocationProvider(  839): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:false
,I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1806): clear
D/LNfcService( 1789): action : android.intent.action.SCREEN_OFF
I/Sensors (  423): sns_pwr.c(301):releasing wakelock
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1806): updateLightsLocked : turn on led
E/LEDService( 1806): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1806): Can't handle this request of patternId:0
D/LEDHandler( 1806): RESTART MSG
D/NfcServiceNXP( 1789): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1880): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1754): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2681): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:7:56
D/WeatherService( 2681): 2 : ACTION screen off
D/WeatherService( 2681): 2 : TimeTick Receiver Unregister
D/WeatherService( 2681): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:7:56
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): ACTION_SCREEN_OFF
D/AppCleanupService( 4003): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4003): AppUsageStatsSaveTask
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
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,E/NxpNfcJni( 1789): getReconnectState = 0x0
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=962986663, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{2e9b4a97 type 2 when 162842 com.android.systemui} when 162842
,D/PhoneUtils( 1754): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1754): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1754): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1754): getCallState : 0
,D/PhoneUtils( 1754): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1754): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1754): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=962986663 [*alarm*], flags=0x0
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 175697724257; DSPS: 5855298; Offset : -3002668704
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{30a2f484 type 2 when 183794 android} when 183794
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  479): init target 500000
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{3dfa846d type 2 when 188785 com.google.android.gms} when 188785
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1735): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 195698401127; DSPS: 6510680; Offset : -3002663167
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 215699140234; DSPS: 7166064; Offset : -3002656430
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 235699811997; DSPS: 7821446; Offset : -3002656055
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  479): init target 500000
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
,D/HeadsetStateMachine( 1988): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 255700699594; DSPS: 8476835; Offset : -3002653676
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 275701450784; DSPS: 9132220; Offset : -3002664982
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5467): --= Surplus to requirements =--
I/jxcore-log( 5467): 
I/jxcore-log( 5467): ****TEST TOOK:  ms ****
I/jxcore-log( 5467): 
I/jxcore-log( 5467): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5467): 
,D/AndroidRuntime( 8077): 
D/AndroidRuntime( 8077): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8077): CheckJNI is OFF
,D/AndroidRuntime( 8077): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  839): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  839): Killing 5467:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  839): WIN DEATH: Window{2fda5568 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  839): Focus left window: Window{2fda5568 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  839): Window went away: Window{2fda5568 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  839): Skipping PackageSetting{17c608fa com.example.hello/10317} due to missing metadata
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ActivityManager(  839):   Force finishing activity ActivityRecord{232edb9f u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  839): Display changed displayId=0
,D/DSDPConnection( 1754): Display #0 changed.
W/ActivityManager(  839): Spurious death for ProcessRecord{1151c8a2 5467:com.test.thalitest/u0a316}, curProc for 5467: null
,I/ActivityManager(  839): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
,D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1880): [Launcher.java:5203:onStart()]onStart
W/GeofencerStateMachine( 1735): Ignoring removeGeofence because network location is disabled.
,I/art     ( 1944): Explicit concurrent mark sweep GC freed 7095(408KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 10.881ms total 81.012ms
W/System.err( 3553): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3553): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3553): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3553): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3553): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3553): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 3553): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3553): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3553): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3553): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1880): [Launcher.java:776:onResume()]onResume
I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8111 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/art     ( 5490): Explicit concurrent mark sweep GC freed 13551(759KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 13MB/18MB, paused 921us total 171.470ms
I/[LGHome]LGActivityUtil( 1880): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1880): [Launcher.java:929:onResume()]onResume end
I/Activity( 1880): Activity.onPostResume() called 
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
,W/[LGHome]LGWallpaperInfo( 1880): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1880): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1373): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/SystemUI[Framework](  839): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
D/InputDispatcher(  839): Focus entered window: Window{a934b14 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  839): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  839): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  839): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2bf28e3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  839): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  839): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  839): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  839): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2bf28e3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 8111): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8111): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8111): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
I/art     (  839): Explicit concurrent mark sweep GC freed 35724(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 2.975ms total 283.080ms
I/art     (  839): WaitForGcToComplete blocked for 137.679ms for cause Explicit
,W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1880): [setNavigationBarColor] color=0x 0
,D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1373): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1373): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
D/KeyguardModel( 1373): handleShortcutListChanged...
D/KeyguardModel( 1373): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1373): createShortcutInfo...
,D/administrator(  839): Handling package changes for user 0
D/KeyguardModel( 1373): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1373): createShortcutInfo...
,W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1373): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1373): createShortcutInfo...
W/ResourceType( 1373): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1373): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1373): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1373): createShortcutInfo...
D/KeyguardModel( 1373): handleShortcutListChanged...
,I/LGEmail ( 8111): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8111): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/InputMethodManagerService(  839): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  839): Got RemoteException sending setActive(false) notification to pid 5467 uid 10316
,I/art     (  839): Explicit concurrent mark sweep GC freed 6626(364KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 6.648ms total 268.486ms
,I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  839): Timeline: Activity_windows_visible id: ActivityRecord{3dd8b8de u0 com.lge.launcher2/.Launcher t221} time:294634
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/IInputConnectionWrapper( 1880): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationService(  839): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
E/b       ( 1624): Unable to connect to the editor to retrieve text... will retry later
D/JobSchedulerService(  839): Receieved: android.intent.action.PACKAGE_REMOVED
I/PackageChangeReceiver( 8111): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/PhoneStatusBar( 1373): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1373): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
D/TaskPersister(  839): removeObsoleteFile: deleting file=222_task.xml
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1880): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1880): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/AppUp4:PreloadHelper( 7735): added Exclude : com.test.thalitest
D/AndroidRuntime( 8077): Shutting down VM
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
I/ActivityManager(  839): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8138 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  839): Killing 7697:com.google.android.talk/u0a61 (adj 15): empty #11
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
,W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1880): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_7697/cgroup.procs: No such file or directory
D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
,W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager( 8138): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8138): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 8138): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1880): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1880): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/SQLiteDatabase( 8138): Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
E/SQLiteDatabase( 8138): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8138): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8138): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8138): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8138): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8138): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8138): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 8138): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8138): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8138): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8138): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/SQLiteDatabase( 8138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 8138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 8138): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 8138): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 8138): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 8138): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 8138): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8138): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8138): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8138): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8138): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8138): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/AndroidRuntime( 8138): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 8138): FATAL EXCEPTION: main
E/AndroidRuntime( 8138): Process: com.android.settings, PID: 8138
E/AndroidRuntime( 8138): java.lang.RuntimeException: Unable to get provider com.android.settings.vibratecreation.VibrateUserPatternProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8138): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 8138): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 8138): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 8138): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 8138): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 8138): 	at android.os.Handler.disp,atchMessage(Handler.java:102)
E/AndroidRuntime( 8138): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8138): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 8138): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8138): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8138): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 8138): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 8138): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8138): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 8138): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 8138): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 8138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 8138): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8138): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 8138): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 8138): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 8138): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 8138): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 8138): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8138): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8138): 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
E/AndroidRuntime( 8138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 8138): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 8138): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 8138): 	... 11 more

```
