#### Test 583805004f2b042_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/AlertService( 3775): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 3775): No events found starting within 1 week.
,--------- beginning of system
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5326): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5326): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5326): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  870): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5388 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 3924:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10006/pid_3924/cgroup.procs: No such file or directory
I/art     ( 5326): CheckpointMarkThreadRoots callback created = 0xaaf2a210
V/JNIHelp ( 5326): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ResourcesManager( 5388): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     ( 5326): CheckpointMarkThreadRoots callback created = 0xb050fa60
W/art     ( 5326): Suspending all threads took: 8.143ms
W/System  ( 5326): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5326): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 5394): 
D/AndroidRuntime( 5394): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5394): CheckJNI is OFF
I/ActivityManager(  870): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5418 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/GservicesProvider( 5418): Gservices pushing to system: true; secure/global: true
I/ActivityManager(  870): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5447 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/GoogleHttpClient( 5418): GMS http client unavailable, use old client
I/GoogleHttpClient( 5418): GMS http client unavailable, use old client
I/ActivityManager(  870): Killing 5135:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/AndroidRuntime( 5394): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  870): failed to open /acct/uid_10014/pid_5135/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 146 ms] updated apps [took 145 ms] 
I/ActivityManager(  870): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  870): setTaskToReturnTo : TaskRecord{12d81d0f #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  870): setTaskToReturnTo : TaskRecord{12d81d0f #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  870): AppWindowTokenEx init.. 
D/ContextHelper(  870): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/SplitWindow(  870): check instance of lgWin Window{1ec4bb88 u0 Starting com.test.thalitest}
D/InputDispatcher(  870): Focus left window: Window{3c073ff5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5394): Shutting down VM
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
I/ActivityManager(  870): Killing 5156:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10021/pid_5156/cgroup.procs: No such file or directory
I/ActivityManager(  870): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5472 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1939): Closing mic
I/WindowStateAnimator(  870): Starting window displayed
I/SystemUI[Framework](  870): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
I/MicrophoneInputStream( 1939): mic_close com.google.android.apps.gsa.speech.audio.u@5f6ec3b
V/AudioRecord( 1939): stop()
D/AudioRecord( 1939): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  870): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  870): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  870): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  870): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1adedb60,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  870): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3c4e000
D/BarTransitions( 1371): draw background and invalidate : color = f000000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
D/BarTransitions( 1371): draw background and invalidate : color = 11111111
V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  282): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  282): disable_audio_route: exit
E/audio_hw_primary(  282): disable_snd_device: enter 144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): disable_snd_device: snd_device(144: lg-vr-handset-mic)
,V/audio_hw_primary(  282): stop_input_stream: exit: status(0)
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
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb3c4e000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{c7a24a3 type 2 when 79955 android} when 79955
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  870): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1739): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem( 1983): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioSystem( 3167): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2744): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread 0xb3c4e000 exiting
V/AudioSystem( 1371): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1939): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioFlinger(  282): releasing 16 from 1939 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  282): removeClient_l() pid 1939, calling pid 282
I/HotwordRecognitionRnr( 1939): Hotword detection finished
I/HotwordRecognitionRnr( 1939): Stopping hotword detection.
D/ContextHelper( 5472): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/Finsky  ( 5447): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/WebViewFactory( 5472): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5472): Time to load native libraries: 5 ms (timestamps 189-194)
I/LibraryLoader( 5472): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5472): Binding Chromium to main looper Looper (main, tid 1) {202bd6ec}
I/LibraryLoader( 5472): Expected native library version number "",actual native library version number ""
I/chromium( 5472): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/Finsky  ( 5447): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/BrowserStartupController( 5472): Initializing chromium process, singleProcess=true
W/art     ( 5472): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5472): ApplicationContext is null in ApplicationStatus
W/Settings( 5447): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5447): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/chromium( 5472): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/NotificationManager( 5447): com.android.vending: cancel(-1050172287) by com.android.vending
E/libEGL  ( 5472): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5472): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5472): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5472): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5472): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5472): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5472): Remote Branch: 
I/Adreno-EGL( 5472): Local Patches: 
I/Adreno-EGL( 5472): Reconstruct Branch: 
V/DownloadManager( 3236): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@2500244d on behalf of 5447
I/NotificationManager( 5447): com.android.vending: cancel(1003285959) by com.android.vending
D/Finsky  ( 5447): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5447): [1] Libraries$2.run: Finished loading 1 libraries.
V/AudioPolicyService(  282): registerClient() client 0xb3c3afc0, uid 10316
D/BluetoothManagerService(  870): Message: 20
D/BluetoothManagerService(  870): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@167fec91:true
D/Ads     ( 5447): Skipping gmscore version check
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
I/ActivityManager(  870): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5541 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 24.480ms
D/Finsky  ( 5447): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 317us total 22.223ms
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 22.333ms
D/Finsky  ( 5447): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5447): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ResourcesManager( 5541): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5541): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5541): VM with version 2.1.0 has multidex support
,I/MultiDex( 5541): install
I/MultiDex( 5541): VM has multidex support, MultiDex support library is disabled.
W/art     ( 5472): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5472): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5472): CordovaWebView is running on device made by: LGE
,W/art     ( 5472): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5472): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 5472): Activity.onPostResume() called 
,D/OpenGLRenderer( 5472): Render dirty regions requested: true
I/OpenGLRenderer( 5472): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5472): Enabling debug mode 0
D/Atlas   ( 5472): Validating map...
,D/SplitWindow(  870): check instance of lgWin Window{240e287e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5472): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  870): Killing 5183:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10009/pid_5183/cgroup.procs: No such file or directory
,V/JNIHelp ( 5541): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/InputDispatcher(  870): Focus entered window: Window{240e287e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/ActivityThread( 5541): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5541): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3392e844: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5541): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5541): com.google.android.gms: cancel(10436) by com.google.android.gms
W/InputMethodManagerService(  870): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/NotificationManager( 5541): com.google.android.gms: cancel(39789) by com.google.android.gms
I/ActivityManager(  870): Displayed com.test.thalitest/.MainActivity: +1s162ms
I/Timeline(  870): Timeline: Activity_windows_visible id: ActivityRecord{2779219c u0 com.test.thalitest/.MainActivity t222} time:80919
I/Timeline( 5472): Timeline: Activity_idle id: android.os.BinderProxy@3c35faab time:80941
,D/ChimeraCfgMgr( 5541): Reading stored module config
,D/PackageBroadcastService( 5541): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,W/BindingManager( 5472): Cannot call determinedVisibility() - never saw a connection for the pid: 5472
,D/ChimeraCfgMgr( 5541): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5541): Loading module APK com.google.android.play.games
,D/JsMessageQueue( 5472): Set native->JS mode to OnlineEventsBridgeMode
,I/art     ( 5541): CheckpointMarkThreadRoots callback created = 0xb046c7d0
,D/NativeLibraryUtils( 5541): Install completed successfully. count=14 extracted=0
I/art     ( 5541): CheckpointMarkThreadRoots callback created = 0xb046c7b0
,D/ChimeraCfgMgr( 5541): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5541): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 5541): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5541): Submit a task: k
,D/ChimeraCfgMgr( 5541): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5541): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/PeopleDatabaseHelper( 5541): cleanUpNonGplusAccounts done.
,I/Icing   ( 5541): Storage manager: low false usage 1.77MB avail 2.38GB capacity 4.06GB
,D/k       ( 5541): Processing package: com.test.thalitest
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/GassUtils( 5541): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5541): Found info for package com.test.thalitest in db.
,D/LocationInitializer( 5541): Restart initialization of location
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
W/BaseAppContext( 5541): Using Auth Proxy for data requests.
,D/jxcore_app_log( 5472): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426160128
,I/ActivityManager(  870): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5605 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5541): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5541): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/BaseAppContext( 5541): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/chromium( 5472): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
W/BaseAppContext( 5541): Using Auth Proxy for data requests.
,W/BaseAppContext( 5541): Using Auth Proxy for data requests.
,W/BaseAppContext( 5541): Using Auth Proxy for data requests.
,W/BaseAppContext( 5541): Using Auth Proxy for data requests.
W/BaseAppContext( 5541): Using Auth Proxy for data requests.
I/art     ( 5472): CheckpointMarkThreadRoots callback created = 0x9c21b530
,W/BaseAppContext( 5541): Using Auth Proxy for data requests.
,I/art     ( 5472): CheckpointMarkThreadRoots callback created = 0x9c21b500
W/IcingInternalCorpora( 5541): getNumBytesRead when not calculated.
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     ( 5541): Background sticky concurrent mark sweep GC freed 15987(1446KB) AllocSpace objects, 14(224KB) LOS objects, 11% free, 12MB/14MB, paused 5.745ms total 89.721ms
,I/Gmail   ( 5605): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5605): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  870): Process com.android.contacts (pid 5253) has died
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/art     (  870): Explicit concurrent mark sweep GC freed 26283(1297KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 5.156ms total 243.682ms
W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5605): Error finding the version of the Email provider.....
E/Gmail   ( 5605): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5605): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5605): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5605): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5605): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5605): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5605): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5605): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5605): We do not support migrating this version of the Email provider.
I/Gmail   ( 5605): getAccountsCursor
,D/ChimeraCfgMgr( 5541): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5541): Module APK com.google.android.play.games already loaded
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  870): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5605): Observing account changes for notifications
,I/ActivityManager(  870): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5663 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5541): updateResources: need to parse f{com.google.android.gms}
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/Gmail   ( 5605): notifyAccountChanged
,D/PhoneMonitor( 5663): Register our PhoneStateListener
I/Gmail   ( 5605): getAccountsCursor
I/Gmail   ( 5605): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5605): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  870): Killing 5209:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Gmail   ( 5605): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5605): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PhoneMonitor( 5663): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5663): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 5663): [parse] Load xml
V/TelephonyAutoProfiling( 5663): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5663): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_5209/cgroup.procs: No such file or directory
,D/PhoneMonitor( 5663): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/Icing   ( 5541): Internal init done: storage state 0
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Icing   ( 5541): Post-init done
I/CheckinService( 5541): Checkin interval check for package: unspecified last checkin: 1455035742939 min interval config: 0 actual interval: 6408
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
I/CheckinService( 5541): Disabling old GoogleServicesFramework version
I/NotificationManager( 5541): com.google.android.gms: cancel(10436) by com.google.android.gms
I/art     ( 5418): Explicit concurrent mark sweep GC freed 8060(404KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 6.360ms total 115.409ms
,W/art     ( 5541): Suspending all threads took: 14.165ms
,V/DownloadManager( 3236): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@2cad1b02 on behalf of 5541
I/art     ( 5541): Background sticky concurrent mark sweep GC freed 8286(676KB) AllocSpace objects, 14(224KB) LOS objects, 4% free, 13MB/14MB, paused 27.091ms total 94.104ms
W/InstanceID/Rpc( 5541): Found 10006
,W/InstanceID/Rpc( 5541): Found 10006
I/Gmail   ( 5605): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 5541): Background sticky concurrent mark sweep GC freed 3656(242KB) AllocSpace objects, 2(32KB) LOS objects, 3% free, 13MB/14MB, paused 6.558ms total 96.102ms
,I/CheckinService( 5541): Checking schedule, now: 1455035749684 next: 1455035772887
,I/CheckinService( 5541): active receiver: disabled
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  870): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5702 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/DownloadManager( 3236): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@297b4c13 on behalf of 5541
V/DownloadManager( 3236): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@245f5e50 on behalf of 5541
,W/jxcore-log( 5472): Initializing JXcore engine
W/jxcore-log( 5472): JXcore engine is ready
,W/ResourcesManager( 5702): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Thread-676( 5604): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5348]" dev="sockfs" ino=5348 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-676( 5604): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-676( 5604): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5471]" dev="sockfs" ino=5471 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-676( 5604): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-676( 5604): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-676( 5604): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[24418]" dev="sockfs" ino=24418 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5472): Starting JXcore engine
,I/Babel_SMS( 5702): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5702): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5702): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5702): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5702): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5702): MmsConfig.loadFromResources
E/Babel_SMS( 5702): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5702): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/jxcore-log( 5472): Platform android
W/jxcore-log( 5472): 
W/jxcore-log( 5472): Process ARCH arm
W/jxcore-log( 5472): 
D/SensorManager( 5702): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5702): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5702): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 5702): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5702): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5702): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5702): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5702): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5702): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5702): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5702): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5702): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5702): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5702): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5702): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5702): found sensor: Motion Accel, handle=46
W/Settings( 5702): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5702): startup - clean
I/art     ( 5702): CheckpointMarkThreadRoots callback created = 0xb042d480
,I/Babel   ( 5702): deleted: false for 0
,I/art     ( 5702): CheckpointMarkThreadRoots callback created = 0xb042d450
,W/art     ( 5702): Suspending all threads took: 31.118ms
,W/AudioCapabilities( 5702): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5702): Unsupported mime audio/adpcm
W/AudioCapabilities( 5702): Unsupported mime audio/g726
W/AudioCapabilities( 5702): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5702): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5702): Unsupported mime video/mjpg
W/VideoCapabilities( 5702): Unsupported mime video/theora
W/AudioCapabilities( 5702): Unsupported mime audio/evrc
,W/AudioCapabilities( 5702): Unsupported mime audio/qcelp
W/VideoCapabilities( 5702): Unrecognized profile 2130706433 for video/avc
D/InitAlarmsService( 3775): Clearing and rescheduling alarms.
W/AudioCapabilities( 5702): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5702): Unsupported mime audio/qcelp
W/AudioCapabilities( 5702): Unsupported mime audio/evrc
,W/VideoCapabilities( 5702): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5702): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5702): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5702): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  870): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5729 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/VideoCapabilities( 5702): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5702): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5702): onServiceConnected
W/Babel   ( 5702): Attempted to change video mute state without an active call.
W/ResourcesManager( 5729): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5729): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@37563843
,D/CalendarProvider2( 5729): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5729): Created com.android.providers.calendar.CalendarAlarmManager@202bd6ec(com.android.providers.calendar.CalendarProvider2@37563843)
D/CalendarProvider2( 5729): Scheduling check of next Alarm
,D/CalendarProvider2( 5729): SCHEDULE_ALARM_REMOVE
I/NotificationManager( 5702): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  870): Killing 3775:com.android.calendar/u0a13 (adj 15): empty #11
,W/ResourcesManager( 5702): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5702): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Icing   ( 5541): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,W/libprocessgroup(  870): failed to open /acct/uid_10013/pid_3775/cgroup.procs: No such file or directory
,I/ActivityManager(  870): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5755 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  870): RTC_WAKEUP set : Alarm{3b277005 type 0 when 1455035731334 com.google.android.gms} when 1455035731334
V/AlarmManager(  870): RTC_WAKEUP set : Alarm{3d960a8b type 0 when 1455035750828 com.google.android.googlequicksearchbox} when 1455035750828
,I/AudioManager( 5031): getMode name:com.lge.qremote
D/Icing   ( 5541): Loaded CLD2 Version V2.0 - 20141016
,I/AudioManager( 5031): getMode name:com.lge.qremote
I/jxcore-log( 5472): JXcore Cordova bridge is ready!
I/jxcore-log( 5472): 
W/jxcore-log( 5472): JXcore engine is started
,I/AudioManager( 5031): getMode name:com.lge.qremote
,V/JNIHelp ( 5702): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/UEI.SmartControl( 5755): Quickset Services start...
I/UEI.SmartControl( 5755): Manufacture = LGE
,D/UEI.SmartControl( 5755): File observer start...
E/UEI.SmartControl( 5755): IR Port is disabled: false
D/UEI.SmartControl( 5755): Starting file observer...
D/UEI.SmartControl( 5755): Extracting JNI libs...
D/UEI.SmartControl( 5755): --- this system supports 32-bit or 64-bit only
I/AudioManager( 5031): getMode name:com.lge.qremote
I/Icing   ( 5541): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/AudioManager( 5031): getMode name:com.lge.qremote
,E/MDM     ( 1732): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5541): Restart initialization of location
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5031): getMode name:com.lge.qremote
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
W/System  ( 5702): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5702): Installed default security provider GmsCore_OpenSSL
I/AudioManager( 5031): getMode name:com.lge.qremote
,I/AudioManager( 5031): getMode name:com.lge.qremote
,I/NotificationManager( 5702): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5786 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/jxcore-log( 5472): Toggling radios to true
I/jxcore-log( 5472): 
,D/UEI.SmartControl( 5755): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5755): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5755): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/BluetoothAdapter( 5472): enable(): BT is already enabled..!
,D/WifiServiceImplEx(  870): setWifiEnabled: true pid=5472, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  870): setWifiEnabled: true pid=5472, uid=10316
,D/WifiServiceImplEx(  870): disconnect pid=5472, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  870): reconnect pid=5472, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5472): Radios toggled
I/jxcore-log( 5472): 
I/jxcore-log( 5472): My device name is: LGE-LG-D722
I/jxcore-log( 5472): 
,I/UEI.SmartControl( 5755): --- Selecting new region: 2
I/UEI.SmartControl( 5755): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5755): Platform has CIR...
D/UEI.SmartControl( 5755): NO CIR support, need to check package...
I/UEI.SmartControl( 5755): Model: LG-D722 uses JNI
I/wpa_supplicant( 2803): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,D/UEI.SmartControl( 5755): QS Service created
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
E/WifiStateMachine(  870): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2803): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/WfdsMonitor( 1801): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  870): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,E/UEI.SmartControl( 5755): QS start get config
I/AppUp4:AppBoxCP( 5786): onCreate
,W/AppUp4:DB( 5786):  [AppBoxDatabaseHelper] construct
,D/LGWifiP2pService(  870): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,I/AppUp4:DB( 5786):  setFingerPrint start
D/DhcpStateMachine(  870): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/AppUp4:DB( 5786):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/CommandListener(  270): Clearing all IP addresses on wlan0
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 7
D/UEI.SmartControl( 5755): Loading JNI Libs...
,D/UEI.SmartControl( 5755):  configuring local db...
I/AppUp4:DB( 5786):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5786):  SDK version = 0
I/AppUp4:DB( 5786):  beforefinger == newfinger no write in DB
,V/NativeCrypto( 1732): Read error: ssl=0xb044e000: I/O error during system call, Connection timed out
V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xb044e000: I/O error during system call, Broken pipe
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 7
D/ConnectivityService(  870): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  870): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  870): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): ValidatedState{ when=-4ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): DefaultState{ when=-9ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): Forcing reevaluation
,D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/ActivityManager(  870): Process com.google.android.apps.docs (pid 5326) has died
,D/AppUp4:AppBoxApplication( 5786): AppBoxApplication onCreate()
D/WifiHS20(  870): hidePasspointNotification off =false
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine(  870): Start Disconnecting Watchdog 1
D/WifiHS20(  870): hidePasspointNotification off =false
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:51.489 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:51.49 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LGWifiP2pService(  870): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2803): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/CommandListener(  270): Clearing all IP addresses on wlan0
,D/ConnectivityService(  870): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  870): disableDataServiceNotify
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  870): hidePasspointNotification off =false
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:51.516 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNetworkAgent(  870): NetworkAgent: NetworkAgent channel lost
D/DSQN    (  870): stop dsqn bin
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/AppUp4:CustModeStarterReceiver( 5786): onReceive
I/AppUp4:CustModeStarterReceiver( 5786): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/WifiHS20(  870): hidePasspointNotification off =false
,W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:51.542 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:51.544 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateSCANNING
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
D/AppUp4:CustFacade( 5786): Context : android.app.ReceiverRestrictedContext@1102233e
D/AppUp4:CustFacade( 5786): isCustomizationCompleted : false
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,D/AppUp4:CustFacade( 5786): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5786): begin check event
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/AppUp4:CustModeStarterReceiver( 5786): Event For Nothing, skip.
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
,D/ConnectivityService(  870): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/DhcpStateMachine(  870): StoppedState
D/DhcpStateMachine(  870): StoppedState{ when=-126ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  870): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): Disconnected - quitting
,D/Nat464Xlat(  870): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524292
D/CSLegacyTypeTracker(  870): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  870): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  870): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  870): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1838): |CORE| No family connected
D/ConnectivityService(  870): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  870): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  870): [LG_RESTRICTED] !!!isConnected  type  :1
D/WIFI    (  870): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  870):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/Tethering(  870): MasterInitialState.processMessage what=3
D/Tethering(  870): MasterInitialState.processMessage what=3
,D/NetworkManagementService(  870): Removing idletimer
D/TelephonyNetworkFactory-1( 1739): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1739):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
W/Settings(  870): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  870): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = -1
I/CalendarProvider2( 5729): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
,W/ContentResolver( 5729): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  870): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5810 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  870): Killing 5272:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/UEI.SmartControl( 5755):  ---- Has DB8: true
D/UEI.SmartControl( 5755): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5755): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5755): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5755): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5755): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5755): IrrcClient ++ 
D/irrcClient( 5755): getIrrcService ++ 
,D/irrcClient( 5755): getIrrcService -- 
D/irrcClient( 5755): IrrcClient -- 
W/irrc_jni( 5755): IRRCPlayer_nativeInit -- 
I/UEI.SmartControl( 5755): Device manager: loading config....
,D/UEI.SmartControl( 5755): Services init done
D/UEI.SmartControl( 5755): Config is loaded...
D/UEI.SmartControl( 5755):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5755): Notify AllClients services are ready: 0
,W/libprocessgroup(  870): failed to open /acct/uid_10069/pid_5272/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5755): QS Service init finished
D/UEI.SmartControl( 5755): QS Service version name: 0.1.73
,D/UEI.SmartControl( 5755): QS Service version code: 1073
D/UEI.SmartControl( 5755): Service requested: Control
D/UEI.SmartControl( 5755): Internal service binding...
D/UEI.SmartControl( 5755): -----IControl: 11
D/UEI.SmartControl( 5755): Caller: com.lge.qremote
D/UEI.SmartControl( 5755): ------------ IControl registerCallback...
I/UEI.SmartControl( 5755): Registering callback...
D/UEI.SmartControl( 5755): -----IControl: 19
,D/UEI.SmartControl( 5755): Caller: com.lge.qremote
I/UEI.SmartControl( 5755): Registering Services Ready callback...
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/UEI.SmartControl( 5755): Notify client services are ready...
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 5755): -----IControl: 8
D/UEI.SmartControl( 5755): Caller: com.lge.qremote
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  870): Killing 5309:com.lge.bnr/1000 (adj 15): empty #11
,W/ResourcesManager( 5810): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5810): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5810): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5810): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5810): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  870): Killing 5292:com.lge.eula/1000 (adj 15): empty #12
,W/libprocessgroup(  870): failed to open /acct/uid_1000/pid_5309/cgroup.procs: No such file or directory
,W/libprocessgroup(  870): failed to open /acct/uid_1000/pid_5292/cgroup.procs: No such file or directory
I/art     (  870): Explicit concurrent mark sweep GC freed 36992(1724KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.081ms total 162.250ms
,I/SystemConfig( 5810): BUILD Country: EU
I/SystemConfig( 5810): BUILD Operator: OPEN
,I/ActivityManager(  870): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5838 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 5388:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10086/pid_5388/cgroup.procs: No such file or directory
,I/SystemConfig( 5810): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5810): existFile = false
I/SystemConfig( 5810): canReadFile = false
I/SystemConfig( 5810): systemFeature RCS result false
D/SystemConfig( 5810): refreshRcsSupport() :false
,I/LockScreenSettings( 5838): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5838): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5838): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5838): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5838): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5838): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  870): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5855 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 5447:com.android.vending/u0a36 (adj 15): empty #11
,I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
,W/libprocessgroup(  870): failed to open /acct/uid_10036/pid_5447/cgroup.procs: No such file or directory
I/wpa_supplicant( 2803): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/LocSvc_java(  870): onReceive
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:52.679 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/wpa_supplicant( 2803): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:52.709 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateASSOCIATED
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:52.725 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateFOUR_WAY_HANDSHAKE
I/wpa_supplicant( 2803): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2803): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:52.734 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/WifiServiceExtension(  870): setVHTCapabilityType  : false
,I/WifiServerServiceExt(  870): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  870): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  870): setSecurityType  : 2
,W/ResourcesManager( 5855): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:52.798 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:52.804 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,D/ConnectivityService(  870): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  870): Got NetworkAgent Messenger
D/ConnectivityService(  870): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  870): NetworkAgent connected
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
E/WifiConfigStore(  870): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
E/WifiConfigStore(  870): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  270): Setting iface cfg
E/WifiStateMachine(  870): Start Dhcp Watchdog 2
D/DhcpStateMachine(  870): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  870): WaitBeforeStartState
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  870): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  870): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  870): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a61bac8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a61bac8 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  870): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  870): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  870): DHCP Start wake lock is acquired.
D/CommandListener(  270): Setting iface cfg
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  270): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  870): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateCOMPLETED
D/ConnectivityService(  870): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  870): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  870): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  870): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  870): ignoring duplicate network state non-change
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:52.964 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:52.971 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  870): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  870): Adding iface wlan0 to network 101
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/WifiStateMachine(  870): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,E/ConnectivityService(  870): Unexpected mtu value: 0, wlan0
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
D/ConnectivityService(  870): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  870): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  270): netlink response contains error (File exists)
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:53.005 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/InputReader(  870): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  870): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  870): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  870): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  870): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:53.015 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,D/Nat464Xlat(  870): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  870): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  870):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  870):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  870):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  870): currentScore = 0, newScore = 20
D/ConnectivityService(  870):    accepting network in place of null
D/ConnectivityService(  870): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI    (  870): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  870):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  870): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  870): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  870): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  870): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  870): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  870): validation of new default Network = false
D/ConnectivityService(  870): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  870): enableDataServiceNotify 
D/DSQN    (  870): start dsqn bin
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = 1
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): [LWD] Start DNSResolver start to wait
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/ConnectivityService(  870): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  870): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): [LWD] wait 500ms before dns check
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 2
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/DSQN    ( 5890): DSQN samuel.seo ver 141203
E/DSQN    ( 5890): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5890): created command queue thread
I/DSQN    ( 5890): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5890): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/CheckinService( 5541): Checkin interval check for package: unspecified last checkin: 1455035742939 min interval config: 0 actual interval: 10152
D/TelephonyNetworkFactory-1( 1739): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1739):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
V/NetworkPolicy(  870): [LG_RESTRICTED] checkMobilePolicy_type()
I/CheckinService( 5541): Checking schedule, now: 1455035753106 next: 1455035772887
I/CheckinService( 5541): active receiver: disabled
,D/administrator(  870): Handling package changes for user 0
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/DhcpStateMachine(  870): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  870): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  870): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5894): version 5.5.6 starting
,E/dhcpcd  ( 5894): get_duid: Read-only file system
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/dhcpcd  ( 5894): wlan0: rebinding lease of 192.168.1.134
,I/ActivityManager(  870): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5907 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  870): Killing 5605:com.google.android.gm/u0a53 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 150 ms] updated apps [took 150 ms] 
,W/libprocessgroup(  870): failed to open /acct/uid_10053/pid_5605/cgroup.procs: No such file or directory
,I/NotificationService(  870): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  870): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  870): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  870): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/WifiHS20(  870): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  870): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/Tethering(  870): MasterInitialState.processMessage what=3
V/BackupManagerService(  870): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  870): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@227ec3a3
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): [LWD] DNSResolver start dns
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  270): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
W/ResourcesManager(  870): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  870): Process com.google.process.gapps (pid 5418) has died
,D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out(  870): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): [LWD] DNSResolver end dns
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 5890): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5890): restart monitoring
,I/DSQN    ( 5890): dsqn report finish
D/LGDataListener(  270): argv[0]=dsqncommand
D/LGDataListener(  270): argv[1]=wlan0
D/LGDataListener(  270): argv[2]=1
D/LGDataListener(  270): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  870): DSQM DsqnNotification wlan0  1
D/DSQN    (  870): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 16:35:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455035753676], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455035753650]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1801): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): Validated
D/ConnectivityService(  870): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  870):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  870):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  870): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  870): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  870): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  870): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1739): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1739):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  870): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    (  870):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/ResourceType(  870): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  870): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5927 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/WifiDataContinuityService(  870): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{1a17c6f7 type 2 when 87798 com.google.android.gms} when 87798
I/WifiServerServiceExt(  870): set CMD_CAPTIVE_CHECK_COMPLETED
I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.636ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 20.781ms
,D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 29.064ms
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/ActivityManager(  870): Process com.lge.qremote (pid 5031) has died
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/GservicesProvider( 5927): Gservices pushing to system: true; secure/global: true
,I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  870): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:54.029 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  870): identical MTU - not setting
D/Nat464Xlat(  870): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  870): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  870): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524295
D/ConnectivityService(  870): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  870): enableDataServiceNotify 
D/DSQN    (  870): start dsqn bin
,I/GoogleHttpClient( 5927): GMS http client unavailable, use old client
,D/DSQN    (  870): dsqn is running restart
D/ConnectivityService(  870): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/DSQN    ( 5948): DSQN samuel.seo ver 141203
E/DSQN    ( 5948): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5948): created command queue thread
I/DSQN    ( 5948): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5948): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/GoogleHttpClient( 5927): GMS http client unavailable, use old client
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
D/LocationProviderProxy(  870): applying state to connected service
,D/Finsky  ( 5907): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5907): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5907): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5907): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 5907): com.android.vending: cancel(-1050172287) by com.android.vending
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/dhcpcd  ( 5894): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5894): wlan0: leased 192.168.1.134 for 86400 seconds
,D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  870): Process com.uei.lg.quicksetsdk.lite (pid 5755) has died
D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  870): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  870): onReceive
D/LocSvc_java(  870): got connectivity action
,D/LocSvc_java(  870): broadcast - no network connections
D/LocSvc_java(  870): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  870): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  870): onReceive
D/LocSvc_java(  870): got connectivity action
D/LocSvc_java(  870): broadcast - no network connections
D/LocSvc_java(  870): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  870): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  870): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  870): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  870): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  870): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  870): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  870): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  870): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  870): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  870): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ProcessCpuTracker(  870): Skipping unknown process pid 5990
V/DownloadManager( 3236): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@d37b849 on behalf of 5907
D/Ads     ( 5907): Skipping gmscore version check
D/Finsky  ( 5907): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5907): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5907): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 5541): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5541): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5541): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 5907): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/SetupWizard( 5663): Connected to Gservices successfully
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  870): DHCPV4 succeeded on wlan0
E/BandwidthController(  270): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  270): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/LgDhcpStateMachineHelper(  870): CheckDhcpDirectory [Lease File Count] : 3
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
V/LgDhcpStateMachineHelper(  870): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  870): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  870): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  870): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  870): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  870): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  870): RunningState
D/LocationInitializer( 5541): Restart initialization of location
,E/MDM     ( 1732): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  870): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6021 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
I/ActivityManager(  870): Process com.android.gallery3d (pid 5226) has died
,D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
,I/DSQN    ( 5948): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5948): restart monitoring
D/LGDataListener(  270): argv[0]=dsqncommand
D/LGDataListener(  270): argv[1]=wlan0
D/LGDataListener(  270): argv[2]=1
D/LGDataListener(  270): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  870): DSQM DsqnNotification wlan0  1
D/DSQN    (  870): start to monitor internet connection
,I/DSQN    ( 5948): dsqn report finish
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6021): getAccountsCursor
,W/GAV2    ( 6021): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6021): Error finding the version of the Email provider.....
E/Gmail   ( 6021): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6021): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6021): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6021): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6021): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6021): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6021): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6021): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6021): We do not support migrating this version of the Email provider.
I/art     ( 1732): Explicit concurrent mark sweep GC freed 29637(1834KB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 13MB/22MB, paused 1.418ms total 116.146ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  870): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 6021): Observing account changes for notifications
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6021): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{38c14e78 type 2 when 89730 com.android.providers.calendar} when 89730
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  870): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6066 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  870): Explicit concurrent mark sweep GC freed 68688(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.235ms total 174.529ms
,I/Gmail   ( 6021): notifyAccountChanged
I/Gmail   ( 6021): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6021): getAccountsCursor
I/Gmail   ( 6021): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/EventLogService( 5541): Aggregate from 1455035734690 (log), 1455033931164 (data)
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6021): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6021): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:35:55.866 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Gmail   ( 6021): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1939): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ResourcesManager( 6066): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6066): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6066): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/ActivityManager(  870): Process com.android.contacts (pid 5810) has died
W/ResourcesManager( 6066): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6066): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  870): onReceive
D/LocSvc_java(  870): got connectivity action
D/LocSvc_java(  870): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  870): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  870): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  870): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  870): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  870): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  870): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Icing   ( 5541): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/IndexDatabaseHelper( 6066): Using schema version: 115
,I/IndexDatabaseHelper( 6066): Index is fine
,I/Icing   ( 5541): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
V/WifiInternetCheck(  870): Single check msg out of sync, ignoring.
,I/ActivityManager(  870): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6094 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6094): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6094): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6094): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  870): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6114 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  870): Killing 5729:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10014/pid_5729/cgroup.procs: No such file or directory
,W/ResourcesManager( 6114): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  870): Message: 20
D/BluetoothManagerService(  870): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7d299ec:true
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
I/PCSuite ( 6094): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6094): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6094): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
,I/PCSuite ( 6094): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6094): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6094): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
I/PCSuite ( 6094): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6094): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6094): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
I/ActivityManager(  870): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6144 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6144): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6144): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6144): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6144): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@47777f9, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1102233e, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@249a159f, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@202bd6ec, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@34ae9ab5, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3e79354a, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@9146cbb, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2a7575d8, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1afb2d31, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@299d5c16, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@39131997, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@b81784, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@19a46b6d, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@70b23a2, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@15e5b833, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3b6127f0, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@36295169, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@69bd7ee, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3c39a48f, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@a48d31c, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@34fc9b25, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2a7184fa, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3c35faab, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@209e0508, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3500c4a1, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2c2f6c6, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@37579687, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@339269b4, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@6c409dd, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1a67b952, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@d1423, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@37c66d20, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3b7c66d9, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2024189e, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1712cf7f, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@9753b4c, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@27c39795, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@18b520aa, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@228ee49b, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2b60c038, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@16131811, lg_preferences_recent_t,imezones=com.android.calendar.adaptation.PreferenceKey$KeyData@259c9d76, l
,D/GeneralPreferenceUtils( 6144): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6144): [init]
,I/Config  ( 6144): LGCalendar ver.4.40.17
I/Config  ( 6144): start check model
I/Config  ( 6144): start check native_ca
I/Config  ( 6144): Config Operator=OPEN, Country=EU
D/Config  ( 6144): [setDefaultValuesToPref]
D/Config  ( 6144): [parseProfiles]
D/ProfilesParser( 6144): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6144): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6144): [updateProfiletoCountryInfo]
D/GeneralPreference( 6144): [checkAndMigrateOldPreference]
D/AlertReceiver( 6144): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6144): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6144): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6144): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6144): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6144): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6144): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6144): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6144): onHandleIntent
,D/HolidayDataLoader( 6144): readJsonAsset : holiday.json
E/AgendaWidgetManager( 6144): [updateWidgets] 
D/AlertService( 6144): 0 Action = android.intent.action.PROVIDER_CHANGED
D/MonthWidgetProvider( 6144): [onReceive]
D/CalendarWidgetProvider( 6144): [onReceive]
D/CalendarWidgetProvider( 6144): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,D/CalendarTypeController( 6144): [onCreate] mContext.getPackageName() = com.android.calendar
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,D/WeekWidgetProvider( 6144): [onReceive]
D/CalendarWidgetProvider( 6144): [onReceive]
D/CalendarWidgetProvider( 6144): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6144): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6144): onHandleIntent:holiday data empty
,I/ActivityManager(  870): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6171 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6114): Create singleton instance
,D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  270): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
I/AudioManager( 6114): getMode name:com.lge.qremote
,V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6066): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
,I/System.out(  870): propertyValue:false
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  270): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out(  870): propertyValue:false
V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
D/UEI.SmartControl( 6171): Quickset Services start...
I/UEI.SmartControl( 6171): Manufacture = LGE
V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/UEI.SmartControl( 6171): File observer start...
E/UEI.SmartControl( 6171): IR Port is disabled: false
D/UEI.SmartControl( 6171): Starting file observer...
D/UEI.SmartControl( 6171): Extracting JNI libs...
D/UEI.SmartControl( 6171): --- this system supports 32-bit or 64-bit only
D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
,V/WifiInternetCheck(  870): isHttpConnectionAvailable - We got a valid response : 204
V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/UEI.SmartControl( 6171): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
D/UEI.SmartControl( 6171): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6171): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
I/UEI.SmartControl( 6171): --- Selecting new region: 2
I/UEI.SmartControl( 6171): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6171): Platform has CIR...
D/UEI.SmartControl( 6171): NO CIR support, need to check package...
I/AppUp4:CustModeStarterReceiver( 5786): onReceive
I/AppUp4:CustModeStarterReceiver( 5786): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5786): Context : android.app.ReceiverRestrictedContext@1102233e
D/AppUp4:CustFacade( 5786): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5786): isSimDevice : true
I/NotificationManager( 5702): com.google.android.talk: cancel(8) by com.google.android.talk
,D/AppUp4:CustModeStarterReceiver( 5786): begin check event
I/AppUp4:CustModeStarterReceiver( 5786): Event For Nothing, skip.
I/UEI.SmartControl( 6171): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6171): QS Service created
W/ResourcesManager( 5702): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5702): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  870): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6204 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,E/UEI.SmartControl( 6171): QS start get config
,W/ResourcesManager( 6204): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6204): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6204): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6171): Loading JNI Libs...
,D/UEI.SmartControl( 6171):  configuring local db...
I/AppConfig( 6204): Total System Memory = 906309632
,I/GalleryUtils( 6204): Application Heap = 96 MB
I/AppConfig( 6204): App Tier : NOT_DEF
,D/SystemHelper( 6204): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  870): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6223 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/UEI.SmartControl( 6171):  ---- Has DB8: true
D/UEI.SmartControl( 6171): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6171): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6171): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6171): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6171): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6171): IrrcClient ++ 
D/irrcClient( 6171): getIrrcService ++ 
,D/irrcClient( 6171): getIrrcService -- 
D/irrcClient( 6171): IrrcClient -- 
W/irrc_jni( 6171): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6171): Services init done
I/UEI.SmartControl( 6171): Device manager: loading config....
,D/UEI.SmartControl( 6171): QS Service init finished
D/UEI.SmartControl( 6171): QS Service version name: 0.1.73
D/UEI.SmartControl( 6171): QS Service version code: 1073
D/UEI.SmartControl( 6171): Service requested: Control
D/UEI.SmartControl( 6171): Config is loaded...
,D/UEI.SmartControl( 6171):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6171): Notify AllClients services are ready: 0
,W/ResourcesManager( 6223): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6223): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6223): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6223): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6223): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6171): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6171): Internal service binding...
D/UEI.SmartControl( 6171): -----IControl: 11
,D/UEI.SmartControl( 6171): Caller: com.lge.qremote
D/UEI.SmartControl( 6171): ------------ IControl registerCallback...
I/UEI.SmartControl( 6171): Registering callback...
D/UEI.SmartControl( 6171): -----IControl: 19
D/UEI.SmartControl( 6171): Caller: com.lge.qremote
I/UEI.SmartControl( 6171): Registering Services Ready callback...
I/UEI.SmartControl( 6171): Notify client services are ready...
D/UEI.SmartControl( 6171): -----IControl: 8
D/UEI.SmartControl( 6171): Caller: com.lge.qremote
I/ActivityManager(  870): Killing 5855:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  870): Killing 5838:com.lge.lockscreensettings/u0a69 (adj 15): empty #12
,W/libprocessgroup(  870): failed to open /acct/uid_10086/pid_5855/cgroup.procs: No such file or directory
,W/libprocessgroup(  870): failed to open /acct/uid_10069/pid_5838/cgroup.procs: No such file or directory
V/AlarmManager(  870): RTC_WAKEUP set : Alarm{2030b0dd type 0 when 1455035758569 com.android.vending} when 1455035758569
D/Finsky  ( 5907): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/SystemConfig( 6223): BUILD Country: EU
I/SystemConfig( 6223): BUILD Operator: OPEN
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  870): android: cancelAsUser(2) by android
,D/libc-netbsd( 5907): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5907): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5907): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5907): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  270): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  870): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6249 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
,I/System.out( 5907): propertyValue:false
D/libc-netbsd( 5907): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5907): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/SystemConfig( 6223): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6223): existFile = false
I/SystemConfig( 6223): canReadFile = false
I/SystemConfig( 6223): systemFeature RCS result false
D/SystemConfig( 6223): refreshRcsSupport() :false
,I/LockScreenSettings( 6249): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6249): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6249): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6249): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6249): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6249): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/libc-netbsd( 5907): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5907): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  870): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6267 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 6021:com.google.android.gm/u0a53 (adj 15): empty #11
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  870): failed to open /acct/uid_10053/pid_6021/cgroup.procs: No such file or directory
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  870): android: cancelAsUser(2) by android
W/ResourcesManager( 6267): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/qtaguid ( 5907): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5907): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5907): untagSocket(41) failed with errno -22
,D/Finsky  ( 5907): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  870): android: cancelAsUser(2) by android
,I/ActivityManager(  870): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6291 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.402ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.872ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.484ms
,I/qtaguid ( 5907): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5907): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5907): untagSocket(41) failed with errno -22
I/art     (  870): Explicit concurrent mark sweep GC freed 23494(1198KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 9.099ms total 172.098ms
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 5541): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/ResourcesManager( 6291): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6291): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/PackageBroadcastService( 5541): Null package name or gms related package.  Ignoreing.
,D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
I/Icing   ( 5541): updateResources: need to parse f{com.google.android.gms}
I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 63 ms] updated apps [took 63 ms] 
,I/PCSuite ( 6094): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6094): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6066): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6066): MCCMNC not supported: null
I/PCSuite ( 6094): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6094): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  870): Killing 5786:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/MultiDex( 6291): VM with version 2.1.0 has multidex support
I/MultiDex( 6291): install
I/MultiDex( 6291): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_5786/cgroup.procs: No such file or directory
,D/WeatherService( 2728): 2 : TimeTick Intent has been received, Time(hour:min:sec) 17:36:0
,D/WeatherService( 2728): 2 : TimeTick Intent And Screen On
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/WeatherService( 2728): 2 : SDK version : 21
I/art     ( 5907): CheckpointMarkThreadRoots callback created = 0xaafe11d0
,I/ActivityManager(  870): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6322 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5907): CheckpointMarkThreadRoots callback created = 0xaafe11a0
I/ActivityManager(  870): Process com.android.contacts (pid 6223) has died
,W/ActivityManager(  870): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2728): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2728): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2728): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2728): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2728): 2 : This is isUpdating : false
D/WeatherService( 2728): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2728): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2728): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2728): 2 : Fixed theme : optimus
D/WeatherReflect( 2728): 2 : Map key string is -2
,D/lim     ( 2728): 2 : time = 17:36
I/WeatherReflect( 2728): Model Name : LG-D722
D/WeatherTheme( 2728): 2 : Different view - status_min_formatted : 35 != 36
D/WeatherTheme( 2728): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2728): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
V/JNIHelp ( 6291): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2728): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/jxcore-log( 5472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5472): 
,D/Weather4x2_optimus( 2728): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2728): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2728): forecast size is 0
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2728): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2728): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2728): setTouchIntent, appWidgetId: 2
W/ActivityThread( 6291): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6291): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c55e54e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6291): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  870): Process com.android.gallery3d (pid 6204) has died
D/Theme_WeatherAncestor_optimus( 2728): url is : null
,I/NotificationManager( 6291): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6291): com.google.android.gms: cancel(39789) by com.google.android.gms
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2728): 2 : update view, appWidgetId: 2
D/WeatherService( 2728): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 17:36:0
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
,I/[SystemUI]Clock( 1371): called onTimeUpdated()
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
,I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/ChimeraCfgMgr( 6291): Reading stored module config
,I/ActivityManager(  870): Process com.google.android.apps.plus (pid 6267) has died
,D/ChimeraCfgMgr( 6291): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 94679097312; DSPS: 3193866; Offset : -2793979738
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  870): Process com.lge.lockscreensettings (pid 6249) has died
,D/NativeLibraryUtils( 6291): Install completed successfully. count=14 extracted=0
D/UEI.SmartControl( 6171): Service.onTrimMemory: 60
E/UEI.SmartControl( 6171): Setup service releasing memory...
,I/BackgroundMemoryTrimmer( 1939): Trimming objects from memory, since app is in the background.
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/PhoneApp( 1739): onTrimMemory: 10
I/PhoneApp( 1739): trim memory
,I/art     ( 6171): Explicit concurrent mark sweep GC freed 10620(757KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 922us total 81.207ms
,I/MusicStore( 6322): Database version: 120
,D/CAR.SERVICE( 6291): Connecting to CarCallService...
,I/art     ( 6291): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6291): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6322): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/CAR.SERVICE( 6291): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6291): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6291): Creating a new PhoneAdapter instance
,W/ActivityManager(  870): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6291): setListener: com.google.android.gms.car.dn@19588475
W/ActivityManager(  870): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6291): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6291): Starting CarCallService with initial phone null
I/NotificationManager( 6291): com.google.android.gms: cancel(10436) by com.google.android.gms
,V/AlarmManager(  870): RTC_WAKEUP set : Alarm{1c3e3147 type 0 when 1455035761104 com.google.android.googlequicksearchbox} when 1455035761104
,I/Icing   ( 5541): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6322): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,D/CAR.SERVICE( 6291): Package validated; name: com.android.vending
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6322): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Icing   ( 5541): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  870): Process com.android.settings (pid 6066) has died
,I/BackgroundMemoryTrimmer( 1939): Trimming objects from memory, since app is in the background.
V/AlarmManager(  870): RTC_WAKEUP set : Alarm{ff1029d type 0 when 1455035761224 com.android.vending} when 1455035761224
I/NotificationManager( 5907): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5907): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/ResourcesManager( 6322): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6322): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6322): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6322): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6322): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14dc7a61: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6322): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6322): GMSCore installation verified
,I/ConfigStore( 6322): Config Database version: 1
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  870): android: cancelAsUser(2) by android
D/Finsky  ( 5907): [730] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5907): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/MediaRouter( 6322): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6322): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6322): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6322): type=WIFI subType= reason=null isConnected=true
,I/jxcore-log( 5472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5472): 
I/ActivityManager(  870): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6369 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/qtaguid ( 5907): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5907): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5907): untagSocket(41) failed with errno -22
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:36:01.894 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/GHttpClientFactory( 6322): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6322): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 6322): com.google.android.music: cancel(1061) by com.google.android.music
,I/jxcore-log( 5472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5472): 
W/ResourcesManager( 6369): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6369): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6369): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5907): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5907): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/jxcore-log( 5472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5472): 
W/ResourcesManager( 5907): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 5472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5472): 
,D/Finsky  ( 5907): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  870): RTC_WAKEUP set : Alarm{30a9d5ed type 0 when 1455035762268 com.android.vending} when 1455035762268
,I/LGEmail ( 6369): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
,D/LGEmail ( 6369): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/DeviceConnectionService( 1732): client connected with version: 8296000
D/Finsky  ( 5907): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5907): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  870): Process com.lge.qremote (pid 6114) has died
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/AlertService( 6144): Beginning updateAlertNotification
,I/ActivityManager(  870): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6395 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6395): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/eas_req ( 6369): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/CalendarProvider2( 6395): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@37563843
,I/ActivityManager(  870): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6418 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/CalendarProvider2( 6395): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6395): Created com.android.providers.calendar.CalendarAlarmManager@202bd6ec(com.android.providers.calendar.CalendarProvider2@37563843)
I/HubEmail( 6369): JNI_OnLoad()
I/HubEmail( 6369): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 6369): registerNatives()
I/HubEmail( 6369): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6369): registerNativeMethods()
I/HubEmail( 6369): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6369): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
E/libprocessgroup(  870): failed to kill 1 processes for processgroup 6171
I/ActivityManager(  870): Process com.uei.lg.quicksetsdk.lite (pid 6171) has died
,W/Settings( 6369): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AlertService( 6144): No fired or scheduled alerts
I/NotificationManager( 6144): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(4) by com.android.calendar
,I/NotificationManager( 6144): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6144): com.android.calendar: cancel(19) by com.android.calendar
,I/NotificationManager( 6144): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6144): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/LGDMClient( 6418): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6418): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6418): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6418): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6418): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6418): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6418): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6418): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6448 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/AlarmScheduler( 6144): No events found starting within 1 week.
,W/ContextImpl( 6418): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6418): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6418): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6418): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6418): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6418): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  870): Killing 5702:com.google.android.talk/u0a61 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6448): onCreate
,W/AppUp4:DB( 6448):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6448):  setFingerPrint start
I/AppUp4:DB( 6448):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6448):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6448):  SDK version = 0
I/AppUp4:DB( 6448):  beforefinger == newfinger no write in DB
W/libprocessgroup(  870): failed to open /acct/uid_10061/pid_5702/cgroup.procs: No such file or directory
,I/ActivityManager(  870): Killing 6144:com.android.calendar/u0a13 (adj 15): empty #11
D/AppUp4:AppBoxApplication( 6448): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6448): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6448): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6448): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6448): [onReceive] request level :IDLE....
W/libprocessgroup(  870): failed to open /acct/uid_10013/pid_6144/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/AppUp4:CustModeStarterReceiver( 6448): onReceive
I/AppUp4:CustModeStarterReceiver( 6448): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6448): Context : android.app.ReceiverRestrictedContext@34ae9ab5
D/AppUp4:CustFacade( 6448): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6448): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6448): begin check event
I/AppUp4:CustModeStarterReceiver( 6448): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6448): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6448): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6448): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6448): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  870): Killing 6094:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_1000/pid_6094/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3167): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3167): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3167): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 5663): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5663): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 3236): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3236): DownloadService onCreate
I/DownloadManager( 3236): in removeSpuriousFiles
I/NotificationManager( 3236): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3236): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@2c55e54e on behalf of 3236
I/ActivityManager(  870): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6473 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3236): DownloadService onStartCommand
,I/DownloadManager( 3236): in trimDatabase
V/DownloadManager( 3236): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@b3a9005 on behalf of 3236
V/DownloadManager( 3236): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@8af085a on behalf of 3236
,V/DownloadManager( 3236): DownloadService onDestroy
,I/ActivityManager(  870): Killing 6322:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10081/pid_6322/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2728): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:36:3
D/UpdateThreadPoolManager( 2728): 2 : This is isUpdating : false
,D/WeatherAncestor( 2728): connectivity changed - connection : true
D/Weather_cast( 2728): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2728): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:36:4
D/WeatherService( 2728): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  870): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6500 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  870): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2728): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2728): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2728): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,W/ResourcesManager( 6500): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6500): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6500): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6500): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6500): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6500): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6500): MmsConfig.loadFromResources
E/Babel_SMS( 6500): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6500): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6500): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6500): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6500): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 6500): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6500): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6500): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6500): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6500): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6500): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6500): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6500): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6500): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6500): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6500): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6500): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6500): found sensor: Motion Accel, handle=46
,W/Settings( 6500): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6500): startup - clean
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     ( 6500): CheckpointMarkThreadRoots callback created = 0xb042d900
,I/Babel   ( 6500): deleted: false for 0
,I/art     ( 6500): CheckpointMarkThreadRoots callback created = 0xb042d8e0
I/ActivityManager(  870): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6535 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6500): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6500): Unsupported mime audio/adpcm
W/AudioCapabilities( 6500): Unsupported mime audio/g726
W/AudioCapabilities( 6500): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6500): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6500): Unsupported mime video/mjpg
W/VideoCapabilities( 6500): Unsupported mime video/theora
W/AudioCapabilities( 6500): Unsupported mime audio/evrc
W/AudioCapabilities( 6500): Unsupported mime audio/qcelp
W/VideoCapabilities( 6500): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6500): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6500): Unsupported mime audio/qcelp
W/AudioCapabilities( 6500): Unsupported mime audio/evrc
W/VideoCapabilities( 6500): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6500): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6500): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6500): Unrecognized profile 2130706433 for video/avc
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-60 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 17:36:04.906 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/VideoCapabilities( 6500): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6500): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6500): onServiceConnected
W/Babel   ( 6500): Attempted to change video mute state without an active call.
I/NotificationManager( 6500): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6500): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6500): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6500): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6500): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  270): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 6500): propertyValue:false
,I/Babel   ( 6500): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  870): Killing 5541:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10006/pid_5541/cgroup.procs: No such file or directory
,I/art     (  870): Explicit concurrent mark sweep GC freed 21090(940KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.584ms total 168.278ms
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6535): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6535): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6535): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6535): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6535): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6535):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6535):   adb logcat -s GAv4
W/GAv4    ( 6535): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6535): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6535): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  870): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=6583 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/WebViewFactory( 6535): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/ResourcesManager( 6583): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6583): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/LibraryLoader( 6535): Time to load native libraries: 2 ms (timestamps 9791-9793)
,I/LibraryLoader( 6535): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6535): Binding Chromium to main looper Looper (main, tid 1) {1eac3dfe}
I/LibraryLoader( 6535): Expected native library version number "",actual native library version number ""
I/chromium( 6535): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6535): Initializing chromium process, singleProcess=true
W/art     ( 6535): Attempt to remove local handle scope entry from IRT, ignoring
I/MultiDex( 6583): VM with version 2.1.0 has multidex support
I/MultiDex( 6583): install
I/MultiDex( 6583): VM has multidex support, MultiDex support library is disabled.
E/SysUtils( 6535): ApplicationContext is null in ApplicationStatus
W/chromium( 6535): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6535): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6535): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6535): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6535): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6535): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6535): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6535): Remote Branch: 
I/Adreno-EGL( 6535): Local Patches: 
I/Adreno-EGL( 6535): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb57e7460, uid 10079
W/AudioManagerAndroid( 6535): Requires BLUETOOTH permission
,I/NSApplication( 6535): Starting up...
,I/ActivityManager(  870): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6619 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  870): Killing 6291:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10006/pid_6291/cgroup.procs: No such file or directory
W/ActivityManager(  870): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,V/JNIHelp ( 6583): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6583): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6583): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3392e844: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6583): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6583): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6583): com.google.android.gms: cancel(39789) by com.google.android.gms
I/ActivityManager(  870): Killing 5907:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10036/pid_5907/cgroup.procs: No such file or directory
,D/NativeLibraryUtils( 6583): Install completed successfully. count=14 extracted=0
I/ActivityManager(  870): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6650 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  870): Killing 6395:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.120ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 20.684ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 21.208ms
,W/libprocessgroup(  870): failed to open /acct/uid_10014/pid_6395/cgroup.procs: No such file or directory
,W/ResourcesManager( 6650): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 6583): SYNC; picasa accounts
,D/NetworkLogImpl( 6583): Loaded NetworkSpeedPredictor
I/iu.Environment( 6583): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  870): Killing 6369:com.lge.email/u0a21 (adj 15): empty #11
,I/iu.UploadsManager( 6583): num queued entries: 0
I/iu.UploadsManager( 6583): num updated entries: 0
I/iu.SyncManager( 6583): NEXT; no task
W/libprocessgroup(  870): failed to open /acct/uid_10021/pid_6369/cgroup.procs: No such file or directory
,I/ActivityManager(  870): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6683 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6683): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6683): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6683): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6683): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6683): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6683): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14dc7a61: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6683): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6683): GMSCore installation verified
,I/ConfigStore( 6683): Config Database version: 1
,I/MediaRouter( 6683): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6683): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6683): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6683): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  870): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6720 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6683): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6683): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  870): Killing 6418:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 6720): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6720): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6720): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  870): failed to open /acct/uid_1000/pid_6418/cgroup.procs: No such file or directory
,I/NotificationManager( 6683): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6720): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6720): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6720): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  870): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6743 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6720): JNI_OnLoad()
I/HubEmail( 6720): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6720): registerNatives()
I/HubEmail( 6720): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6720): registerNativeMethods()
I/HubEmail( 6720): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6720): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  870): Killing 6448:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/Settings( 6720): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_6448/cgroup.procs: No such file or directory
I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  268): 
D/LGDMClient( 6743): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6743): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/ContextImpl( 6743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6743): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6743): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6743): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6743): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6772 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6743): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6743): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6743): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6743): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6743): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6743): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  870): Killing 5663:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  870): failed to open /acct/uid_10038/pid_5663/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6772): onCreate
,W/AppUp4:DB( 6772):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6772):  setFingerPrint start
I/AppUp4:DB( 6772):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6772):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6772):  SDK version = 0
I/AppUp4:DB( 6772):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6772): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6772): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6772): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6772): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6772): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6772): onReceive
I/AppUp4:CustModeStarterReceiver( 6772): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6772): Context : android.app.ReceiverRestrictedContext@34ae9ab5
D/AppUp4:CustFacade( 6772): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6772): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6772): begin check event
I/AppUp4:CustModeStarterReceiver( 6772): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6772): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6772): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6772): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6772): handleAsyncCustNotification do not startCustService
I/ActivityManager(  870): Killing 6473:com.lge.drmservice/u0a51 (adj 15): empty #11
I/LgeMiscReceiver( 3167): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3167): action = android.net.conn.CONNECTIVITY_CHANGE
W/libprocessgroup(  870): failed to open /acct/uid_10051/pid_6473/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3167): networkInfo.isConnected() = false
,I/ActivityManager(  870): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6794 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6794): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6794): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6794): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  870): Killing 6500:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10061/pid_6500/cgroup.procs: No such file or directory
V/DownloadManager( 3236): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3236): DownloadService onCreate
I/DownloadManager( 3236): in removeSpuriousFiles
I/ActivityManager(  870): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6815 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/NotificationManager( 3236): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3236): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@2ba0a768 on behalf of 3236
I/DownloadManager( 3236): in trimDatabase
V/DownloadManager( 3236): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@1d455026 on behalf of 3236
,V/DownloadManager( 3236): DownloadService onStartCommand
,V/DownloadManager( 3236): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@b8cd214 on behalf of 3236
,D/PhoneMonitor( 6794): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6794): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6794): [parse] Load xml
V/TelephonyAutoProfiling( 6794): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6794): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/CheckinService( 6583): Checkin interval check for package: unspecified last checkin: 1455035742939 min interval config: 0 actual interval: 26907
,D/PhoneMonitor( 6794): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 6583): Disabling old GoogleServicesFramework version
,V/DownloadManager( 3236): DownloadService onDestroy
,D/WeatherAncestor( 2728): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:36:9
D/UpdateThreadPoolManager( 2728): 2 : This is isUpdating : false
D/WeatherAncestor( 2728): connectivity changed - connection : true
D/Weather_cast( 2728): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2728): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:36:9
D/WeatherService( 2728): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  870): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6842 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  870): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2728): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2728): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2728): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/CheckinService( 6583): Checking schedule, now: 1455035770048 next: 1455035772887
I/CheckinService( 6583): active receiver: disabled
,I/art     (  870): Explicit concurrent mark sweep GC freed 18457(925KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.087ms total 141.082ms
,I/ActivityManager(  870): Killing 6535:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/ResourcesManager( 6842): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/libprocessgroup(  870): failed to kill 1 processes for processgroup 6535
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Babel_SMS( 6842): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6842): MmsConfig.loadMmsSettings
I/Babel_SMS( 6842): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6842): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6842): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6842): MmsConfig.loadFromResources
E/Babel_SMS( 6842): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6842): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6842): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6842): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6842): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6842): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6842): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6842): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6842): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6842): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6842): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6842): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6842): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6842): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6842): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6842): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6842): found sensor: LGE Relative Motion Detector Sensor, handle=34
,D/SensorManager( 6842): found sensor: Motion Accel, handle=46
W/Settings( 6842): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6842): startup - clean
I/Babel   ( 6842): deleted: false for 0
,I/art     ( 6842): CheckpointMarkThreadRoots callback created = 0xb042d550
I/art     ( 6842): CheckpointMarkThreadRoots callback created = 0xb042d530
,I/ActivityManager(  870): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6888 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6842): Unsupported mime audio/x-lg-flac
,I/jxcore-log( 5472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5472): 
W/AudioCapabilities( 6842): Unsupported mime audio/adpcm
W/AudioCapabilities( 6842): Unsupported mime audio/g726
W/AudioCapabilities( 6842): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6842): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6842): Unsupported mime video/mjpg
,W/VideoCapabilities( 6842): Unsupported mime video/theora
I/jxcore-log( 5472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5472): 
,W/AudioCapabilities( 6842): Unsupported mime audio/evrc
,W/AudioCapabilities( 6842): Unsupported mime audio/qcelp
W/VideoCapabilities( 6842): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6842): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6842): Unsupported mime audio/qcelp
W/AudioCapabilities( 6842): Unsupported mime audio/evrc
W/VideoCapabilities( 6842): Unsupported mime video/mp4v-esdp
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,I/VideoCapabilities( 6842): Unsupported profile 4 for video/mp4v-es
I/GAv4    ( 6888): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6888):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6888):   adb logcat -s GAv4
,W/ContextImpl( 6888): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6888): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/VideoCapabilities( 6842): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6842): Unrecognized profile 2130706433 for video/avc
,W/GAv4    ( 6888): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/VideoCapabilities( 6842): Unrecognized profile 2130706433 for video/avc
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/VideoCapabilities( 6842): Unrecognized profile 2130706433 for video/avc
W/ContextImpl( 6888): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/vclib   ( 6842): onServiceConnected
,W/Babel   ( 6842): Attempted to change video mute state without an active call.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6888): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6888): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/NotificationManager( 6842): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  270): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 6842): propertyValue:false
W/GAv4    ( 6888): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/jxcore-log( 5472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5472): 
,I/WebViewFactory( 6888): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6888): Time to load native libraries: 2 ms (timestamps 5670-5672)
,I/LibraryLoader( 6888): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6888): Binding Chromium to main looper Looper (main, tid 1) {1eac3dfe}
I/LibraryLoader( 6888): Expected native library version number "",actual native library version number ""
I/chromium( 6888): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/Babel   ( 6842): connection state changed from UNKNOWN to CONNECTED
,I/BrowserStartupController( 6888): Initializing chromium process, singleProcess=true
W/art     ( 6888): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6888): ApplicationContext is null in ApplicationStatus
,W/chromium( 6888): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6888): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6888): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6888): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6888): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6888): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6888): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6888): Remote Branch: 
I/Adreno-EGL( 6888): Local Patches: 
I/Adreno-EGL( 6888): Reconstruct Branch: 
V/AudioPolicyService(  282): registerClient() client 0xb3c3ad20, uid 10079
,I/NSApplication( 6888): Starting up...
W/AudioManagerAndroid( 6888): Requires BLUETOOTH permission
I/ActivityManager(  870): Killing 6650:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10086/pid_6650/cgroup.procs: No such file or directory
,I/ActivityManager(  870): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6951 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 6683:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10081/pid_6683/cgroup.procs: No such file or directory
,W/ResourcesManager( 6951): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  870): Killing 6720:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10021/pid_6720/cgroup.procs: No such file or directory
,I/ActivityManager(  870): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6979 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/jxcore-log( 5472): Test app app.js loaded
I/jxcore-log( 5472): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@313b7237 added. We now have 1 listener(s)
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
I/Gmail   ( 6979): getAccountsCursor
,I/jxcore-log( 5472): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5472): 
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6979): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/jxcore-log( 5472): TAP version 13
I/jxcore-log( 5472): 
,I/chromium( 5472): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 5472): 
W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6979): Error finding the version of the Email provider.....
E/Gmail   ( 6979): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6979): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6979): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6979): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6979): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6979): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6979): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6979): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6979): We do not support migrating this version of the Email provider.
,I/jxcore-log( 5472): ok 1 publicKeysToNotify cannot be null
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 2 ecdhForLocalDevice cannot be null
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #generatePreambleAndBeacons expiration out of range lower
I/jxcore-log( 5472): 
I/Gmail   ( 6979): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 5472): ok 3 secondsUntilExpiration out of range.
I/jxcore-log( 5472): 
,W/ActivityManager(  870): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #generatePreambleAndBeacons expiration out of range upper
I/jxcore-log( 5472): 
W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/jxcore-log( 5472): ok 4 secondsUntilExpiration out of range.
I/jxcore-log( 5472): 
I/Gmail   ( 6979): Observing account changes for notifications
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 5 should be equal
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 5472): 
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  870): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7031 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.226ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.728ms
,I/ActivityManager(  870): Killing 6743:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.764ms
I/Gmail   ( 6979): notifyAccountChanged
,I/Gmail   ( 6979): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6979): getAccountsCursor
I/Gmail   ( 6979): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/jxcore-log( 5472): ok 6 should be equal
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 7 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 8 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 9 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/Gmail   ( 6979): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/jxcore-log( 5472): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 5472): 
I/Gmail   ( 6979): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/jxcore-log( 5472): ok 10 should throw
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 5472): 
W/libprocessgroup(  870): failed to open /acct/uid_1000/pid_6743/cgroup.procs: No such file or directory
,I/jxcore-log( 5472): ok 11 Preamble expiration must be a 64 bit integer
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #parseBeacons expiration out of range lower
I/jxcore-log( 5472): 
W/ResourcesManager( 7031): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/jxcore-log( 5472): ok 12 Expiration out of range
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #parseBeacons expiration out of range lower
I/jxcore-log( 5472): 
D/CalendarProvider2( 7031): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@37563843
D/CalendarProvider2( 7031): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 7031): Created com.android.providers.calendar.CalendarAlarmManager@202bd6ec(com.android.providers.calendar.CalendarProvider2@37563843)
D/CalendarProviderBroadcastReceiver( 7031): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
I/jxcore-log( 5472): ok 13 Expiration out of range
I/jxcore-log( 5472): 
,D/CalendarProviderBroadcastReceiver( 7031): [IntentService] WakeLock acquire, start IntentSerivce
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #parseBeacons no beacons returns null
I/jxcore-log( 5472): 
D/CalendarProvider2( 7031): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 7031): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7031): [getOrCreateCalendarAlarmManager]
I/jxcore-log( 5472): ok 14 should be equal
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 15 Malformed encrypted beacon key ID
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 5472): 
,I/ActivityManager(  870): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7052 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/CalendarProvider2( 7031): [IntentService] Release Lock
,D/CalendarProvider2( 7031): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  870): Killing 6772:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/MusicStore( 7052): Database version: 120
,W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_6772/cgroup.procs: No such file or directory
,I/jxcore-log( 5472): ok 16 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #parseBeacons addressBookCallback returns no matches
I/jxcore-log( 5472): 
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7052): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/Gmail   ( 6979): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7052): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7052): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7052): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7052): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7052): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/jxcore-log( 5472): ok 17 should be equal
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 18 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 5472): 
W/ActivityThread( 7052): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7052): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14dc7a61: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7052): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7052): GMSCore installation verified
I/ConfigStore( 7052): Config Database version: 1
,I/jxcore-log( 5472): ok 19 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 20 (unnamed assert)
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 5472): 
,I/art     (  870): Explicit concurrent mark sweep GC freed 17397(895KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.498ms total 151.688ms
,I/MediaRouter( 7052): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 7052): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7052): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7052): type=WIFI subType= reason=null isConnected=true
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  870): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7084 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/jxcore-log( 5472): ok 21 (unnamed assert)
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/art     ( 5927): Explicit concurrent mark sweep GC freed 2337(101KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 523us total 48.598ms
,W/ResourcesManager( 7084): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7084): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/GHttpClientFactory( 7052): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7052): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  870): Killing 6794:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10038/pid_6794/cgroup.procs: No such file or directory
,I/NotificationManager( 7052): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7084): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7084): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7084): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  870): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7109 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7084): JNI_OnLoad()
I/HubEmail( 7084): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7084): registerNatives()
I/HubEmail( 7084): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7084): registerNativeMethods()
I/HubEmail( 7084): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7084): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  870): Killing 6815:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10051/pid_6815/cgroup.procs: No such file or directory
W/Settings( 7084): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7109): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7109): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7109): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7109): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7109): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7109): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7109): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7109): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7133 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7109): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7109): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7109): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 7109): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7109): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7109): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  870): Killing 6888:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10079/pid_6888/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7133): onCreate
W/AppUp4:DB( 7133):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7133):  setFingerPrint start
I/AppUp4:DB( 7133):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7133):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7133):  SDK version = 0
,I/AppUp4:DB( 7133):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7133): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7133): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7133): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7133): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7133): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7133): onReceive
I/AppUp4:CustModeStarterReceiver( 7133): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7133): Context : android.app.ReceiverRestrictedContext@34ae9ab5
,D/AppUp4:CustFacade( 7133): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7133): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7133): begin check event
I/AppUp4:CustModeStarterReceiver( 7133): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7133): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7133): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7133): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7133): handleAsyncCustNotification do not startCustService
I/ActivityManager(  870): Killing 6619:com.android.chrome/u0a48 (adj 15): empty #11
I/LgeMiscReceiver( 3167): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3167): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3167): networkInfo.isConnected() = true
W/libprocessgroup(  870): failed to open /acct/uid_10048/pid_6619/cgroup.procs: No such file or directory
D/PhoneState( 3167): setPdpRejectCasuse : false
I/ActivityManager(  870): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7152 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7152): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7152): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7152): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  870): Killing 6951:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,D/PhoneMonitor( 7152): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7152): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7152): [parse] Load xml
V/TelephonyAutoProfiling( 7152): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7152): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7152): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  870): failed to open /acct/uid_10086/pid_6951/cgroup.procs: No such file or directory
,V/DownloadManager( 3236): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3236): DownloadService onCreate
I/DownloadManager( 3236): in removeSpuriousFiles
I/NotificationManager( 3236): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,V/DownloadManager( 3236): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@1fa648b2 on behalf of 3236
I/DownloadManager( 3236): in trimDatabase
V/DownloadManager( 3236): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@3b6efb80 on behalf of 3236
,I/ActivityManager(  870): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7177 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3236): DownloadService onStartCommand
I/CheckinService( 6583): Checkin interval check for package: unspecified last checkin: 1455035742939 min interval config: 0 actual interval: 32256
V/DownloadManager( 3236): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@1eac3dfe on behalf of 3236
,I/CheckinService( 6583): Checking schedule, now: 1455035775231 next: 1455035772887
I/CheckinService( 6583): active receiver: enabled
,V/DownloadManager( 3236): DownloadService onDestroy
I/CheckinService( 6583): Preparing to send checkin request
,D/WeatherAncestor( 2728): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:36:15
,D/UpdateThreadPoolManager( 2728): 2 : This is isUpdating : false
D/WeatherAncestor( 2728): connectivity changed - connection : true
D/Weather_cast( 2728): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2728): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 17:36:15
I/EventLogService( 6583): Accumulating logs since 1455035755953
D/WeatherService( 2728): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  870): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2728): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2728): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2728): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  870): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7203 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 6583): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6583): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7203): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/NotificationManager( 6583): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/GAv4    ( 7203): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7203):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7203):   adb logcat -s GAv4
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7203): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7203): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/GAv4    ( 7203): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7203): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7203): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7203): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/CheckinRequestBuilder( 6583): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6583): Failed to find provider info for com.google.android.wearable.settings
,I/WebViewFactory( 7203): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7203): Time to load native libraries: 2 ms (timestamps 56-58)
I/LibraryLoader( 7203): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7203): Binding Chromium to main looper Looper (main, tid 1) {1eac3dfe}
I/LibraryLoader( 7203): Expected native library version number "",actual native library version number ""
I/chromium( 7203): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7203): Initializing chromium process, singleProcess=true
W/art     ( 7203): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  870): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7250 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
E/SysUtils( 7203): ApplicationContext is null in ApplicationStatus
W/chromium( 7203): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7203): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7203): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7203): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7203): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7203): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7203): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7203): Remote Branch: 
I/Adreno-EGL( 7203): Local Patches: 
I/Adreno-EGL( 7203): Reconstruct Branch: 
,W/ResourcesManager( 7250): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7250): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/AudioPolicyService(  282): registerClient() client 0xb3c3ad60, uid 10079
,W/AudioManagerAndroid( 7203): Requires BLUETOOTH permission
I/NSApplication( 7203): Starting up...
I/MultiDex( 7250): VM with version 2.1.0 has multidex support
I/MultiDex( 7250): install
I/MultiDex( 7250): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  870): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7284 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/JNIHelp ( 7250): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7250): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7250): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c55e54e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7250): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7250): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7250): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 7250): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7250): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/ActivityManager(  870): Killing 6979:com.google.android.gm/u0a53 (adj 15): empty #11
,D/NativeLibraryUtils( 7250): Install completed successfully. count=14 extracted=0
,V/AlarmManager(  870): RTC_WAKEUP set : Alarm{3106d231 type 0 when 1455035772887 com.google.android.gms} when 1455035772887
,I/ActivityManager(  870): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7306 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  870): RTC_WAKEUP set : Alarm{36d89d16 type 0 when 1455035776360 com.android.vending} when 1455035776360
W/libprocessgroup(  870): failed to open /acct/uid_10053/pid_6979/cgroup.procs: No such file or directory
I/ActivityManager(  870): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7323 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  870): Killing 7031:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 21.720ms
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.141ms
,D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): CdmEngine::OpenSession
I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.195ms
W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
,W/libprocessgroup(  870): failed to open /acct/uid_10014/pid_7031/cgroup.procs: No such file or directory
W/ResourcesManager( 7323): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=3649285159
D/Finsky  ( 7306): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7306): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7306): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7306): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7306): com.android.vending: cancel(-1050172287) by com.android.vending
,I/art     ( 7250): CheckpointMarkThreadRoots callback created = 0xb04d4ef0
,I/art     ( 7250): CheckpointMarkThreadRoots callback created = 0xb04d4ee0
,I/art     (  870): Explicit concurrent mark sweep GC freed 19521(937KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.548ms total 163.760ms
,V/DownloadManager( 3236): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@3c884fac on behalf of 7306
D/Ads     ( 7306): Skipping gmscore version check
,I/ActivityManager(  870): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7376 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/Finsky  ( 7306): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7306): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  870): Killing 7052:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10081/pid_7052/cgroup.procs: No such file or directory
,D/Finsky  ( 7306): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/WVCdm   (  282): CdmEngine::OpenSession
,D/Finsky  ( 7306): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 7376): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  870): Message: 20
,D/BluetoothManagerService(  870): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bbfa9a1:true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
D/Finsky  ( 7306): [950] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7306): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  870): Killing 7084:com.lge.email/u0a21 (adj 15): empty #11
I/ActivityManager(  870): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7399 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  870): failed to open /acct/uid_10021/pid_7084/cgroup.procs: No such file or directory
,V/LGMDMManager( 7376): Create singleton instance
,I/AudioManager( 7376): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7399): Quickset Services start...
I/AudioManager( 7376): getMode name:com.lge.qremote
I/UEI.SmartControl( 7399): Manufacture = LGE
D/UEI.SmartControl( 7399): File observer start...
E/UEI.SmartControl( 7399): IR Port is disabled: false
D/UEI.SmartControl( 7399): Starting file observer...
D/UEI.SmartControl( 7399): Extracting JNI libs...
D/UEI.SmartControl( 7399): --- this system supports 32-bit or 64-bit only
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 6583): Restart initialization of location
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
D/Finsky  ( 7306): [955] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,E/MDM     ( 1732): [106] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/NotificationManager(  870): android: cancelAsUser(2) by android
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
D/LocationInitializer( 6583): Restart initialization of location
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 7306): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7306): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7306): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7306): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  270): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  870): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7433 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 7306): propertyValue:false
D/UEI.SmartControl( 7399): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7399): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7399): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,W/IcingInternalCorpora( 6583): getNumBytesRead when not calculated.
,I/UEI.SmartControl( 7399): --- Selecting new region: 2
,I/UEI.SmartControl( 7399): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7399): Platform has CIR...
D/UEI.SmartControl( 7399): NO CIR support, need to check package...
I/UEI.SmartControl( 7399): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7399): QS Service created
E/UEI.SmartControl( 7399): QS start get config
,D/UEI.SmartControl( 7399): Loading JNI Libs...
D/UEI.SmartControl( 7399):  configuring local db...
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Gmail   ( 7433): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7433): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7433): Error finding the version of the Email provider.....
E/Gmail   ( 7433): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7433): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7433): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7433): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7433): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7433): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7433): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7433): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7433): We do not support migrating this version of the Email provider.
I/Gmail   ( 7433): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/MDM     ( 1732): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 6583): Restart initialization of location
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/ActivityManager(  870): Killing 7109:com.lge.lgdmsclient/1000 (adj 15): empty #11
,D/UEI.SmartControl( 7399):  ---- Has DB8: true
,D/UEI.SmartControl( 7399): QS start statue = true Error code = 0
D/UEI.SmartControl( 7399): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7399): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7399): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7399): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7399): IrrcClient ++ 
D/irrcClient( 7399): getIrrcService ++ 
D/irrcClient( 7399): getIrrcService -- 
,D/irrcClient( 7399): IrrcClient -- 
W/irrc_jni( 7399): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7399): Services init done
I/UEI.SmartControl( 7399): Device manager: loading config....
D/UEI.SmartControl( 7399): Config is loaded...
,D/UEI.SmartControl( 7399):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7399): Notify AllClients services are ready: 0
,W/libprocessgroup(  870): failed to open /acct/uid_1000/pid_7109/cgroup.procs: No such file or directory
,W/ActivityManager(  870): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/UEI.SmartControl( 7399): QS Service init finished
D/UEI.SmartControl( 7399): QS Service version name: 0.1.73
D/UEI.SmartControl( 7399): QS Service version code: 1073
D/UEI.SmartControl( 7399): Service requested: Control
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7433): Observing account changes for notifications
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 7399): Internal service binding...
D/UEI.SmartControl( 7399): -----IControl: 11
D/UEI.SmartControl( 7399): Caller: com.lge.qremote
D/UEI.SmartControl( 7399): ------------ IControl registerCallback...
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
I/UEI.SmartControl( 7399): Registering callback...
I/CheckinService( 6583): Checkin interval check for package: unspecified last checkin: 1455035742939 min interval config: 0 actual interval: 35956
D/UEI.SmartControl( 7399): -----IControl: 19
,I/WVCdm   (  282): CdmEngine::CloseSession
D/UEI.SmartControl( 7399): Caller: com.lge.qremote
I/UEI.SmartControl( 7399): Registering Services Ready callback...
I/UEI.SmartControl( 7399): Notify client services are ready...
I/AudioManager( 7376): getMode name:com.lge.qremote
D/UEI.SmartControl( 7399): -----IControl: 8
,D/UEI.SmartControl( 7399): Caller: com.lge.qremote
I/ActivityManager(  870): Killing 7177:com.lge.drmservice/u0a51 (adj 15): empty #11
W/ContextImpl( 3591): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=3023309331
,I/ActivityManager(  870): Killing 7133:com.lge.appbox.client/u0a11 (adj 15): empty #12
,I/Gmail   ( 7433): notifyAccountChanged
,I/Gmail   ( 7433): getAccountsCursor
I/Gmail   ( 7433): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7433): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7433): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7433): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,W/libprocessgroup(  870): failed to open /acct/uid_10051/pid_7177/cgroup.procs: No such file or directory
W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_7133/cgroup.procs: No such file or directory
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 7376): getMode name:com.lge.qremote
,I/AudioManager( 7376): getMode name:com.lge.qremote
,I/AudioManager( 7376): getMode name:com.lge.qremote
,I/Gmail   ( 7433): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 114679868555; DSPS: 3849252; Offset : -2794002030
I/WVCdm   (  282): CdmEngine::CloseSession
I/WVCdm   (  282): L3 Terminate.
,I/dex2oat ( 7504): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=38 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/MusicWidget( 2646): mDelayedStopHandler : unbind
,I/dex2oat ( 7504): dex2oat took 100.951ms (threads: 4)
,I/MusicBrowser( 2744): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2744): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2744): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2744): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2744): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2744): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2744): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2744): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/Adreno-EGL( 7250): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7250): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7250): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7250): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7250): Remote Branch: 
I/Adreno-EGL( 7250): Local Patches: 
I/Adreno-EGL( 7250): Reconstruct Branch: 
I/Adreno-EGL( 7250): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7250): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7250): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7250): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7250): Remote Branch: 
I/Adreno-EGL( 7250): Local Patches: 
I/Adreno-EGL( 7250): Reconstruct Branch: 
,I/art     (  870): Explicit concurrent mark sweep GC freed 17039(765KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.382ms total 182.339ms
,I/MediaFocusControl(  870):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2a7184facom.lge.music.MediaPlaybackService$6@3c35faab
D/MusicBrowser( 2744): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2744): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2744): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2744): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2744): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1afb2d31
I/MusicBrowser( 2744): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2744): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
,I/MusicBrowser( 2744): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2744): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2744): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2744): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2744): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2744): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2744): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2744): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2744): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2744): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2744): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2744): reset
,V/MediaPlayer[Native]( 2744): setListener
,V/MediaPlayer[Native]( 2744): disconnect
V/MediaPlayer[Native]( 2744): destructor
,V/AudioFlinger(  282): releasing 19 from 2744 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/MediaPlayer[Native]( 2744): disconnect
D/MusicBrowser( 2744): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2744): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2744): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2744): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2744): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2744): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2744): [SmartShareManagerClient] unregisterListener: 547226888
W/SmartShareClient( 2744): [SmartShareManagerClient] unregisterListener invalid listener: 547226888
I/SmartShareClient( 2744): [SmartShareManagerClient] terminate service: 2744/MediaPlaybackService/614077855
E/HomeCloudIF( 2744): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2744): [SmartShareManagerClient] unbindService context:android.app.Application@3500c4a1
V/CloudHub( 2744): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2744): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2744): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2744): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2744): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
,I/ActivityManager(  870): Killing 6842:com.google.android.talk/u0a61 (adj 15): empty #11
I/CloudHub( 2744): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29988
,W/libprocessgroup(  870): failed to open /acct/uid_10061/pid_6842/cgroup.procs: No such file or directory
,I/Adreno-EGL( 7250): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7250): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7250): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7250): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7250): Remote Branch: 
I/Adreno-EGL( 7250): Local Patches: 
I/Adreno-EGL( 7250): Reconstruct Branch: 
,I/CheckinRequestBuilder( 6583): Classify the device as Phone.
,D/libc-netbsd( 6583): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6583): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6583): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6583): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  270): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 6583): propertyValue:false
D/libc-netbsd( 6583): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6583): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6583): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6583): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6583): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6583): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 6583): Sending checkin request (9910 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 6583): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6583): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 5927): Explicit concurrent mark sweep GC freed 3117(125KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.021ms total 32.772ms
,I/CheckinRequestBuilder( 6583): Classify the device as Phone.
,I/CheckinTask( 6583): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6583): Checking schedule, now: 1455035783056 next: 1455563032051
I/CheckinService( 6583): active receiver: disabled
,I/CheckinService( 6583): Checking schedule, now: 1455035783102 next: 1455563032051
I/CheckinService( 6583): active receiver: disabled
,D/CheckinService( 6583): Recording last checkin time for package unspecified as 1455035783120
,V/SetupWizard( 7152): Connected to Gservices successfully
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAv4-SVC( 6583): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 7433): Thread[GAThread,5,main]: No campaign data found.
,D/UEI.SmartControl( 7399): Internal timer expired: 1
,I/ActivityManager(  870): Killing 7284:com.android.chrome/u0a48 (adj 15): empty #11
,I/ActivityManager(  870): Killing 7203:com.google.android.apps.magazines/u0a79 (adj 15): empty #12
,W/libprocessgroup(  870): failed to open /acct/uid_10048/pid_7284/cgroup.procs: No such file or directory
,W/libprocessgroup(  870): failed to open /acct/uid_10079/pid_7203/cgroup.procs: No such file or directory
,I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  870): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  870): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7563 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/administrator(  870): Handling package changes for user 0
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7563): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  870): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  870): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  870): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  870): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/BackupManagerService(  870): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  870): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@131e62b8
W/ResourcesManager(  870): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Babel_SMS( 7563): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7563): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7563): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 7563): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7563): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7563): MmsConfig.loadFromResources
E/Babel_SMS( 7563): canonicalizeMccMnc: invalid mccmnc nullnull
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
,I/Babel_SMS( 7563): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,W/ResourceType(  870): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/SensorManager( 7563): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7563): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7563): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7563): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7563): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7563): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7563): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7563): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7563): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7563): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7563): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7563): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7563): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7563): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7563): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7563): found sensor: Motion Accel, handle=46
I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     ( 7563): CheckpointMarkThreadRoots callback created = 0xaaf55490
I/art     ( 7563): CheckpointMarkThreadRoots callback created = 0xaaf55460
,I/ActivityManager(  870): Process com.google.android.apps.plus (pid 7323) has died
,W/Settings( 7563): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7563): startup - clean
,D/LocationProviderProxy(  870): applying state to connected service
I/Babel   ( 7563): deleted: false for 0
,W/AudioCapabilities( 7563): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7563): Unsupported mime audio/adpcm
W/AudioCapabilities( 7563): Unsupported mime audio/g726
W/AudioCapabilities( 7563): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7563): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7563): Unsupported mime video/mjpg
W/VideoCapabilities( 7563): Unsupported mime video/theora
,I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7598 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 7563): Unsupported mime audio/evrc
W/AudioCapabilities( 7563): Unsupported mime audio/qcelp
W/VideoCapabilities( 7563): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7563): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7563): Unsupported mime audio/qcelp
W/AudioCapabilities( 7563): Unsupported mime audio/evrc
,W/VideoCapabilities( 7563): Unsupported mime video/mp4v-esdp
I/AppUp4:AppBoxCP( 7598): onCreate
,W/AppUp4:DB( 7598):  [AppBoxDatabaseHelper] construct
I/VideoCapabilities( 7563): Unsupported profile 4 for video/mp4v-es
I/AppUp4:DB( 7598):  setFingerPrint start
I/AppUp4:DB( 7598):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7598):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7598):  SDK version = 0
I/AppUp4:DB( 7598):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7598): AppBoxApplication onCreate()
W/VideoCapabilities( 7563): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7563): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7563): Unrecognized profile 2130706433 for video/avc
I/AppUp4:CustModeStarterReceiver( 7598): onReceive
,I/AppUp4:CustModeStarterReceiver( 7598): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
W/VideoCapabilities( 7563): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 7598): Context : android.app.ReceiverRestrictedContext@1102233e
D/AppUp4:CustFacade( 7598): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7598): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7598): begin check event
I/AppUp4:CustModeStarterReceiver( 7598): Event For Nothing, skip.
I/ActivityManager(  870): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7626 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 7563): onServiceConnected
,W/Babel   ( 7563): Attempted to change video mute state without an active call.
I/NotificationManager( 7563): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 7563): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7563): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  870): Process com.android.vending (pid 7306) has died
,W/ResourcesManager( 7626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7626): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7626): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 7563): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7563): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7563): Installed default security provider GmsCore_OpenSSL
,I/AppConfig( 7626): Total System Memory = 906309632
,I/NotificationManager( 7563): com.google.android.talk: cancel(10436) by com.google.android.talk
I/GalleryUtils( 7626): Application Heap = 96 MB
I/AppConfig( 7626): App Tier : NOT_DEF
D/SystemHelper( 7626): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  870): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7653 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ResourcesManager( 7653): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7653): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7653): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7653): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7653): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7653): BUILD Country: EU
I/SystemConfig( 7653): BUILD Operator: OPEN
,I/SystemConfig( 7653): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7653): existFile = false
I/SystemConfig( 7653): canReadFile = false
I/SystemConfig( 7653): systemFeature RCS result false
D/SystemConfig( 7653): refreshRcsSupport() :false
I/ActivityManager(  870): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7672 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  870): Killing 7433:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10053/pid_7433/cgroup.procs: No such file or directory
,I/LockScreenSettings( 7672): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7672): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7672): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7672): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7672): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7672): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  870): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7689 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 2744:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  282): 2744 died, releasing its sessions
V/AudioFlinger(  282):  pid 1739 @ 0
V/AudioFlinger(  282):  pid 3167 @ 1
V/AudioFlinger(  282):  pid 3167 @ 2
,W/libprocessgroup(  870): failed to open /acct/uid_10028/pid_2744/cgroup.procs: No such file or directory
,W/ResourcesManager( 7689): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 41 ms] updated apps [took 41 ms] 
,I/ActivityManager(  870): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7715 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 7152:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10038/pid_7152/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/Finsky  ( 7715): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7715): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7715): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7715): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7715): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3236): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3236): created cursor android.database.sqlite.SQLiteCursor@19588475 on behalf of 7715
,D/Ads     ( 7715): Skipping gmscore version check
,D/Finsky  ( 7715): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7715): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 7715): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 7715): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 6583): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6583): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 6583): Storage manager: low false usage 1.77MB avail 2.38GB capacity 4.06GB
,I/art     (  870): Explicit concurrent mark sweep GC freed 28560(1434KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.156ms total 165.256ms
,I/Icing   ( 6583): updateResources: need to parse f{com.google.android.gms}
,I/art     ( 6583): CheckpointMarkThreadRoots callback created = 0xaafdf2d0
,I/art     ( 6583): CheckpointMarkThreadRoots callback created = 0xaafdf8f0
,W/SQLiteConnectionPool( 6583): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Icing   ( 6583): Internal init done: storage state 0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 6583): Post-init done
I/Icing   ( 6583): updateResources: need to parse f{com.google.android.gms}
,I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Icing   ( 6583): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 6583): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6583): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  870): Killing 7250:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10006/pid_7250/cgroup.procs: No such file or directory
,I/CheckinService( 6583): Done disabling old GoogleServicesFramework version
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  870): Killing 7399:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7376): android.os.DeadObjectException
,W/libprocessgroup(  870): failed to open /acct/uid_10089/pid_7399/cgroup.procs: No such file or directory
W/ActivityManager(  870): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/System.err( 7376): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7376): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7376): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7376): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7376): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7376): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7376): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7376): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7376): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7376): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7376): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7376): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7376): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7376): android.os.DeadObjectException
,W/System.err( 7376): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7376): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7376): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7376): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7376): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7376): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7376): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7376): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7376): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7376): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7376): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7376): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7376): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/ActivityManager(  870): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7786 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  304): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 34.536ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 571us total 22.489ms
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.845ms
,D/UEI.SmartControl( 7786): Quickset Services start...
,I/UEI.SmartControl( 7786): Manufacture = LGE
D/UEI.SmartControl( 7786): File observer start...
E/UEI.SmartControl( 7786): IR Port is disabled: false
D/UEI.SmartControl( 7786): Starting file observer...
D/UEI.SmartControl( 7786): Extracting JNI libs...
D/UEI.SmartControl( 7786): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7786): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7786): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7786): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7786): --- Selecting new region: 2
I/UEI.SmartControl( 7786): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7786): Platform has CIR...
D/UEI.SmartControl( 7786): NO CIR support, need to check package...
I/UEI.SmartControl( 7786): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7786): QS Service created
E/UEI.SmartControl( 7786): QS start get config
,D/UEI.SmartControl( 7786): Loading JNI Libs...
,D/UEI.SmartControl( 7786):  configuring local db...
D/UEI.SmartControl( 7786):  ---- Has DB8: true
,D/UEI.SmartControl( 7786): QS start statue = true Error code = 0
D/UEI.SmartControl( 7786): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7786): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7786): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7786): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7786): IrrcClient ++ 
D/irrcClient( 7786): getIrrcService ++ 
D/irrcClient( 7786): getIrrcService -- 
D/irrcClient( 7786): IrrcClient -- 
W/irrc_jni( 7786): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7786): Services init done
,I/UEI.SmartControl( 7786): Device manager: loading config....
D/UEI.SmartControl( 7786): QS Service init finished
D/UEI.SmartControl( 7786): QS Service version name: 0.1.73
D/UEI.SmartControl( 7786): Config is loaded...
D/UEI.SmartControl( 7786): QS Service version code: 1073
D/UEI.SmartControl( 7786): Service requested: Control
D/UEI.SmartControl( 7786): -----IControl: 11
I/ActivityManager(  870): Killing 7376:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7786): Caller: com.lge.qremote
D/UEI.SmartControl( 7786): ------------ IControl registerCallback...
I/UEI.SmartControl( 7786): Registering callback...
,W/libprocessgroup(  870): failed to open /acct/uid_10106/pid_7376/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7786): Internal service binding...
D/UEI.SmartControl( 7786):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7786): Notify AllClients services are ready: 0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/charger_monitor(  485): init target 500000
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/charger_monitor(  485): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
D/WifiController(  870): battery changed pluggedType: 2
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  293): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7786): Internal timer expired: 1
,D/UEI.SmartControl( 7786): Service.onUnbind: IControl
D/UEI.SmartControl( 7786): Service.onDestroy
D/UEI.SmartControl( 7786): Shutdown IRRCPlayer... 
,W/irrc_jni( 7786): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7786): ~IrrcClient ++ 
D/irrcClient( 7786): ~IrrcClient -- 
W/irrc_jni( 7786): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7786): Blaster closed
D/UEI.SmartControl( 7786): Blaster closed
D/UEI.SmartControl( 7786): Shut down QS...
D/UEI.SmartControl( 7786): Stopped file observer...
I/UEI.SmartControl( 7786): QS lib stop result = true
D/UEI.SmartControl( 7786): QS shutdown complete
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 134681135162; DSPS: 4504653; Offset : -2793987139
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{3bc416cb type 2 when 143668 com.google.android.gms} when 143668
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1732): Vacuum at: now=1455035809763 tag=VacuumService
W/InstanceID/Rpc( 6583): Found 10006
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 45821(2MB) AllocSpace objects, 21(336KB) LOS objects, 40% free, 13MB/22MB, paused 4.239ms total 133.964ms
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 7143 seconds from now (1455035810268)
,D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  870): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  270): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  870): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  870): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  870): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  870): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  870): ALS enabled for SRE
,D/PowerManagerServiceEx(  870): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28718 ms ago)
D/qdlights(  870): set_light_backlight: 254
,D/qdlights(  870): set_light_backlight: 251
D/qdlights(  870): set_light_backlight: 247
,D/qdlights(  870): set_light_backlight: 244
,D/qdlights(  870): set_light_backlight: 241
,D/qdlights(  870): set_light_backlight: 237
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  870): set_light_backlight: 234
,D/qdlights(  870): set_light_backlight: 231
,D/qdlights(  870): set_light_backlight: 227
,D/qdlights(  870): set_light_backlight: 224
,D/qdlights(  870): set_light_backlight: 221
,D/qdlights(  870): set_light_backlight: 217
,D/qdlights(  870): set_light_backlight: 214
,D/qdlights(  870): set_light_backlight: 211
,D/qdlights(  870): set_light_backlight: 207
,D/qdlights(  870): set_light_backlight: 204
,D/qdlights(  870): set_light_backlight: 201
,D/qdlights(  870): set_light_backlight: 197
,D/qdlights(  870): set_light_backlight: 194
,D/qdlights(  870): set_light_backlight: 191
,D/qdlights(  870): set_light_backlight: 187
,D/qdlights(  870): set_light_backlight: 184
,D/qdlights(  870): set_light_backlight: 181
,D/qdlights(  870): set_light_backlight: 177
,D/qdlights(  870): set_light_backlight: 174
,D/qdlights(  870): set_light_backlight: 171
,D/qdlights(  870): set_light_backlight: 167
,D/qdlights(  870): set_light_backlight: 164
,D/qdlights(  870): set_light_backlight: 161
,D/qdlights(  870): set_light_backlight: 157
,D/qdlights(  870): set_light_backlight: 154
,D/qdlights(  870): set_light_backlight: 151
,D/qdlights(  870): set_light_backlight: 147
,D/qdlights(  870): set_light_backlight: 144
,D/qdlights(  870): set_light_backlight: 141
,D/qdlights(  870): set_light_backlight: 137
,D/qdlights(  870): set_light_backlight: 134
,D/qdlights(  870): set_light_backlight: 131
,D/qdlights(  870): set_light_backlight: 127
,D/qdlights(  870): set_light_backlight: 124
,D/qdlights(  870): set_light_backlight: 121
,D/qdlights(  870): set_light_backlight: 117
,D/qdlights(  870): set_light_backlight: 114
,D/qdlights(  870): set_light_backlight: 111
,D/qdlights(  870): set_light_backlight: 107
,D/qdlights(  870): set_light_backlight: 104
,D/qdlights(  870): set_light_backlight: 101
,D/qdlights(  870): set_light_backlight: 97
,D/qdlights(  870): set_light_backlight: 94
,D/qdlights(  870): set_light_backlight: 91
,D/qdlights(  870): set_light_backlight: 87
,D/qdlights(  870): set_light_backlight: 84
,D/qdlights(  870): set_light_backlight: 81
,D/qdlights(  870): set_light_backlight: 77
,D/qdlights(  870): set_light_backlight: 74
,D/qdlights(  870): set_light_backlight: 71
,D/qdlights(  870): set_light_backlight: 67
,D/qdlights(  870): set_light_backlight: 64
,D/qdlights(  870): set_light_backlight: 61
,D/qdlights(  870): set_light_backlight: 57
,D/qdlights(  870): set_light_backlight: 54
,D/qdlights(  870): set_light_backlight: 51
,D/qdlights(  870): set_light_backlight: 47
,D/qdlights(  870): set_light_backlight: 44
,D/qdlights(  870): set_light_backlight: 41
,D/qdlights(  870): set_light_backlight: 37
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  870): set_light_backlight: 34
,D/qdlights(  870): set_light_backlight: 31
,D/qdlights(  870): set_light_backlight: 27
,D/qdlights(  870): set_light_backlight: 24
,D/qdlights(  870): set_light_backlight: 21
,D/qdlights(  870): set_light_backlight: 17
,D/qdlights(  870): set_light_backlight: 14
,D/qdlights(  870): set_light_backlight: 11
,D/qdlights(  870): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/PowerManagerServiceEx(  870): acquireWakeLockInternal: lock=713373693, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=870
,D/WeatherService( 2728): 2 : TimeTick Intent has been received, Time(hour:min:sec) 17:37:0
D/WeatherService( 2728): 2 : TimeTick Intent And Screen On
D/WeatherService( 2728): 2 : SDK version : 21
W/ActivityManager(  870): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2728): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2728): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2728): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2728): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2728): 2 : This is isUpdating : false
D/WeatherService( 2728): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2728): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2728): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2728): 2 : Fixed theme : optimus
D/WeatherReflect( 2728): 2 : Map key string is -2
,D/lim     ( 2728): 2 : time = 17:37
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
,I/WeatherReflect( 2728): Model Name : LG-D722
D/WeatherTheme( 2728): 2 : Different view - status_min_formatted : 36 != 37
D/WeatherTheme( 2728): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
D/WeatherReflect( 2728): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2728): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/Weather4x2_optimus( 2728): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2728): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2728): forecast size is 0
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2728): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2728): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2728): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2728): url is : null
D/Theme   ( 2728): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2728): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2728): 2 : update view, appWidgetId: 2
D/WeatherService( 2728): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 17:37:0
,D/PowerManagerServiceEx(  870): releaseWakeLockInternal: lock=713373693 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 154681667968; DSPS: 5160030; Offset : -2793973079
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  870): ALS enabled for SRE
D/PowerManagerServiceEx(  870): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35705 ms ago)
I/PowerManagerService(  870): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  870): ALS enabled for SRE
D/PowerManagerServiceEx(  870): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35717 ms ago)
W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  870): Sleeping (uid 1000)...
D/LPWGController(  870): [updateScreenState] screen on = false
D/LPWGController(  870): disable proximity sensor
D/LPWGController(  870): enable proximity sensor
I/SensorManager(  870): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3add1433] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  870): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  870): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  870): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  870): activate: handle is 48, enable
V/sensors_hal_Ctx(  870): activate sensors is 1400000000000
D/sensors_hal_Thresh(  870): enable: handle=48
I/sensors_hal_SAM(  870): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  870): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  870): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  870): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  870): enable: Received response: 0
D/PowerManagerServiceEx(  870): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35765 ms ago)
I/Adreno-EGL(  870): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  870): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  870): Build Date: 03/02/15 Mon
I/Adreno-EGL(  870): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  870): Remote Branch: 
I/Adreno-EGL(  870): Local Patches: 
I/Adreno-EGL(  870): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1057 us)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Sensors (  421): sns_pwr.c(273):acquiring wakelock
V/sensors_hal_SAM(  870): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  870): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  870): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  870): processInd: handle 48, count=1
V/sensors_hal_Thresh(  870): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  870): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  870): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  870): poll: count: 256
I/sensors_hal_Ctx(  870): poll: released wakelock sensor_ind
D/sensors_hal_Util(  870): waitForResponse: timeout=0
D/LPWGController(  870): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  870): current mode = 1  value = 1 1
I/LPWGController(  870): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  870): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  870): set_light_backlight: 0
,I/SensorManager(  870): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  870): activate: handle is 46, disable
V/sensors_hal_Ctx(  870): activate sensors is 1000000000000
,D/sensors_hal_LP2(  870): enable: handle=46
D/sensors_hal_LP2(  870): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  870): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
I/DisplayManagerService(  870): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  870): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  870): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  870): Display changed displayId=0
,D/DSDPConnection( 1739): Display #0 changed.
,D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  870): Excessive delay in setPowerMode(): 240ms
I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  870): Got set_interactive hint
D/KeyguardViewMediator( 1371): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
D/KeyguardViewMediator( 1371): notifyScreenOffLocked
,D/KeyguardViewMediator( 1371): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1371): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1371): unregisterProximitySensor
,D/StatusBarWindowView( 1371): onScreenTurnedOff why = 3
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/WifiServerServiceExt(  870): sendKtScanInterval  mRtspPlay : false
V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 870
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
V/voice   (  282): voice_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
,V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  282): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/GpsLocationProvider(  870): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:true
,I/WifiServerServiceExt(  870): set CMD_KT_SCAN_INTERVAL
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1801): stopPatternFlashing()
D/Cliptray Service( 1801): lockStatus = 0
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): updateLightsLocked : turn off led
D/LNfcService( 1784): action : android.intent.action.SCREEN_ON
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1801): RESTART MSG
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
,D/NfcService( 1784): Discovery configuration equal, not updating.
D/Ulp_jni (  870): JNI:system_update. Event-0
D/SplitWindow(  870): check instance of lgWin Window{3d0fe3ee u0 SearchPanel}
,D/InputDispatcher(  870): Window went away: Window{39d7dcd5 u0 SearchPanel}
I/[SystemUI]Clock( 1371): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1371): time changed, timezoneChanged : false
,V/PhoneApp( 1739): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2728): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:37:2
,D/WeatherService( 2728): 2 : ACTION screen on
D/WeatherService( 2728): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2728): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2728): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 17:37:2
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): ACTION_SCREEN_ON
D/AppCleanupService( 4037): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 870
,D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
D/WifiController(  870): CMD_SCREEN_OFF 
D/WifiController(  870): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  870): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:false
,I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1801): clear
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1801): updateLightsLocked : turn on led
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1801): Can't handle this request of patternId:0
D/LNfcService( 1784): action : android.intent.action.SCREEN_OFF
D/LEDHandler( 1801): RESTART MSG
D/NfcServiceNXP( 1784): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1876): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1739): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2728): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:37:3
,D/WeatherService( 2728): 2 : ACTION screen off
,D/WeatherService( 2728): 2 : TimeTick Receiver Unregister
D/WeatherService( 2728): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 17:37:3
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): ACTION_SCREEN_OFF
D/AppCleanupService( 4037): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4037): AppUsageStatsSaveTask
,E/NxpNfcJni( 1784): getReconnectState = 0x0
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
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
,E/NxpNfcJni( 1784): getReconnectState = 0x0
,I/Sensors (  421): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1371): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{f4ac08f type 2 when 161679 com.android.systemui} when 161679
,D/PhoneUtils( 1739): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1739): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1739): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1739): getCallState : 0
,D/PhoneUtils( 1739): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1739): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1739): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1371): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1371): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 174682369002; DSPS: 5815414; Offset : -2794003999
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{719bf1c type 2 when 182332 android} when 182332
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{9d91725 type 2 when 187128 com.google.android.gms} when 187128
,D/charger_monitor(  485): init target 500000
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
D/WifiController(  870): battery changed pluggedType: 2
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 194683051129; DSPS: 6470796; Offset : -2793993310
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 214683764872; DSPS: 7126180; Offset : -2794012249
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 234684439187; DSPS: 7781562; Offset : -2794009529
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  485): init target 500000
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 254685191887; DSPS: 8436946; Offset : -2793989095
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 274685937869; DSPS: 9092331; Offset : -2794006079
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # multiplex can send data
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 22 String should be length:200
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # enqueue and run in order
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 23 firstPromise setTimeout
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 24 firstPromise result
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 25 firstPromise testValue
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 26 secondPromise setTimeout
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 27 secondPromise result
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 28 secondPromise testValue
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 29 thirdPromise in promise
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 30 thirdPromise result
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 31 thirdPromise testValue
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # basic
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 32 sane
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # another
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 33 sane
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 34 should be equal
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 35 null
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 36 (unnamed assert)
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 37 should be equal
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 38 should not throw
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 39 (unnamed assert)
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 40 (unnamed assert)
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 41 should not throw
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 42 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 43 should be equal
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 44 should be equal
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # failed to get mobile documents path
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 45 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 46 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 47 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 48 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #init should register the networkChanged event
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 49 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #startBroadcasting should throw on null device name
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 50 should throw
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 51 should throw
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 52 should throw
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 53 should throw
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #startBroadcasting should throw on negative port
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 54 should throw
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #startBroadcasting should throw on too large port
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 55 should throw
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 56 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 57 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 58 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 59 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 60 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 61 should be equal
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 62 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 63 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 64 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 65 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 66 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 67 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 68 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 69 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 70 should be equal
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 71 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 72 should be equal
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 73 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 74 should be equal
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #start should fail if called twice in a row
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 75 specific error should be received
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 76 specific error should be returned
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 77 error should be null
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 78 error should be null
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 79 error should be null
I/jxcore-log( 5472): 
I/jxcore-log( 5472): ok 80 error should be null
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 81 error should be null
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 82 error should be null
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): ok 83 specific error should be returned
I/jxcore-log( 5472): 
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # setup
I/jxcore-log( 5472): 
,I/jxcore-log( 5472): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5472): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20a693a4 added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035954842.5472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035954842.5472","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035954842.5472, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035954842.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: {"pi":"F8:95:C7:87:85:54","pn":"1455035954842.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455035954842.5472","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5472): getBluetoothService() called with no BluetoothManagerCallback
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035954842.5472, mode: WIFI
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8671c860 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-5ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@8671c860 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/LGWifiP2pService(  870): P2pEnabledState add service
,I/io.jxcore.node.ConnectionHelper( 5472): start: OK
I/jxcore-log( 5472): ok 84 Should be able to call startBroadcasting without error
I/jxcore-log( 5472): 
I/io.jxcore.node.ConnectionHelper( 5472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: NOT_STARTED
D/LGWifiP2pService(  870): add a new client
,I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5472): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: NOT_INITIALIZED
I/bt-btif ( 1983): BTA_JvCreateRecordByUser
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5472): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: NOT_STARTED
I/jxcore-log( 5472): ok 85 Should be able to call stopBroadcasting without error
I/jxcore-log( 5472): 
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: NOT_STARTED
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@128b4610 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local service added successfully
,D/LGBluetoothServiceAdapter( 1983): [BTUI] createSocketChannel FD=87 mFd=85
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  870): discovery change broadcast true
D/LGWifiP2pService(  870): InactiveState{ when=-13ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-13ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: STARTED
,D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955025.5472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
I/bt-btif ( 1983): BTA_JvRfcommStartServer
,D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 2803): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1801): Event [CTRL-EVENT-SCAN-STARTED ]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  870): remove client information from framework
D/LGWifiP2pService(  870): InactiveState{ when=-40ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2803): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955025.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): startListeningForIncomingConnections: Starting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: RUNNING
,D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/LGWifiP2pService(  870): InactiveState{ when=-47ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  870): P2pEnabledState{ when=-47ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service request
D/LGWifiP2pService(  870): InactiveState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5472): Service requests cleared successfully
D/LGWifiP2pService(  870): P2pEnabledState{ when=-6ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955025.5472, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): bind: Binding a new listener
W/BluetoothAdapter( 5472): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/bt-btif ( 1983): BTA_JvCreateRecordByUser
I/bt-btif ( 1983): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 1983): [BTUI] createSocketChannel FD=88 mFd=87
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Waiting for incoming connections...
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955025.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: {"pi":"F8:95:C7:87:85:54","pn":"1455035955025.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455035955025.5472","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fb00d16c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@fb00d16c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState add service
D/LGWifiP2pService(  870): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955025.5472, mode: WIFI
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 2803): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 5472): ok 86 Should be able to call startBroadcasting without error
I/jxcore-log( 5472): 
D/LGWifiP2pService(  870): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/bt-btif ( 1983): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/bt-btif ( 1983): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnecto,rlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5472): stopProvideBluetoothMacAddressMode
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): stop: Stopping services
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2803): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery started successfully
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
,D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): release: No more listeners, de-initializing...
D/LGWifiP2pService(  870): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local services cleared successfully
D/LGWifiP2pService(  870): InactiveState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): discovery change broadcast false
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5472): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5472): Service requests cleared successfully
I/jxcore-log( 5472): ok 87 Should be able to call stopBroadcasting without error
I/jxcore-log( 5472): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise TX power level: 1, 
V/org.tha,liproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dc6b33c added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955104.5472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955104.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5472): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1983): BTA_JvCreateRecordByUser
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955104.5472, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): bind: Binding a new listener
I/bt-btif ( 1983): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Waiting for incoming connections...
,D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955104.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: {"pi":"F8:95:C7:87:85:54","pn":"1455035955104.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455035955104.5472","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@afa01ef0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@afa01ef0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState add service
D/LGWifiP2pService(  870): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: true
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955104.5472, mode: WIFI
I/wpa_supplicant( 2803): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 5472): start: OK
D/LGWifiP2pService(  870): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/jxcore-log( 5472): ok 88 Should be able to call startBroadcasting without error
I/jxcore-log( 5472): 
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2803): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 5472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): onServerStopped
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): discovery change broadcast false
I/bt-btif ( 1983): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: NOT_STARTED
I/bt-btif ( 1983): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5472): stopProvideBluetoothMacAddressMode
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: RESTARTING
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: NOT_INITIALIZED
D/LGWifiP2pService(  870): remove client information from framework
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/,org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: No more listeners, de-initializing...
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5472): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5472): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5472): ok 89 Should be able to call stopBroadcasting without error
I/jxcore-log( 5472): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ee9c728 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955159.5472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955159.5472","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5472): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5472): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1983): BTA_JvCreateRecordByUser
I/bt-btif ( 1983): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955159.5472, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955159.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: {"pi":"F8:95:C7:87:85:54","pn":"1455035955159.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455035955159.5472","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a4b845dc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a4b845dc target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState add service
D/LGWifiP2pService(  870): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955159.5472, mode: WIFI
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2803): p2p0: P2P: Reject scan trigger since one is already pending
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  870): discovery change broadcast true
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: RUNNING_WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2803): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 5472): ok 90 Should be able to call startBroadcasting without error
I/jxcore-log( 5472): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper( 5472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): Shutting down...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): shutdown
I/bt-btif ( 1983): BTA_JvDeleteRecord
I/bt-btif ( 1983): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5472): stopProvideBluetoothMacAddressMode
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): stop: Stopping P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5472): clear
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  870): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local services cleared successfully
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 5472): ok 91 Should be able to call stopBroadcasting without error
I/jxcore-log( 5472): 
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service request
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5472): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a82dd4 added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee,
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee,
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955207.5472
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955207.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): startListeningForIncomingConnections,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: OK,
I/io.jxcore.node.ConnectionHelper( 5472): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0,
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5472): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955207.5472, mode: WIFI,
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): bind: Binding a new listener
I/bt-btif ( 1983): BTA_JvCreateRecordByUser,
I/bt-btif ( 1983): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Waiting for incoming connections...
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955207.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: {"pi":"F8:95:C7:87:85:54","pn":"1455035955207.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455035955207.5472","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a46e74e8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a46e74e8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState add service
D/LGWifiP2pService(  870): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955207.5472, mode: WIFI
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5472): ok 92 Should be able to call startBroadcasting without error
I/jxcore-log( 5472): 
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-2ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2803): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 5472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): stop: Stopping Bluetooth...
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): shutdown
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): onServerStopped
I/bt-btif ( 1983): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: 1 listener(s) left
I/bt-btif ( 1983): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: NOT_STARTED
D/LGWifiP2pService(  870): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5472): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: NOT_INITIALIZED
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): release: No more listeners, de-initializing...
D/LGWifiP2pService(  870): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5472): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  870): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local services cleared successfully
D/LGWifiP2pService(  870): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2803): P2P-FIND-STOPPED 
I/jxcore-log( 5472): ok 93 Should be able to call stopBroadcasting without error
I/jxcore-log( 5472): 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/LGWifiP2pS,ervice(  870): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): discovery change broadcast false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3445340 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
D/LGWifiP2pService(  870): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler },
D/LGWifiP2pService(  870): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5472): Service requests cleared successfully
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true,
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955256.5472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955256.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5472): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955256.5472, mode: WIFI
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): bind: Binding a new listener
I/bt-btif ( 1983): BTA_JvCreateRecordByUser
I/bt-btif ( 1983): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Waiting for incoming connections...
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955256.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: {"pi":"F8:95:C7:87:85:54","pn":"1455035955256.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455035955256.5472","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@657ce460 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@657ce460 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: INITIALIZED
D/LGWifiP2pService(  870): add a new client
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955256.5472, mode: WIFI
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 2803): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  870): discovery change broadcast true
,I/jxcore-log( 5472): ok 94 Should be able to call startBroadcasting without error
I/jxcore-log( 5472): 
I/io.jxcore.node.ConnectionHelper( 5472): stop
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): onServerStopped
I/bt-btif ( 1983): BTA_JvDeleteRecord
I/bt-btif ( 1983): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5472): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: No more listeners, de-initializing...
D/LGWifiP2pService(  870): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5472): clear
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local services cleared successfully
I/wpa_supplicant( 2803): P2P-FIND-STOPPED 
I/io.jxcore,.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: NOT_STARTED
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/LGWifiP2pService(  870): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service request
I/jxcore-log( 5472): ok 95 Should be able to call stopBroadcasting without error
I/jxcore-log( 5472): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5472): Service requests cleared successfully
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): discovery change broadcast false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26bb636c added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955304.5472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
,D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): initialize: My bluetooth address is F8:95:C7:87:85:54,
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955304.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): setConnectionTimeout: 15000,
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5472): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1983): BTA_JvCreateRecordByUser
,I/bt-btif ( 1983): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955304.5472, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955304.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: {"pi":"F8:95:C7:87:85:54","pn":"1455035955304.5472","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455035955304.5472","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6533136c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6533136c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState add service
D/LGWifiP2pService(  870): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: true
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955304.5472, mode: WIFI
I/wpa_supplicant( 2803): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/LGWifiP2pService(  870): discovery change broadcast true
,I/jxcore-log( 5472): ok 96 Should be able to call startBroadcasting without error
I/jxcore-log( 5472): 
,I/io.jxcore.node.ConnectionHelper( 5472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): shutdown
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 1983): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: 1 listener(s) left
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: NOT_STARTED
I/bt-btif ( 1983): BTA_JvRfcommStopServer
I/wpa_supplicant( 2803): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5472): stopProvideBluetoothMacAddressMode
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): release: No more listeners, de-initializing...
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: No more listeners, de-initializing...
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5472): clear
,D/LGWifiP2pService(  870): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  870): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local services cleared successfully
I/jxcore-log( 5472): ok 97 Should be able to call stopBroadcasting without error
I/jxcore-log( 5472): 
D/LGWifiP2pService(  870): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Maximum number of connection attempt retries: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/LGWifiP2pService(  870): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-4ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service request
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1bb14a58 added. We now have 9 listener(s)
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5472): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955356.5472
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955356.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955356.5472, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): bind: Binding a new listener
,W/BluetoothAdapter( 5472): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: State changed to 2
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/bt-btif ( 1983): BTA_JvCreateRecordByUser
I/bt-btif ( 1983): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955356.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: {"pi":"F8:95:C7:87:85:54","pn":"1455035955356.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455035955356.5472","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c0465e9e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@c0465e9e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState add service
D/LGWifiP2pService(  870): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955356.5472, mode: WIFI
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2803): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  870): discovery change broadcast true
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 5472): ok 98 Should be able to call startBroadcasting without error
I/jxcore-log( 5472): 
I/io.jxcore.node.ConnectionHelper( 5472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): onServerStopped
I/bt-btif ( 1983): BTA_JvDeleteRecord
I/bt-btif ( 1983): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5472): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5472): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  870): remove client information from framework
D/LGWifiP2pService(  870): InactiveState{ when=-3ms what=139268, arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local services cleared successfully
I/wpa_supplicant( 2803): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
I/jxcore-log( 5472): ok 99 Should be able to call stopBroadcasting without error
I/jxcore-log( 5472): 
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): discovery change broadcast false
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/LGWifiP2pService(  870): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Scan mode: 1
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5472): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f1cb404 added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955410.5472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955410.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5472): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955410.5472, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): bind: Binding a new listener
I/bt-btif ( 1983): BTA_JvCreateRecordByUser
I/bt-btif ( 1983): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955410.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: {"pi":"F8:95:C7:87:85:54","pn":"1455035955410.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455035955410.5472","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ac0a5a70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@ac0a5a70 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState add service
D/LGWifiP2pService(  870): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955410.5472, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5472): start: OK
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 2803): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  870): discovery change broadcast true
I/jxcore-log( 5472): ok 100 Should be able to call startBroadcasting without error
I/jxcore-log( 5472): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139268 arg2=3 target=c,om.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2803): P2P-FIND-STOPPED 
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): discovery change broadcast false
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): onServerStopped
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 1983): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: 1 listener(s) left
I/bt-btif ( 1983): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5472): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): stop: Stopping services
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  870): remove client information from framework
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: No more listeners, de-initializing...
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5472): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/LGWifiP2pService(  870): InactiveState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-1ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5472): Service requests cl,eared successfully
I/jxcore-log( 5472): ok 101 Should be able to call stopBroadcasting without error
I/jxcore-log( 5472): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5472): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24b30c70 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(712340952)( 1983): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@69bd7ee
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5472): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955470.5472
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955470.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5472): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1983): BTA_JvCreateRecordByUser
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955470.5472, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): bind: Binding a new listener
I/bt-btif ( 1983): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5472): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455035955470.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: {"pi":"F8:95:C7:87:85:54","pn":"1455035955470.5472","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455035955470.5472","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@48404e4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@48404e4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState add service
D/LGWifiP2pService(  870): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
I/io.jxcore.node.ConnectionHelper( 5472): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455035955470.5472, mode: WIFI
,D/BluetoothManagerService(  870): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  870): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5472): ok 102 Should be able to call startBroadcasting without error
I/jxcore-log( 5472): 
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5472): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5472): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5472): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local service added successfully
I/bt-btif ( 1983): BTA_JvDeleteRecord
I/bt-btif ( 1983): BTA_JvRfcommStopServer
I/wpa_supplicant( 2803): p2p0: P2P: Reject scan trigger since one is already pending
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: 1 listener(s) left
D/WfdsMonitor( 1801): Event [P2P: Reject scan trigger since one is already pending]
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5472): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5472): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5472): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 5472): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: NOT_INITIALIZED
D/LGWifiP2pService(  870): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5472): release: No more listeners, de-initializing...
,D/LGWifiP2pService(  870): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2803): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5472): release: No more listeners, de-initializing...
D/WfdsMonitor( 1801): Event [P2P-FIND-STOPPED ]
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5472): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5472): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5472): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  870): InactiveState{ when=-3ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-3ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service
I/jxcore-log( 5472): ok 103 Should be able to call stopBroadcasting without error
I/jxcore-log( 5472): 
D/LGWifiP2pService(  870): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5472): Local services cleared successfully
D/LGWifiP2pService(  870): InactiveState{ when=-5ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5472): P2P device discovery stopped successfully
D/LGWifiP2pService(  870): InactiveState{ when=-6ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=-6ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5472): Service requests cleared successfully
,D/LGWifiP2pService(  870): InactiveState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  870): P2pEnabledState{ when=-5ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): discovery change broadcast false
I/jxcore-log( 5472): # teardown
I/jxcore-log( 5472): 
I/Netd    (  270): M: Get netlink event, ifname: p2p0 action: 4
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 294690535310; DSPS: 9747841; Offset : -2793987837
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  485): init target 500000
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 314691215927; DSPS: 10403224; Offset : -2794007353
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 334691906232; DSPS: 11058606; Offset : -2793988618
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  870): remove 34763483
D/LocationManagerService(  870): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  870): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  870): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  870): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  870): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  870): acquireWakeLockInternal: lock=713373693, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=870
,D/PowerManagerServiceEx(  870): releaseWakeLockInternal: lock=713373693 [*alarm*], flags=0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 354692554089; DSPS: 11713987; Offset : -2793983400
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 374693236790; DSPS: 12369370; Offset : -2794002448
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 394693994230; DSPS: 13024755; Offset : -2794006098
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 414694740003; DSPS: 13680139; Offset : -2793992904
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 434695420829; DSPS: 14335521; Offset : -2793983803
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 454696154675; DSPS: 14990906; Offset : -2794014016
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 474696819668; DSPS: 15646287; Offset : -2793988746
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 494697592681; DSPS: 16301673; Offset : -2794008930
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 514698438819; DSPS: 16957060; Offset : -2793988120
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 534699187301; DSPS: 17612445; Offset : -2794001094
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 554699852502; DSPS: 18267827; Offset : -2794007540
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 574700817130; DSPS: 18923218; Offset : -2793988801
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 594701558737; DSPS: 19578603; Offset : -2794010159
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 614702235761; DSPS: 20233985; Offset : -2794004808
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  870): acquireWakeLockInternal: lock=713373693, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=870
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{1a496c27 type 2 when 621116 android} when 621116
D/PowerManagerServiceEx(  870): releaseWakeLockInternal: lock=713373693 [*alarm*], flags=0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 634702991742; DSPS: 20889370; Offset : -2794011585
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 654703721839; DSPS: 21544754; Offset : -2794014039
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 674704460112; DSPS: 22200138; Offset : -2794007901
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 694705177970; DSPS: 22855521; Offset : -2793992001
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 714705915670; DSPS: 23510905; Offset : -2793986643
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 734706595246; DSPS: 24166288; Offset : -2794009155
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 754707343467; DSPS: 24821672; Offset : -2793993616
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 774708104605; DSPS: 25477057; Offset : -2793995104
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 794708781889; DSPS: 26132439; Offset : -2793988843
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 814709517871; DSPS: 26787824; Offset : -2794015774
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 834710455781; DSPS: 27443214; Offset : -2793994043
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 854711131554; DSPS: 28098596; Offset : -2793989343
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 874711927485; DSPS: 28753982; Offset : -2793986844
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 894712740549; DSPS: 29409369; Offset : -2793997547
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 914713418251; DSPS: 30064751; Offset : -2793991648
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 934714074649; DSPS: 30720133; Offset : -2794006428
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  870): acquireWakeLockInternal: lock=713373693, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=870
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{1d611ed4 type 2 when 951442 com.android.bluetooth} when 951442
I/ActivityManager(  870): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8073 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,W/bt-smp  ( 1983): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1983): Plain text(LSB ~ MSB) = b3 de 64 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1983): Encrypted text(LSB ~ MSB) = 99 a3 b6 17 1e b7 13 d2 80 99 c4 15 cd 99 2a 2e 
W/bt-btm  ( 1983): Stopping oneshot timer
,I/DigitalAppWidgetProvider( 8073): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8073): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1102233e
I/ActivityManager(  870): Killing 7598:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/PowerManagerServiceEx(  870): releaseWakeLockInternal: lock=713373693 [*alarm*], flags=0x0
W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_7598/cgroup.procs: No such file or directory
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 954714820683; DSPS: 31375517; Offset : -2793993466
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 974715506092; DSPS: 32030900; Offset : -2794009207
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{5b6e87d type 2 when 989548 com.google.android.gms} when 989548
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 994716249782; DSPS: 32686284; Offset : -2793998173
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1014716997587; DSPS: 33341669; Offset : -2794013125
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1034717673829; DSPS: 33997051; Offset : -2794008844
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1054718421998; DSPS: 34652435; Offset : -2793992705
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1074719246158; DSPS: 35307822; Offset : -2793992728
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1094719939639; DSPS: 35963205; Offset : -2794000656
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1114720890466; DSPS: 36618596; Offset : -2793996057
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1134721594052; DSPS: 37273979; Offset : -2793994402
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1154722261596; DSPS: 37929361; Offset : -2793998504
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1174723002317; DSPS: 38584745; Offset : -2793989606
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1194723731633; DSPS: 39240129; Offset : -2793992764
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1214724485219; DSPS: 39895514; Offset : -2794002144
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  870): User[0] Flushing usage stats to disk
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1234725150368; DSPS: 40550896; Offset : -2794008746
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1254725878225; DSPS: 41206280; Offset : -2794013520
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  485): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1983): Disconnected process message: 10, size: 0
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1274726550508; DSPS: 41861662; Offset : -2794012181
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 8153): 
D/AndroidRuntime( 8153): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8153): CheckJNI is OFF
D/AndroidRuntime( 8153): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  870): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  870): Killing 5472:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  870): WIN DEATH: Window{240e287e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  870): Focus left window: Window{240e287e u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  870): Window went away: Window{240e287e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  870): Skipping PackageSetting{3d4e91e com.example.hello/10317} due to missing metadata
I/bt-btif ( 1983): BTA_JvDeleteRecord
I/bt-btif ( 1983): BTA_JvRfcommStopServer
I/ActivityManager(  870):   Force finishing activity ActivityRecord{2779219c u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  870): Display changed displayId=0
D/DSDPConnection( 1739): Display #0 changed.
W/ActivityManager(  870): Spurious death for ProcessRecord{37654372 5472:com.test.thalitest/u0a316}, curProc for 5472: null
I/ActivityManager(  870): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3591): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/[LGHome]EVENT( 1876): [Launcher.java:5203:onStart()]onStart
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
W/System.err( 3591): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3591): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3591): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3591): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3591): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3591): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3591): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3591): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3591): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3591): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3591): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  870): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  870): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8180 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1876): [Launcher.java:776:onResume()]onResume
I/art     ( 1939): Explicit concurrent mark sweep GC freed 21941(1370KB) AllocSpace objects, 3(71KB) LOS objects, 39% free, 11MB/19MB, paused 3.989ms total 147.716ms
I/[LGHome]EVENT( 1876): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1876): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1876): [Launcher.java:929:onResume()]onResume end
I/Activity( 1876): Activity.onPostResume() called 
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1876): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1876): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 1371): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1371): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework](  870): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourcesManager( 1371): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/InputDispatcher(  870): Focus entered window: Window{3c073ff5 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  870): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  870): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  870): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  870): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1adedb60,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  870): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  870): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  870): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  870): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  870): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  870): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1adedb60,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  870): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourcesManager( 1371): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1371): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1371): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/art     (  870): Explicit concurrent mark sweep GC freed 78326(4MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 23MB/35MB, paused 24.619ms total 286.196ms
I/art     (  870): WaitForGcToComplete blocked for 256.085ms for cause Explicit
W/ResourcesManager( 8180): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8180): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8180): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1876): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1371): handleShortcutListChanged...
W/InputMethodManagerService(  870): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  870): Got RemoteException sending setActive(false) notification to pid 5472 uid 10316
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): handleShortcutListChanged...
D/administrator(  870): Handling package changes for user 0
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/Timeline(  870): Timeline: Activity_windows_visible id: ActivityRecord{1b023537 u0 com.lge.launcher2/.Launcher t221} time:1292744
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/LGEmail ( 8180): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/IInputConnectionWrapper( 1876): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LGEmail ( 8180): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
E/b       ( 1600): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1876): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
I/NotificationService(  870): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  870): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  870): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/TaskPersister(  870): removeObsoleteFile: deleting file=222_task.xml
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
I/art     (  870): Explicit concurrent mark sweep GC freed 8850(520KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 7.653ms total 435.827ms
I/PackageChangeReceiver( 8180): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8212 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  870): Killing 7563:com.google.android.talk/u0a61 (adj 15): empty #11
D/AndroidRuntime( 8153): Shutting down VM
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
W/libprocessgroup(  870): failed to open /acct/uid_10061/pid_7563/cgroup.procs: No such file or directory
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppUp4:AppBoxCP( 8212): onCreate
W/AppUp4:DB( 8212):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 8212):  setFingerPrint start
I/AppUp4:DB( 8212):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8212):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8212):  SDK version = 0
I/AppUp4:DB( 8212):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8212): AppBoxApplication onCreate()
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
D/AppUp4:PreloadHelper( 8212): added Exclude : com.test.thalitest
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  870): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8229 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  870): Killing 7626:com.android.gallery3d/u0a23 (adj 15): empty #11
I/Timeline( 1876): Timeline: Activity_idle id: android.os.BinderProxy@f31bbba time:1293342
W/libprocessgroup(  870): failed to open /acct/uid_10023/pid_7626/cgroup.procs: No such file or directory
I/art     ( 1876): Explicit concurrent mark sweep GC freed 31749(1723KB) AllocSpace objects, 20(2MB) LOS objects, 40% free, 15MB/25MB, paused 953us total 75.501ms

```
