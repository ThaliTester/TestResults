#### Test 57924002d5e0b14_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,D/Finsky  ( 5523): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/Finsky  ( 5523): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 5523): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5523): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5523): com.android.vending: cancel(-1050172287) by com.android.vending
I/NotificationManager( 5523): com.android.vending: cancel(1003285959) by com.android.vending
D/Ads     ( 5523): Skipping gmscore version check
D/AndroidRuntime( 5575): 
D/AndroidRuntime( 5575): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5575): CheckJNI is OFF
--------- beginning of system
I/ActivityManager(  973): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5601 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/Finsky  ( 5523): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5523): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 5523): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  973): Killing 5301:com.google.android.partnersetup/u0a9 (adj 15): empty #11
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@2fee90a0 on behalf of 5523
W/libprocessgroup(  973): failed to open /acct/uid_10009/pid_5301/cgroup.procs: No such file or directory
W/ResourcesManager( 5601): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5601): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 5601): VM with version 2.1.0 has multidex support
I/MultiDex( 5601): install
I/MultiDex( 5601): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 5523): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 5523): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/AndroidRuntime( 5575): Calling main entry com.android.commands.am.Am
I/ActivityManager(  973): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  973): setTaskToReturnTo : TaskRecord{22eaef08 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  973): setTaskToReturnTo : TaskRecord{22eaef08 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  973): AppWindowTokenEx init.. 
D/ContextHelper(  973): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  973): Focus left window: Window{161b4714 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5575): Shutting down VM
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
V/JNIHelp ( 5601): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/SplitWindow(  973): check instance of lgWin Window{12bd5352 u0 Starting com.test.thalitest}
I/ActivityManager(  973): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5642 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1932): Closing mic
I/MicrophoneInputStream( 1932): mic_close com.google.android.apps.gsa.speech.audio.u@245f0943
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
V/AudioRecord( 1932): stop()
D/AudioRecord( 1932): AudioRecord->stop()
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
W/ActivityThread( 5601): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5601): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2ceaa183: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5601): Installed default security provider GmsCore_OpenSSL
V/AudioFlinger(  284): Record stopped OK
V/AudioPolicyManager(  284): stopInput() input 17
V/AudioPolicyService(  284): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  284): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  284): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  284): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  284): ThreadBase::setParameters() routing=0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 2
I/WindowStateAnimator(  973): Starting window displayed
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb43ad000
D/audio_hw_primary(  284): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/SystemUI[Framework](  973): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  973): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  973): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  973): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  973): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33b449b0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  973): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/NotificationManager( 5601): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5601): com.google.android.gms: cancel(39789) by com.google.android.gms
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1371): draw background and invalidate : color = 15000000
D/BarTransitions( 1371): draw background and invalidate : color = 15141414
V/audio_hw_primary(  284): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  284): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  284): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  284): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  284): disable_audio_route: exit
E/audio_hw_primary(  284): disable_snd_device: enter 144
D/hardware_info(  284): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  284): disable_snd_device: snd_device(144: lg-vr-handset-mic)
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
V/audio_hw_primary(  284): stop_input_stream: exit: status(0)
V/audio_hw_primary(  284): in_standby: exit:  status(0)
V/AudioFlinger(  284): RecordThread: loop stopping
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyManager(  284): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  284): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  284): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  284): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyService(  284): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  284): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  284): setParameters(): io 17, keyvalue hotword_active=0, calling pid 284
V/AudioFlinger(  284): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  284): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  284): in_set_parameters: exit: status(0)
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb43ad000
V/AudioFlinger(  284): RecordThread: loop stopping
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioRecord( 1932): stop()
V/AudioRecord( 1932): stop()
V/AudioRecord( 1932): stop()
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
V/AudioPolicyManager(  284): releaseInput() 17
V/AudioPolicyManager(  284): closeInput(17)
V/AudioFlinger(  284): closeInput() 17
V/AudioSystem(  284): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1371): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  973): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1932): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): ThreadBase::exit
V/AudioFlinger(  284): releasing 16 from 1932 for -1
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioSystem( 1967): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1751): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): RecordThread 0xb43ad000 exiting
V/AudioSystem( 3169): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
V/AudioSystem( 2729): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  284): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  284): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  284): in_standby: exit:  status(0)
V/AudioPolicyService(  284): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  284): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyManager(  284): releaseInput() exit
V/AudioFlinger(  284): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  284): removeClient_l() pid 1932, calling pid 284
I/HotwordRecognitionRnr( 1932): Stopping hotword detection.
D/ChimeraCfgMgr( 5601): Reading stored module config
D/PackageBroadcastService( 5601): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/HotwordRecognitionRnr( 1932): Hotword detection finished
D/ChimeraCfgMgr( 5601): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5601): Loading module APK com.google.android.play.games
D/ContextHelper( 5642): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/WebViewFactory( 5642): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5642): Time to load native libraries: 2 ms (timestamps 3615-3617)
I/LibraryLoader( 5642): Expected native library version number "",actual native library version number ""
D/NativeLibraryUtils( 5601): Install completed successfully. count=14 extracted=0
V/WebViewChromiumFactoryProvider( 5642): Binding Chromium to main looper Looper (main, tid 1) {29e84c4b}
I/LibraryLoader( 5642): Expected native library version number "",actual native library version number ""
I/chromium( 5642): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/art     ( 5601): CheckpointMarkThreadRoots callback created = 0xb042d4a0
I/BrowserStartupController( 5642): Initializing chromium process, singleProcess=true
W/art     ( 5642): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5642): ApplicationContext is null in ApplicationStatus
I/art     ( 5601): CheckpointMarkThreadRoots callback created = 0xb042d480
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
V/AudioPolicyService(  284): registerClient() client 0xb3846e20, uid 10316
D/ChimeraCfgMgr( 5601): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/BluetoothManagerService(  973): Message: 20
D/BluetoothManagerService(  973): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@122d9f4e:true
D/BluetoothAdapterService(544039463)( 1967): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@ab25035
,D/ChimeraModuleLdr( 5601): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 5601): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5601): Submit a task: k
,I/PeopleDatabaseHelper( 5601): cleanUpNonGplusAccounts done.
D/ChimeraCfgMgr( 5601): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5601): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 5601): Processing package: com.test.thalitest
,D/GassUtils( 5601): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5601): Found info for package com.test.thalitest in db.
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
E/MDM     ( 1732): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/Icing   ( 5601): Storage manager: low false usage 1.77MB avail 2.37GB capacity 4.06GB
,D/LocationInitializer( 5601): Restart initialization of location
W/BaseAppContext( 5601): Using Auth Proxy for data requests.
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,W/art     ( 5642): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5642): onDetachedFromWindow called when already detached. Ignoring
,I/art     ( 5601): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5601): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/SystemWebViewEngine( 5642): CordovaWebView is running on device made by: LGE
,I/ActivityManager(  973): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5716 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/art     ( 5642): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5642): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 347us total 21.221ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 321us total 26.984ms
,E/BaseAppContext( 5601): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 5601): Using Auth Proxy for data requests.
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 22.286ms
,I/Activity( 5642): Activity.onPostResume() called 
,D/OpenGLRenderer( 5642): Render dirty regions requested: true
I/OpenGLRenderer( 5642): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5642): Enabling debug mode 0
W/BaseAppContext( 5601): Using Auth Proxy for data requests.
,D/Atlas   ( 5642): Validating map...
W/BaseAppContext( 5601): Using Auth Proxy for data requests.
,D/SplitWindow(  973): check instance of lgWin Window{82ae3c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
E/Icing   ( 5601): Array storage bad crc 623832639 vs 1502658010
W/BaseAppContext( 5601): Using Auth Proxy for data requests.
W/BaseAppContext( 5601): Using Auth Proxy for data requests.
W/chromium( 5642): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,E/Icing   ( 5601): Array storage bad crc 1075988376 vs 2100516220
,W/BaseAppContext( 5601): Using Auth Proxy for data requests.
W/IcingInternalCorpora( 5601): getNumBytesRead when not calculated.
,D/InputDispatcher(  973): Focus entered window: Window{82ae3c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
E/Icing   ( 5601): Array storage bad crc 2768229568 vs 474198949
E/Icing   ( 5601): Trie mmap suffix failed
,W/InputMethodManagerService(  973): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  973): Displayed com.test.thalitest/.MainActivity: +1s374ms
I/Timeline(  973): Timeline: Activity_windows_visible id: ActivityRecord{1b0c66a1 u0 com.test.thalitest/.MainActivity t222} time:84474
I/Timeline( 5642): Timeline: Activity_idle id: android.os.BinderProxy@190b9b96 time:84492
,W/Icing   ( 5601): Docstore bad crc 0xe5f4c39e vs 0x2a5cbd13
,W/BindingManager( 5642): Cannot call determinedVisibility() - never saw a connection for the pid: 5642
,W/ActivityManager(  973): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     ( 5601): Background sticky concurrent mark sweep GC freed 15926(1450KB) AllocSpace objects, 14(224KB) LOS objects, 11% free, 12MB/14MB, paused 5.233ms total 85.416ms
,E/Icing   ( 5601): Array storage bad crc 2024692317 vs 0
E/Icing   ( 5601): Trie mmap node failed
,I/Gmail   ( 5716): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5716): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  973): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5716): Error finding the version of the Email provider.....
E/Gmail   ( 5716): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5716): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5716): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5716): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5716): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5716): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5716): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 5716): We do not support migrating this version of the Email provider.
I/Gmail   ( 5716): getAccountsCursor
,I/ActivityManager(  973): Killing 5324:com.lge.appbox.client/u0a11 (adj 15): empty #11
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/JsMessageQueue( 5642): Set native->JS mode to OnlineEventsBridgeMode
,D/ChimeraCfgMgr( 5601): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5601): Module APK com.google.android.play.games already loaded
W/libprocessgroup(  973): failed to open /acct/uid_10011/pid_5324/cgroup.procs: No such file or directory
,W/ActivityManager(  973): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5716): Observing account changes for notifications
,W/ActivityManager(  973): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@14648459 on behalf of 5601
D/InitAlarmsService( 3804): Clearing and rescheduling alarms.
,I/art     ( 5496): Explicit concurrent mark sweep GC freed 7982(401KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.433ms total 68.283ms
,I/ActivityManager(  973): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5790 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  973): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5796 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/InstanceID/Rpc( 5601): Found 10006
W/InstanceID/Rpc( 5601): Found 10006
,D/jxcore_app_log( 5642): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426139648
I/chromium( 5642): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/Gmail   ( 5716): notifyAccountChanged
,I/Gmail   ( 5716): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/ResourcesManager( 5790): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Gmail   ( 5716): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CalendarProvider2( 5790): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3534ea0e
,I/Gmail   ( 5716): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/CalendarProvider2( 5790): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5790): Created com.android.providers.calendar.CalendarAlarmManager@29e84c4b(com.android.providers.calendar.CalendarProvider2@3534ea0e)
D/CalendarProvider2( 5790): Scheduling check of next Alarm
I/art     ( 5642): CheckpointMarkThreadRoots callback created = 0x9f66c4b0
,D/CalendarProvider2( 5790): SCHEDULE_ALARM_REMOVE
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
I/ActivityManager(  973): Killing 3804:com.android.calendar/u0a13 (adj 15): empty #11
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@4f5a81e on behalf of 5601
I/art     ( 5642): CheckpointMarkThreadRoots callback created = 0x9f66c480
,I/Gmail   ( 5716): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5716): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Icing   ( 5601): updateResources: need to parse f{com.google.android.gms}
,D/PhoneMonitor( 5796): Register our PhoneStateListener
W/libprocessgroup(  973): failed to open /acct/uid_10013/pid_3804/cgroup.procs: No such file or directory
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@1b05e8ff on behalf of 5601
,I/ActivityManager(  973): Killing 5350:com.android.gallery3d/u0a23 (adj 15): empty #11
,D/PhoneMonitor( 5796): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5796): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 5796): [parse] Load xml
,W/libprocessgroup(  973): failed to open /acct/uid_10023/pid_5350/cgroup.procs: No such file or directory
V/TelephonyAutoProfiling( 5796): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5796): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PhoneMonitor( 5796): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/art     ( 5601): Background sticky concurrent mark sweep GC freed 8354(592KB) AllocSpace objects, 6(96KB) LOS objects, 4% free, 13MB/14MB, paused 6.965ms total 66.251ms
,I/CheckinService( 5601): Checkin interval check for package: unspecified last checkin: 1454440650932 min interval config: 0 actual interval: 7950
,I/CheckinService( 5601): Disabling old GoogleServicesFramework version
,I/art     (  973): Explicit concurrent mark sweep GC freed 35000(1628KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 6.508ms total 221.504ms
I/ActivityManager(  973): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5838 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5838): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  973): Process com.android.contacts (pid 5376) has died
,I/Gmail   ( 5716): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinService( 5601): Checking schedule, now: 1454440659169 next: 1454440680885
I/CheckinService( 5601): active receiver: disabled
,I/Icing   ( 5601): Internal init done: storage state 0
,I/Icing   ( 5601): 22 corpora need re-polling
,I/NotificationManager( 5601): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Icing   ( 5601): Post-init done
I/ActivityManager(  973): Process com.lge.lockscreensettings (pid 5395) has died
,I/Icing   ( 5601): Indexing 1612944C7007A012B1C904336C8580EC6DBD4F91 from com.google.android.music
,I/ActivityManager(  973): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=5859 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  973): Process com.lge.eula (pid 5412) has died
,I/CalendarProvider2( 5790): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5790): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/Babel_SMS( 5838): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5838): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5838): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5838): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5838): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5838): MmsConfig.loadFromResources
E/Babel_SMS( 5838): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5838): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/ActivityManager(  973): Process com.lge.bnr (pid 5174) has died
,D/SensorManager( 5838): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5838): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5838): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5838): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5838): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5838): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5838): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5838): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5838): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5838): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5838): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5838): found sensor: LGE Orientation Sensor, handle=49
,D/SensorManager( 5838): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5838): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5838): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5838): found sensor: Motion Accel, handle=46
I/MusicStore( 5859): Database version: 120
,I/art     ( 5838): CheckpointMarkThreadRoots callback created = 0xb042d880
,W/Settings( 5838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5838): startup - clean
I/Babel   ( 5838): deleted: false for 0
,I/art     ( 5838): CheckpointMarkThreadRoots callback created = 0xb042d860
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5859): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/art     ( 5838): Suspending all threads took: 34.903ms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5859): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5859): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5859): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5859): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/AudioCapabilities( 5838): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5838): Unsupported mime audio/adpcm
W/AudioCapabilities( 5838): Unsupported mime audio/g726
W/AudioCapabilities( 5838): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5838): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5838): Unsupported mime video/mjpg
W/VideoCapabilities( 5838): Unsupported mime video/theora
V/JNIHelp ( 5859): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/AudioCapabilities( 5838): Unsupported mime audio/evrc
,W/AudioCapabilities( 5838): Unsupported mime audio/qcelp
W/VideoCapabilities( 5838): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5838): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5838): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5838): Unsupported mime audio/evrc
W/ActivityThread( 5859): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5859): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1ff479e2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5859): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5859): GMSCore installation verified
,I/ConfigStore( 5859): Config Database version: 1
,W/VideoCapabilities( 5838): Unsupported mime video/mp4v-esdp
W/jxcore-log( 5642): Initializing JXcore engine
,W/jxcore-log( 5642): JXcore engine is ready
,I/VideoCapabilities( 5838): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5838): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5838): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5838): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5838): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5838): onServiceConnected
W/Babel   ( 5838): Attempted to change video mute state without an active call.
,W/Thread-676( 5825): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8207]" dev="sockfs" ino=8207 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-676( 5825): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-676( 5825): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8297]" dev="sockfs" ino=8297 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-676( 5825): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-676( 5825): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-676( 5825): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26347]" dev="sockfs" ino=26347 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/MediaRouter( 5859): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
W/jxcore-log( 5642): Starting JXcore engine
,I/NotificationManager( 5838): com.google.android.talk: cancel(10436) by com.google.android.talk
I/NetworkMonitor( 5859): type=WIFI subType= reason=null isConnected=true
I/Icing   ( 5601): Indexing done 1612944C7007A012B1C904336C8580EC6DBD4F91
,I/Icing   ( 5601): Indexing 1F53EECCEBEB5877C2973BC154C132777EB605A6 from com.google.android.apps.books
W/ResourcesManager( 5838): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5838): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ActivityManager(  973): Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{3f4e19ac 5601:com.google.android.gms/u0a6} (pid=5601, uid=10006) that is not exported from uid 10046
I/NetworkMonitor( 5859): type=WIFI subType= reason=null isConnected=true
E/Icing   ( 5601): Cursor call threw an exception: Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{3f4e19ac 5601:com.google.android.gms/u0a6} (pid=5601, uid=10006) that is not exported from uid 10046
,I/Icing   ( 5601): Indexing done 1F53EECCEBEB5877C2973BC154C132777EB605A6
E/Icing   ( 5601): Aborting indexing of corpus volumes__id
I/Icing   ( 5601): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/GHttpClientFactory( 5859): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5859): Using platform SSLCertificateSocketFactory
I/NotificationManager( 5859): com.google.android.music: cancel(1061) by com.google.android.music
,W/jxcore-log( 5642): Platform android
W/jxcore-log( 5642): 
,W/jxcore-log( 5642): Process ARCH arm
W/jxcore-log( 5642): 
I/ActivityManager(  973): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5903 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5145): getMode name:com.lge.qremote
,V/JNIHelp ( 5838): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AudioManager( 5145): getMode name:com.lge.qremote
,I/AudioManager( 5145): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5903): Quickset Services start...
,I/UEI.SmartControl( 5903): Manufacture = LGE
D/UEI.SmartControl( 5903): File observer start...
E/UEI.SmartControl( 5903): IR Port is disabled: false
D/UEI.SmartControl( 5903): Starting file observer...
D/UEI.SmartControl( 5903): Extracting JNI libs...
I/AudioManager( 5145): getMode name:com.lge.qremote
D/UEI.SmartControl( 5903): --- this system supports 32-bit or 64-bit only
I/AudioManager( 5145): getMode name:com.lge.qremote
,W/System  ( 5838): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5838): Installed default security provider GmsCore_OpenSSL
E/MDM     ( 1732): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5601): Restart initialization of location
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AudioManager( 5145): getMode name:com.lge.qremote
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,I/NotificationManager( 5838): com.google.android.talk: cancel(8) by com.google.android.talk
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
V/AlarmManager(  973): RTC_WAKEUP set : Alarm{22668424 type 0 when 1454440661003 com.google.android.googlequicksearchbox} when 1454440661003
W/art     ( 1932): Suspending all threads took: 60.375ms
I/InputReader(  973): Reconfiguring input devices.  changes=0x00000010
,D/administrator(  973): Handling package changes for user 0
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/UEI.SmartControl( 5903): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5903): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5903): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationService(  973): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  973): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  973): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/UEI.SmartControl( 5903): --- Selecting new region: 2
I/UEI.SmartControl( 5903): -- Running on KitKat(19) and above! JNI will be used.
I/jxcore-log( 5642): JXcore Cordova bridge is ready!
I/jxcore-log( 5642): 
,W/jxcore-log( 5642): JXcore engine is started
I/ActivityManager(  973): Process com.google.android.apps.docs (pid 5429) has died
D/UEI.SmartControl( 5903): Platform has CIR...
D/UEI.SmartControl( 5903): NO CIR support, need to check package...
,I/UEI.SmartControl( 5903): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5903): QS Service created
I/ActivityManager(  973): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5935 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ResourcesManager(  973): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/BackupManagerService(  973): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  973): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  973): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3382bd13
,E/UEI.SmartControl( 5903): QS start get config
,D/UEI.SmartControl( 5903): Loading JNI Libs...
,D/UEI.SmartControl( 5903):  configuring local db...
,I/jxcore-log( 5642): Toggling radios to true
I/jxcore-log( 5642): 
,D/BluetoothAdapter( 5642): enable(): BT is already enabled..!
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,D/WifiServiceImplEx(  973): setWifiEnabled: true pid=5642, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,I/AppUp4:AppBoxCP( 5935): onCreate
D/WifiService(  973): setWifiEnabled: true pid=5642, uid=10316
W/AppUp4:DB( 5935):  [AppBoxDatabaseHelper] construct
D/WifiServiceImplEx(  973): disconnect pid=5642, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  973): reconnect pid=5642, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5642): Radios toggled
I/jxcore-log( 5642): 
I/jxcore-log( 5642): My device name is: LGE-LG-D722
I/jxcore-log( 5642): 
I/AppUp4:DB( 5935):  setFingerPrint start
I/AppUp4:DB( 5935):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,W/ResourceType(  973): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/wpa_supplicant( 2791): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/wpa_supplicant( 2791): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,E/WifiStateMachine(  973): WifiStateMachine: Leaving Connected state
I/AppUp4:DB( 5935):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
D/WfdsMonitor( 1794): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
I/AppUp4:DB( 5935):  SDK version = 0
I/AppUp4:DB( 5935):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5935): AppBoxApplication onCreate()
E/WifiConfigStore(  973): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/AppUp4:CustModeStarterReceiver( 5935): onReceive
,I/AppUp4:CustModeStarterReceiver( 5935): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5935): Context : android.app.ReceiverRestrictedContext@2a25ebc5
D/AppUp4:CustFacade( 5935): isCustomizationCompleted : false
D/LGWifiP2pService(  973): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/AppUp4:CustFacade( 5935): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5935): begin check event
I/AppUp4:CustModeStarterReceiver( 5935): Event For Nothing, skip.
D/DhcpStateMachine(  973): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  278): Clearing all IP addresses on wlan0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1732): Read error: ssl=0xb0463c00: I/O error during system call, Connection timed out
,V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xb0463c00: I/O error during system call, Broken pipe
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  973): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  973): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  973): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/ActivityManager(  973): Process com.google.android.apps.plus (pid 5460) has died
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): ValidatedState{ when=-16ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): DefaultState{ when=-24ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): Forcing reevaluation
,D/WifiServiceExtension( 1794): isInternetCheckAvailable return false
I/ActivityManager(  973): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5956 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/WifiHS20(  973): hidePasspointNotification off =false
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:41.976 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/DhcpStateMachine(  973): StoppedState
D/ConnectivityService(  973): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  973): disableDataServiceNotify
,D/DSQN    (  973): stop dsqn bin
D/ConnectivityService(  973): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  973):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  973):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  973): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  973): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): Disconnected - quitting
D/CSLegacyTypeTracker(  973): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  973): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  973): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,I/ActivityManager(  973): Process com.android.vending (pid 5523) has died
,E/WifiStateMachine(  973): Start Disconnecting Watchdog 1
I/wpa_supplicant( 2791): wlan0: CTRL-EVENT-SCAN-STARTED 
D/DhcpStateMachine(  973): StoppedState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/LGWifiP2pService(  973): InactiveState{ when=-12ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): P2pEnabledState{ when=-12ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/UEI.SmartControl( 5903):  ---- Has DB8: true
,D/UEI.SmartControl( 5903): QS start statue = true Error code = 0
D/UEI.SmartControl( 5903): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5903): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/WifiHS20(  973): hidePasspointNotification off =false
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:42.098 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  973): hidePasspointNotification off =false
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  973): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  973): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:42.102 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/Tethering(  973): MasterInitialState.processMessage what=3
I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
V/NetworkPolicy(  973): [LG_RESTRICTED] !!!isConnected  type  :1
D/WifiServiceExtension( 1794): isInternetCheckAvailable return false
W/QCNEJ   ( 1839): |CORE| No family connected
D/ConnectivityService(  973): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  973): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Tethering(  973): MasterInitialState.processMessage what=3
D/ConnectivityService(  973): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  973): [LG_RESTRICTED] !!!isConnected  type  :1
W/ResourcesManager( 5956): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5956): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5956): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/UEI.SmartControl( 5903): IRRCDataComm has AudioManager!!!!.
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  973): Removing idletimer
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyNetworkFactory-1( 1751): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/Settings(  973): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  973): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WifiNetworkAgent(  973): NetworkAgent: NetworkAgent channel lost
W/irrc_jni( 5903): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5903): IrrcClient ++ 
D/irrcClient( 5903): getIrrcService ++ 
,D/irrcClient( 5903): getIrrcService -- 
D/irrcClient( 5903): IrrcClient -- 
W/irrc_jni( 5903): IRRCPlayer_nativeInit -- 
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:42.153 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiHS20(  973): hidePasspointNotification off =false
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/Icing   ( 5601): Loaded CLD2 Version V2.0 - 20141016
D/UEI.SmartControl( 5903): Services init done
I/UEI.SmartControl( 5903): Device manager: loading config....
,D/UEI.SmartControl( 5903): Config is loaded...
D/WIFI    (  973): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  973):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:42.189 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
,D/WifiServerServiceExt(  973): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  973): setSupplicantStateDISCONNECTED
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiServerServiceExt(  973): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  973): setSupplicantStateSCANNING
D/LocationProviderProxy(  973): applying state to connected service
,D/UEI.SmartControl( 5903):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5903): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5903): QS Service init finished
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
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
D/UEI.SmartControl( 5903): QS Service version name: 0.1.73
D/UEI.SmartControl( 5903): QS Service version code: 1073
D/UEI.SmartControl( 5903): Service requested: Control
,D/UEI.SmartControl( 5903): Internal service binding...
D/UEI.SmartControl( 5903): -----IControl: 11
D/UEI.SmartControl( 5903): Caller: com.lge.qremote
,D/UEI.SmartControl( 5903): ------------ IControl registerCallback...
I/UEI.SmartControl( 5903): Registering callback...
D/UEI.SmartControl( 5903): -----IControl: 19
D/UEI.SmartControl( 5903): Caller: com.lge.qremote
I/UEI.SmartControl( 5903): Registering Services Ready callback...
I/UEI.SmartControl( 5903): Notify client services are ready...
D/UEI.SmartControl( 5903): -----IControl: 8
D/UEI.SmartControl( 5903): Caller: com.lge.qremote
I/AppConfig( 5956): Total System Memory = 906309632
,I/GalleryUtils( 5956): Application Heap = 96 MB
I/AppConfig( 5956): App Tier : NOT_DEF
D/SystemHelper( 5956): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  973): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5982 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 5982): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5982): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5982): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5982): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5982): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/art     (  973): Explicit concurrent mark sweep GC freed 39356(1936KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/36MB, paused 2.431ms total 168.099ms
,I/ActivityManager(  973): Process com.google.android.gm (pid 5716) has died
,I/SystemConfig( 5982): BUILD Country: EU
,I/SystemConfig( 5982): BUILD Operator: OPEN
I/ActivityManager(  973): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6001 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 5982): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 5982): existFile = false
I/SystemConfig( 5982): canReadFile = false
I/SystemConfig( 5982): systemFeature RCS result false
D/SystemConfig( 5982): refreshRcsSupport() :false
,I/LockScreenSettings( 6001): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6001): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6001): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6001): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6001): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6001): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  973): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6018 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2791): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:43.227 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/LocSvc_java(  973): onReceive
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:43.235 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/wpa_supplicant( 2791): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/WifiServerServiceExt(  973): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  973): setSupplicantStateASSOCIATING
,D/WifiServerServiceExt(  973): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  973): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:43.269 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:43.27 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/wpa_supplicant( 2791): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2791): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
,I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/WifiServiceExtension(  973): setVHTCapabilityType  : false
W/ResourcesManager( 6018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WifiServerServiceExt(  973): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  973): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  973): setSecurityType  : 2
,W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:43.337 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:43.339 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
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
D/ConnectivityService(  973): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: ,false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  973): Got NetworkAgent Messenger
D/ConnectivityService(  973): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  973): NetworkAgent connected
D/WifiServiceExtension( 1794): isInternetCheckAvailable return false
E/WifiConfigStore(  973): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  973): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Setting iface cfg
E/WifiStateMachine(  973): Start Dhcp Watchdog 2
D/DhcpStateMachine(  973): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  973): WaitBeforeStartState
I/ActivityManager(  973): Process com.google.android.music:main (pid 5859) has died
,D/WifiServerServiceExt(  973): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  973): setSupplicantStateGROUP_HANDSHAKE
D/ConnectivityService(  973): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{2774ce3 type 2 when 90842 com.android.providers.calendar} when 90842
,E/WifiStateMachine(  973): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  973): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  973): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a7567e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@2a7567e target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  973): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  973): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  973): DHCP Start wake lock is acquired.
D/CommandListener(  278): Setting iface cfg
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  278): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper(  973): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  973): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  973): setSupplicantStateCOMPLETED
D/ConnectivityService(  973): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/WifiServerServiceExt(  973): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  973): setSupplicantStateCOMPLETED
D/LGWifiP2pService(  973): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  973): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  973): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  973): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  973): ignoring duplicate network state non-change
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  973): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  973): Adding iface wlan0 to network 101
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:43.62 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:43.623 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1794): isInternetCheckAvailable return false
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiServiceExtension( 1794): isInternetCheckAvailable return false
E/WifiStateMachine(  973): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:43.632 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiHS20(  973): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  973): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:43.642 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
E/ConnectivityService(  973): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  973): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/ConnectivityService(  973): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  278): netlink response contains error (File exists)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  973): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  973): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  973): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  973): Setting Dns servers for network 101 to [/192.168.1.1]
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  973): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  973): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  973): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  973): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  973):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  973):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  973):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  973):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  973):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  973): currentScore = 0, newScore = 20
D/ConnectivityService(  973):    accepting network in place of null
D/ConnectivityService(  973): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  973): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  973): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/WIFI    (  973):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/CSLegacyTypeTracker(  973): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  973): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  973): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  973): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  973): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failo,ver: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/TelephonyNetworkFactory-1( 1751): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  973): validation of new default Network = false
D/ConnectivityService(  973): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  973): enableDataServiceNotify 
D/DSQN    (  973): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): [LWD] wait 500ms before dns check
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/ConnectivityService(  973): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  973):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  973):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  973): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
I/DSQN    ( 6050): DSQN samuel.seo ver 141203
E/DSQN    ( 6050): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6050): created command queue thread
I/DSQN    ( 6050): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6050): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/Tethering(  973): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
,I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
V/NetworkPolicy(  973): [LG_RESTRICTED] checkMobilePolicy_type()
I/CheckinService( 5601): Checkin interval check for package: unspecified last checkin: 1454440650932 min interval config: 0 actual interval: 12810
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/CheckinService( 5601): Checking schedule, now: 1454440663768 next: 1454440680885
I/CheckinService( 5601): active receiver: disabled
,D/DhcpStateMachine(  973): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  973): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  973): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6057): version 5.5.6 starting
,E/dhcpcd  ( 6057): get_duid: Read-only file system
I/UpdateIcingCorporaServi( 1932): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  973): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6066 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dhcpcd  ( 6057): wlan0: rebinding lease of 192.168.1.134
,I/art     (  306): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 284us total 23.397ms
I/art     (  306): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 312us total 20.785ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 21.889ms
,I/UpdateIcingCorporaServi( 1932): UpdateCorporaTask done [took 127 ms] updated apps [took 127 ms] 
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): [LWD] DNSResolver start dns
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  973): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): [LWD] DNSResolver end dns
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6050): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 6050): restart monitoring
I/DSQN    ( 6050): dsqn report finish
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  973): DSQM DsqnNotification wlan0  1
D/DSQN    (  973): start to monitor internet connection
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 19:17:44 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454440664290], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454440664269]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1794): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  973): Validated
D/ConnectivityService(  973): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  973): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  973):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  973):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  973):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  973): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  973): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  973):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  973):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  973): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  973): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  973): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
D/WIFI    (  973): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  973):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1751): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/ActivityManager(  973): Process com.android.providers.calendar (pid 5790) has died
,D/WifiDataContinuityService(  973): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  973): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/Finsky  ( 6066): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Icing   ( 5601): Indexing B2F716F68058802BDD4E913C0921699984AB1871 from com.google.android.videos
I/ActivityManager(  973): Start proc com.google.android.videos for content provider com.google.android.videos/.search.IcingContentProvider: pid=6096 uid=10099 gids={50099, 9997, 3003, 1028, 1015, 3002} abi=armeabi
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  973): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  973): identical MTU - not setting
D/Nat464Xlat(  973): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  973): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  973):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  973):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  973): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  973): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  973): enableDataServiceNotify 
D/DSQN    (  973): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524295
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:44.683 DNS addrs= 192.168.1.1, 0.0.0.0, 
,D/DSQN    (  973): dsqn is running restart
D/ConnectivityService(  973): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/ResourcesManager( 6096): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
I/DSQN    ( 6121): DSQN samuel.seo ver 141203
E/DSQN    ( 6121): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6121): created command queue thread
I/DSQN    ( 6121): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6121): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/Finsky  ( 6066): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6066): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6066): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6066): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 6066): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6066): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@2bc16cc on behalf of 6066
D/Ads     ( 6066): Skipping gmscore version check
I/AudioManager( 5145): getMode name:com.lge.qremote
,D/PackageBroadcastService( 5601): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Finsky  ( 6066): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/AudioManager( 5145): getMode name:com.lge.qremote
,I/PackageBroadcastService( 5601): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 6066): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/SetupWizard( 5796): Connected to Gservices successfully
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
,D/LocationInitializer( 5601): Restart initialization of location
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1732): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dhcpcd  ( 6057): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 1732): propertyValue:false
I/dhcpcd  ( 6057): wlan0: leased 192.168.1.134 for 86400 seconds
,I/DSQN    ( 6121): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6121): restart monitoring
I/ActivityManager(  973): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6161 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DSQN    ( 6121): dsqn report finish
D/LGDataListener(  278): argv[0]=dsqncommand
D/LGDataListener(  278): argv[1]=wlan0
D/LGDataListener(  278): argv[2]=1
D/LGDataListener(  278): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  973): DSQM DsqnNotification wlan0  1
D/DSQN    (  973): start to monitor internet connection
D/ConnectivityService(  973): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  973): Process com.android.gallery3d (pid 5956) has died
D/ConnectivityService(  973): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  973): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  973): onReceive
D/LocSvc_java(  973): got connectivity action
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  973): broadcast - no network connections
D/LocSvc_java(  973): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  973): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  973): onReceive
D/LocSvc_java(  973): got connectivity action
D/LocSvc_java(  973): broadcast - no network connections
D/LocSvc_java(  973): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  973): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  973): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  973): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  973): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  973): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  973): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  973): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  973): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  973): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  973): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  973): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  973): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  973): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  973): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  973): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  973): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  973): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  973): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  973): RunningState
W/PlayMovies( 6096): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 6096): 
,W/ActivityManager(  973): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/PlayMovies( 6096): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 6096): 
I/Icing   ( 5601): Indexing done B2F716F68058802BDD4E913C0921699984AB1871
I/Icing   ( 5601): Indexing FC5805F301A6400196925772B79FE617968B1409 from com.google.android.videos
D/PlayMovies( 6096): PersistentCache.cleanup:94 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/PlayMovies( 6096): 
,W/AudioCapabilities( 6096): Unsupported mime audio/x-lg-flac
,D/Finsky  ( 6066): [715] SignatureUtils.faultInOtherSignatures: Will not allow first-party apps signed by test keys
D/Finsky  ( 6066): [715] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.videos
W/AudioCapabilities( 6096): Unsupported mime audio/adpcm
W/AudioCapabilities( 6096): Unsupported mime audio/g726
I/Icing   ( 5601): Indexing done FC5805F301A6400196925772B79FE617968B1409
,W/AudioCapabilities( 6096): Unsupported mime audio/x-ms-wma
D/PlayMovies( 6096): TransferService.onCreate:60 creating transfer service
D/PlayMovies( 6096): 
W/AudioCapabilities( 6096): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6096): Unsupported mime video/mjpg
W/VideoCapabilities( 6096): Unsupported mime video/theora
I/Icing   ( 5601): Indexing 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9 from com.google.android.gms
,I/Gmail   ( 6161): getAccountsCursor
,W/AudioCapabilities( 6096): Unsupported mime audio/evrc
W/AudioCapabilities( 6096): Unsupported mime audio/qcelp
W/VideoCapabilities( 6096): Unrecognized profile 2130706433 for video/avc
I/Icing   ( 5601): Indexing done 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9
I/Icing   ( 5601): Indexing 261F31C44790DA98645222D6E4244392E5409193 from com.google.android.gms
,W/AudioCapabilities( 6096): Unsupported mime audio/amr-wb-plus
W/GAV2    ( 6161): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/Icing   ( 5601): Indexing done 261F31C44790DA98645222D6E4244392E5409193
W/AudioCapabilities( 6096): Unsupported mime audio/qcelp
I/Icing   ( 5601): Indexing AC7CA1348821615DDDE9D587591668A8B8E68A6F from com.google.android.googlequicksearchbox
I/art     ( 5496): Explicit concurrent mark sweep GC freed 3068(121KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 486us total 44.425ms
W/AudioCapabilities( 6096): Unsupported mime audio/evrc
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/VideoCapabilities( 6096): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6096): Unsupported profile 4 for video/mp4v-es
,W/ActivityManager(  973): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/WVCdm   (  284): Instantiating CDM.
I/WVCdm   (  284): CdmEngine::QueryStatus
I/WVCdm   (  284): Level3 Library Dec 11 2014 16:13:16
E/Gmail   ( 6161): Error finding the version of the Email provider.....
E/Gmail   ( 6161): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6161): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6161): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6161): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6161): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6161): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6161): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6161): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6161): We do not support migrating this version of the Email provider.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6096): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
W/WVCdm   (  284): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  284): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  284): L1 library not specified. Falling Back to L3
,I/WVCdm   (  284): L3 Terminate.
I/Gmail   ( 6161): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  973): Killing 5935:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Icing   ( 5601): Indexing done AC7CA1348821615DDDE9D587591668A8B8E68A6F
,I/Icing   ( 5601): Indexing 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652 from com.google.android.googlequicksearchbox
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/art     (  973): Explicit concurrent mark sweep GC freed 61604(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/37MB, paused 2.196ms total 181.368ms
,W/libprocessgroup(  973): failed to open /acct/uid_10011/pid_5935/cgroup.procs: No such file or directory
,W/ActivityManager(  973): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/ActivityManager(  973): Killing 5838:com.google.android.talk/u0a61 (adj 15): empty #11
I/Gmail   ( 6161): Observing account changes for notifications
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  973): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup(  973): failed to open /acct/uid_10061/pid_5838/cgroup.procs: No such file or directory
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Icing   ( 5601): Indexing done 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652
I/Icing   ( 5601): Indexing 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D from com.google.android.gm
I/ActivityManager(  973): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6243 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 40327(2MB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 13MB/22MB, paused 1.689ms total 113.815ms
,I/Gmail   ( 6161): notifyAccountChanged
,I/Gmail   ( 6161): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/NotificationManager( 1932): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
I/Gmail   ( 6161): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6161): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 5601): Indexing done 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D
,I/Icing   ( 5601): Indexing 59716A40DEE00805E4208F1709FD830CA906A723 from com.google.android.music
I/Gmail   ( 6161): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6161): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ResourcesManager( 6243): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  973): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=6264 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 20:17:46.507 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/CalendarApplication( 6243): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6243): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6243): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3438823c, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2a25ebc5, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1f59991a, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@29e84c4b, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2c298628, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1f7e7f41, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@20e82ce6, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@206d6227, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@33a4dcd4, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1872ce7d, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@157a3172, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1043f9c3, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@12dcf240, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3762d579, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@6b5f2be, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@8626f1f, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@20bef26c, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@ab25035, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@205a7cca, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@26c8de3b, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@13dec958, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2944bab1, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@190b9b96, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1f5d2317, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@36232304, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1ab950ed, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@1bdddb22, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@1486d9b3, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@27316b70, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@7670ee9, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3ea2876e, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1d8b5e0f, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1999ce9c, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2c18b0a5, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@10f3ac7a, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@16a9cc2b, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@36c33888, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@d88b221, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@10001646, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@16f70007, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@15975534, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@279
D/GeneralP,referenceUtils( 6243): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6243): [init]
I/Config  ( 6243): LGCalendar ver.4.40.17
I/Config  ( 6243): start check model
I/Config  ( 6243): start check native_ca
I/Config  ( 6243): Config Operator=OPEN, Country=EU
D/Config  ( 6243): [setDefaultValuesToPref]
D/Config  ( 6243): [parseProfiles]
,D/ProfilesParser( 6243): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6243): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6243): [updateProfiletoCountryInfo]
,D/GeneralPreference( 6243): [checkAndMigrateOldPreference]
D/AlertReceiver( 6243): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,V/WifiInternetCheck(  973): Single check msg out of sync, ignoring.
I/InitNotificationRingtoneService( 6243): Start InitializeAlertRingtoneService.onHandleIntent
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/AlertUtils( 6243): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,D/ConnectivityService(  973): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  973): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  973): onReceive
D/LocSvc_java(  973): got connectivity action
D/LocSvc_java(  973): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  973): Sending msg: 4 arg1:1 arg2:1
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  973): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  973): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  973): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  973): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/MusicStore( 6264): Database version: 120
I/AlertUtils( 6243): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/Gmail   ( 6161): getAccountsCursor
I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6243): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6243): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
V/AlarmManager(  973): RTC_WAKEUP set : Alarm{d8c0cc9 type 0 when 1454440666793 com.android.vending} when 1454440666793
D/Finsky  ( 6066): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/AlertUtils( 6243): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 6243): End InitializeAlertRingtoneService.onHandleIntent
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6264): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  973): android: cancelAsUser(2) by android
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6264): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,D/libc-netbsd( 6066): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
D/libc-netbsd( 6066): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6066): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6066): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
W/ContextImpl( 6264): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6066): propertyValue:false
D/libc-netbsd( 6066): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6066): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 6264): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6264): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/HolidayIntentService( 6243): onHandleIntent
,D/HolidayDataLoader( 6243): readJsonAsset : holiday.json
V/JNIHelp ( 6264): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/AlertService( 6243): 0 Action = android.intent.action.PROVIDER_CHANGED
I/Icing   ( 5601): Indexing done 59716A40DEE00805E4208F1709FD830CA906A723
,I/Icing   ( 5601): Not indexing corpus from package com.android.chrome as it has never connected
E/Icing   ( 5601): Aborting indexing of corpus omnibox
D/libc-netbsd( 6066): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6066): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Icing   ( 5601): Indexing 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3 from com.google.android.gms
E/HolidayIntentService( 6243): onHandleIntent:holiday data empty
,I/Icing   ( 5601): Indexing done 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3
I/Icing   ( 5601): Indexing F200CD067697391E5BA8387C554D1EADCF480F28 from com.google.android.gms
D/UEI.SmartControl( 5903): Internal timer expired: 1
,I/ActivityManager(  973): Process com.android.contacts (pid 5982) has died
E/AgendaWidgetManager( 6243): [updateWidgets] 
W/ActivityThread( 6264): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6264): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1ff479e2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6264): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6264): GMSCore installation verified
D/MonthWidgetProvider( 6243): [onReceive]
D/CalendarWidgetProvider( 6243): [onReceive]
D/CalendarWidgetProvider( 6243): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6243): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6243): [onReceive]
D/CalendarWidgetProvider( 6243): [onReceive]
D/CalendarWidgetProvider( 6243): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6243): [onCreate] mContext.getPackageName() = com.android.calendar
I/Icing   ( 5601): Indexing done F200CD067697391E5BA8387C554D1EADCF480F28
,I/Icing   ( 5601): Indexing 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5 from com.google.android.music
I/ActivityManager(  973): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6299 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  973): Process com.google.android.apps.plus (pid 6018) has died
I/ConfigStore( 6264): Config Database version: 1
,I/Icing   ( 5601): Indexing done 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5
I/Icing   ( 5601): Indexing 98E736199A4D0A3DAA0BBDB44355DD80A1943A96 from com.google.android.googlequicksearchbox
,I/Icing   ( 5601): Indexing done 98E736199A4D0A3DAA0BBDB44355DD80A1943A96
,I/Icing   ( 5601): Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
W/ResourcesManager( 6299): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Icing   ( 5601): Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
I/Icing   ( 5601): Indexing 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4 from com.google.android.googlequicksearchbox
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  973): android: cancelAsUser(2) by android
,I/MediaRouter( 6264): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/Icing   ( 5601): Indexing done 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4
I/qtaguid ( 6066): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6066): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6066): untagSocket(41) failed with errno -22
I/NetworkMonitor( 6264): type=WIFI subType= reason=null isConnected=true
I/Icing   ( 5601): Indexing BC9EFFA8FB4EBD74F2B7898FFA6492656D342420 from com.google.android.music
D/Finsky  ( 6066): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/art     ( 6264): CheckpointMarkThreadRoots callback created = 0xb0516a20
,I/Icing   ( 5601): Indexing done BC9EFFA8FB4EBD74F2B7898FFA6492656D342420
,I/Icing   ( 5601): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
I/NetworkMonitor( 6264): type=WIFI subType= reason=null isConnected=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     ( 6264): CheckpointMarkThreadRoots callback created = 0xb05169f0
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 95000808977; DSPS: 3211369; Offset : -3012508177
,I/ActivityManager(  973): Process com.lge.lockscreensettings (pid 6001) has died
I/ActivityManager(  973): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6325 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GHttpClientFactory( 6264): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6264): Using platform SSLCertificateSocketFactory
,I/NotificationManager(  973): android: cancelAsUser(2) by android
,D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
,W/ResourcesManager( 6325): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6325): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 5601): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
I/Icing   ( 5601): Indexing B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839 from com.google.android.gms
I/Icing   ( 5601): Indexing done B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839
I/Icing   ( 5601): Indexing 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15 from com.google.android.googlequicksearchbox
,I/MultiDex( 6325): VM with version 2.1.0 has multidex support
,I/MultiDex( 6325): install
I/MultiDex( 6325): VM has multidex support, MultiDex support library is disabled.
I/art     (  973): Explicit concurrent mark sweep GC freed 28318(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.692ms total 171.869ms
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  973): propertyValue:false
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  973): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  973): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  278): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out(  973): propertyValue:false
,I/ActivityManager(  973): Process com.lge.qremote (pid 5145) has died
,D/UEI.SmartControl( 5903): Service.onUnbind: IControl
D/UEI.SmartControl( 5903): Service.onDestroy
D/UEI.SmartControl( 5903): Shutdown IRRCPlayer... 
I/BackgroundMemoryTrimmer( 1932): Trimming objects from memory, since app is in the background.
,V/WifiInternetCheck(  973): isHttpConnectionAvailable - We got a valid response : 204
I/PhoneApp( 1751): onTrimMemory: 10
I/PhoneApp( 1751): trim memory
,I/NotificationManager( 6264): com.google.android.music: cancel(1061) by com.google.android.music
W/irrc_jni( 5903): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5903): ~IrrcClient ++ 
D/irrcClient( 5903): ~IrrcClient -- 
W/irrc_jni( 5903): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5903): Blaster closed
D/UEI.SmartControl( 5903): Blaster closed
D/UEI.SmartControl( 5903): Shut down QS...
D/UEI.SmartControl( 5903): Stopped file observer...
I/UEI.SmartControl( 5903): QS lib stop result = true
,D/UEI.SmartControl( 5903): QS shutdown complete
V/JNIHelp ( 6325): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/BackgroundMemoryTrimmer( 1932): Trimming objects from memory, since app is in the background.
I/Icing   ( 5601): Indexing done 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15
,I/art     ( 6299): CheckpointMarkThreadRoots callback created = 0xb042d4d0
,I/qtaguid ( 6066): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6066): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6066): untagSocket(41) failed with errno -22
,I/Babel_SMS( 6299): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6299): MmsConfig.loadMmsSettings
I/Babel_SMS( 6299): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6299): MmsConfig.loadFromDatabase
W/ActivityThread( 6325): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6325): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26d00d15: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6325): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6325): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6325): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 6299): CheckpointMarkThreadRoots callback created = 0xb042d4b0
,I/Icing   ( 5601): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/Icing   ( 5601): updateResources: need to parse f{com.google.android.gms}
,D/ChimeraCfgMgr( 6325): Reading stored module config
E/Babel_SMS( 6299): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6299): MmsConfig.loadFromResources
E/Babel_SMS( 6299): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6299): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/ChimeraCfgMgr( 6325): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/SensorManager( 6299): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6299): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6299): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6299): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6299): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6299): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6299): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6299): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6299): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6299): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6299): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6299): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6299): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6299): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6299): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6299): found sensor: Motion Accel, handle=46
,W/Settings( 6299): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6299): startup - clean
I/Babel   ( 6299): deleted: false for 0
,D/CAR.SERVICE( 6325): Connecting to CarCallService...
,I/art     ( 6325): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6325): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/AudioCapabilities( 6299): Unsupported mime audio/x-lg-flac
,D/NativeLibraryUtils( 6325): Install completed successfully. count=14 extracted=0
W/AudioCapabilities( 6299): Unsupported mime audio/adpcm
,I/ActivityManager(  973): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6367 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/CAR.SERVICE( 6325): com.google.android.projection.gearhead isn't installed.
W/AudioCapabilities( 6299): Unsupported mime audio/g726
,I/BackgroundMemoryTrimmer( 1932): Trimming objects from memory, since app is in the background.
W/AudioCapabilities( 6299): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6299): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6299): Unsupported mime video/mjpg
W/VideoCapabilities( 6299): Unsupported mime video/theora
,D/CAR.TEL.Service( 6325): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6325): Creating a new PhoneAdapter instance
W/ActivityManager(  973): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6325): setListener: com.google.android.gms.car.dn@3d659ae8
,W/ActivityManager(  973): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6325): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6325): Starting CarCallService with initial phone null
I/NotificationManager( 6325): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/AppUp4:AppBoxCP( 6367): onCreate
,W/AudioCapabilities( 6299): Unsupported mime audio/evrc
W/AppUp4:DB( 6367):  [AppBoxDatabaseHelper] construct
W/AudioCapabilities( 6299): Unsupported mime audio/qcelp
W/VideoCapabilities( 6299): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:DB( 6367):  setFingerPrint start
I/AppUp4:DB( 6367):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6367):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6367):  SDK version = 0
I/AppUp4:DB( 6367):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6367): AppBoxApplication onCreate()
W/AudioCapabilities( 6299): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6299): Unsupported mime audio/qcelp
I/AppUp4:CustModeStarterReceiver( 6367): onReceive
I/AppUp4:CustModeStarterReceiver( 6367): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,W/AudioCapabilities( 6299): Unsupported mime audio/evrc
D/AppUp4:CustFacade( 6367): Context : android.app.ReceiverRestrictedContext@2a25ebc5
D/AppUp4:CustFacade( 6367): isCustomizationCompleted : false
W/VideoCapabilities( 6299): Unsupported mime video/mp4v-esdp
D/CAR.SERVICE( 6325): Package validated; name: com.android.vending
,I/art     ( 6066): CheckpointMarkThreadRoots callback created = 0xaaeeb8a0
D/AppUp4:CustFacade( 6367): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6367): begin check event
I/AppUp4:CustModeStarterReceiver( 6367): Event For Nothing, skip.
I/art     ( 6066): CheckpointMarkThreadRoots callback created = 0xb05619a0
,I/ActivityManager(  973): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6390 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/VideoCapabilities( 6299): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6299): Unrecognized profile 2130706433 for video/avc
,I/NotificationManager( 6066): com.android.vending: cancel(10436) by com.android.vending
W/VideoCapabilities( 6299): Unrecognized profile 2130706433 for video/avc
V/Finsky  ( 6066): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/VideoCapabilities( 6299): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6299): Unrecognized profile 2130706433 for video/avc
,W/ResourcesManager( 6390): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6390): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6390): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/vclib   ( 6299): onServiceConnected
,W/Babel   ( 6299): Attempted to change video mute state without an active call.
I/NotificationManager( 6299): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6299): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6299): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Icing   ( 5601): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/AppConfig( 6390): Total System Memory = 906309632
I/GalleryUtils( 6390): Application Heap = 96 MB
,I/AppConfig( 6390): App Tier : NOT_DEF
,D/SystemHelper( 6390): region [EU], country [EU], operator [OPEN], sub-operator []
I/Icing   ( 5601): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,V/JNIHelp ( 6299): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 6299): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6299): Installed default security provider GmsCore_OpenSSL
,I/Icing   ( 5601): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 5601): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  973): Process com.uei.lg.quicksetsdk.lite (pid 5903) has died
,I/ActivityManager(  973): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6413 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/NotificationManager( 6299): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 6413): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6413): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6413): BUILD Country: EU
I/SystemConfig( 6413): BUILD Operator: OPEN
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  973): android: cancelAsUser(2) by android
I/ActivityManager(  973): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6441 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6413): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6413): existFile = false
I/SystemConfig( 6413): canReadFile = false
I/SystemConfig( 6413): systemFeature RCS result false
D/SystemConfig( 6413): refreshRcsSupport() :false
I/qtaguid ( 6066): Failed write_ctrl(u 41) res=-1 errno=22
,I/qtaguid ( 6066): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6066): untagSocket(41) failed with errno -22
,I/LockScreenSettings( 6441): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6441): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 6441): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6441): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6441): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6441): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  973): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6459 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 741us total 29.087ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 23.652ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 21.161ms
,W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6066): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6066): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6066): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/GAV2    ( 6161): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 5601): Google Analytics 8.4.89 is starting up.
I/art     ( 6066): WaitForGcToComplete blocked for 5.612ms for cause DisableMovingGc
,D/Finsky  ( 6066): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  973): RTC_WAKEUP set : Alarm{37de2b02 type 0 when 1454440670885 com.android.vending} when 1454440670885
,D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
D/Finsky  ( 6066): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6066): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  973): Killing 5796:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  973): Killing 6096:com.google.android.videos/u0a99 (adj 15): empty #12
,W/libprocessgroup(  973): failed to open /acct/uid_10038/pid_5796/cgroup.procs: No such file or directory
,W/libprocessgroup(  973): failed to open /acct/uid_10099/pid_6096/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 1932): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 5601): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5642): 
,I/ActivityManager(  973): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6497 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PackageBroadcastService( 5601): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 5601): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 1932): UpdateCorporaTask done [took 133 ms] updated apps [took 133 ms] 
,W/ResourcesManager( 6497): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6497): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6497): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6497): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6497): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/IndexDatabaseHelper( 6497): Using schema version: 115
,I/IndexDatabaseHelper( 6497): Index is fine
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
I/ActivityManager(  973): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6534 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  973): Killing 6264:com.google.android.music:main/u0a81 (adj 15): empty #11
,V/AlarmManager(  973): RTC_WAKEUP set : Alarm{27ef0abd type 0 when 1454440671972 com.google.android.googlequicksearchbox} when 1454440671972
W/libprocessgroup(  973): failed to open /acct/uid_10081/pid_6264/cgroup.procs: No such file or directory
,I/PCSuite ( 6534): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/AlertService( 6243): Beginning updateAlertNotification
D/PCSuite ( 6534): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6534): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  973): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6558 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/ActivityManager(  973): Killing 6161:com.google.android.gm/u0a53 (adj 15): empty #11
,I/ActivityManager(  973): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6578 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  973): failed to open /acct/uid_10053/pid_6161/cgroup.procs: No such file or directory
I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5642): 
,I/Icing   ( 5601): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,W/ResourcesManager( 6578): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ResourcesManager( 6558): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5642): 
,I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5642): 
I/Icing   ( 5601): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/jxcore-log( 5642): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5642): 
D/CalendarProvider2( 6578): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3534ea0e
I/ActivityManager(  973): Killing 6367:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10011/pid_6367/cgroup.procs: No such file or directory
,D/CalendarProvider2( 6578): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6578): Created com.android.providers.calendar.CalendarAlarmManager@29e84c4b(com.android.providers.calendar.CalendarProvider2@3534ea0e)
D/AlertService( 6243): No fired or scheduled alerts
,I/NotificationManager( 6243): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6243): com.android.calendar: cancel(20) by com.android.calendar
,D/AlertService( 6243): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  973): Killing 6390:com.android.gallery3d/u0a23 (adj 15): empty #11
D/BluetoothManagerService(  973): Message: 20
D/BluetoothManagerService(  973): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c1842f1:true
,W/libprocessgroup(  973): failed to open /acct/uid_10023/pid_6390/cgroup.procs: No such file or directory
,D/BluetoothAdapterService(544039463)( 1967): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@ab25035
D/BluetoothAdapterService(544039463)( 1967): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@ab25035
D/AlarmScheduler( 6243): No events found starting within 1 week.
,I/ActivityManager(  973): Killing 6243:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  973): failed to open /acct/uid_10013/pid_6243/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
I/PCSuite ( 6534): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6534): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6534): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
I/PCSuite ( 6534): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6534): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6534): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
I/PCSuite ( 6534): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6534): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6534): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
I/ActivityManager(  973): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6614 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6558): Create singleton instance
,D/UEI.SmartControl( 6614): Quickset Services start...
I/UEI.SmartControl( 6614): Manufacture = LGE
D/UEI.SmartControl( 6614): File observer start...
,E/UEI.SmartControl( 6614): IR Port is disabled: false
D/UEI.SmartControl( 6614): Starting file observer...
D/UEI.SmartControl( 6614): Extracting JNI libs...
D/UEI.SmartControl( 6614): --- this system supports 32-bit or 64-bit only
I/AudioManager( 6558): getMode name:com.lge.qremote
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6497): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
D/CalendarProviderBroadcastReceiver( 6578): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 6578): [IntentService] WakeLock acquire, start IntentSerivce
D/UEI.SmartControl( 6614): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6614): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6614): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/CalendarProvider2( 6578): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6578): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6578): [getOrCreateCalendarAlarmManager]
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
I/UEI.SmartControl( 6614): --- Selecting new region: 2
,I/UEI.SmartControl( 6614): -- Running on KitKat(19) and above! JNI will be used.
D/CalendarProvider2( 6578): [IntentService] Release Lock
D/CalendarProvider2( 6578): CalendarProviderIntentService.onDestroy()
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/UEI.SmartControl( 6614): Platform has CIR...
D/UEI.SmartControl( 6614): NO CIR support, need to check package...
,I/UEI.SmartControl( 6614): Model: LG-D722 uses JNI
D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
D/UEI.SmartControl( 6614): QS Service created
I/PCSuite ( 6534): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6534): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6497): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6497): MCCMNC not supported: null
I/PCSuite ( 6534): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6534): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,E/UEI.SmartControl( 6614): QS start get config
,D/UEI.SmartControl( 6614): Loading JNI Libs...
,D/UEI.SmartControl( 6614):  configuring local db...
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/art     (  973): Explicit concurrent mark sweep GC freed 19942(915KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.538ms total 175.374ms
,I/ActivityManager(  973): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6639 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/UEI.SmartControl( 6614):  ---- Has DB8: true
,D/UEI.SmartControl( 6614): QS start statue = true Error code = 0
D/UEI.SmartControl( 6614): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 6614): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6614): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6614): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6614): IrrcClient ++ 
D/irrcClient( 6614): getIrrcService ++ 
,D/irrcClient( 6614): getIrrcService -- 
D/irrcClient( 6614): IrrcClient -- 
W/irrc_jni( 6614): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6614): Services init done
I/UEI.SmartControl( 6614): Device manager: loading config....
D/UEI.SmartControl( 6614): QS Service init finished
,D/UEI.SmartControl( 6614): QS Service version name: 0.1.73
D/UEI.SmartControl( 6614): QS Service version code: 1073
D/UEI.SmartControl( 6614): Service requested: Control
D/UEI.SmartControl( 6614): Config is loaded...
D/UEI.SmartControl( 6614):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6614): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6614): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6614): Internal service binding...
D/UEI.SmartControl( 6614): -----IControl: 11
D/UEI.SmartControl( 6614): Caller: com.lge.qremote
D/UEI.SmartControl( 6614): ------------ IControl registerCallback...
I/UEI.SmartControl( 6614): Registering callback...
D/UEI.SmartControl( 6614): -----IControl: 19
D/UEI.SmartControl( 6614): Caller: com.lge.qremote
I/UEI.SmartControl( 6614): Registering Services Ready callback...
I/UEI.SmartControl( 6614): Notify client services are ready...
D/UEI.SmartControl( 6614): -----IControl: 8
D/UEI.SmartControl( 6614): Caller: com.lge.qremote
,D/PhoneMonitor( 6639): Register our PhoneStateListener
I/ActivityManager(  973): Killing 6441:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/ActivityManager(  973): Killing 6413:com.android.contacts/u0a18 (adj 15): empty #12
,W/libprocessgroup(  973): failed to open /acct/uid_10069/pid_6441/cgroup.procs: No such file or directory
,W/libprocessgroup(  973): failed to open /acct/uid_10018/pid_6413/cgroup.procs: No such file or directory
D/CAR.SERVICE( 6325): mConnectedToCar = false, abort
,E/ActivityThread( 6325): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1e9761d0 that was originally bound here
E/ActivityThread( 6325): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1e9761d0 that was originally bound here
E/ActivityThread( 6325): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6325): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6325): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6325): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6325): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6325): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6325): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6325): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6325): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6325): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6325): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6325): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6325): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6325): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6325): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6325): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6325): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6325): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6325): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6325): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6325): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6325): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6325): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6325): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1c68bc0b that was originally bound here
E/ActivityThread( 6325): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1c68bc0b that was originally bound here
E/ActivityThread( 6325): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6325): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6325): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6325): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6325): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6325): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6325): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6325): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6325): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6325): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6325): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6325): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6325): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6325): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6325): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6325): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6325): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6325): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6325): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6325): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6325): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6325): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  973): Unbind failed: could not find connection for android.os.BinderProxy@2f6d7247
I/ActivityManager(  973): Killing 6325:com.google.android.gms:car/u0a6 (adj 15): empty #11
,D/PhoneMonitor( 6639): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,W/ProcessCpuTracker(  973): Skipping unknown process pid 6662
V/TelephonyAutoProfiling( 6639): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6639): [parse] Load xml
V/TelephonyAutoProfiling( 6639): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6639): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6639): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  973): failed to open /acct/uid_10006/pid_6325/cgroup.procs: No such file or directory
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AudioManager( 6558): getMode name:com.lge.qremote
I/CheckinService( 5601): Checkin interval check for package: unspecified last checkin: 1454440650932 min interval config: 0 actual interval: 23419
,I/CheckinService( 5601): Checking schedule, now: 1454440674368 next: 1454440680885
I/CheckinService( 5601): active receiver: disabled
I/AudioManager( 6558): getMode name:com.lge.qremote
,I/ActivityManager(  973): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6668 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6668): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6668): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6668): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6668): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6668): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6668): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6668): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  486): init target 500000
W/ActivityThread( 6668): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
W/System  ( 6668): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@10b573c4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6668): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6668): GMSCore installation verified
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/ConfigStore( 6668): Config Database version: 1
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/charger_monitor(  486): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
D/WifiController(  973): battery changed pluggedType: 2
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/MediaRouter( 6668): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6668): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6668): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  973): Killing 6459:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10086/pid_6459/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6668): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  973): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6709 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6668): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6668): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  973): Killing 6066:com.android.vending/u0a36 (adj 15): empty #11
,I/rmt_storage(  274): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  274): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  274): wakelock acquired: 1, error no: 42
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
W/libprocessgroup(  973): failed to open /acct/uid_10036/pid_6066/cgroup.procs: No such file or directory
,I/NotificationManager( 6668): com.google.android.music: cancel(1061) by com.google.android.music
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  274): 
I/rmt_storage(  274): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/ResourcesManager( 6709): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6709): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6709): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/LGEmail ( 6709): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6709): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/eas_req ( 6709): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  973): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6744 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6709): JNI_OnLoad()
I/HubEmail( 6709): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6709): registerNatives()
I/HubEmail( 6709): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6709): registerNativeMethods()
I/HubEmail( 6709): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6709): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  973): Killing 6299:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10061/pid_6299/cgroup.procs: No such file or directory
,W/Settings( 6709): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6744): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6744): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6744): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6744): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6744): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6744): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6744): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6744): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  973): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6779 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 6744): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6744): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6744): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6744): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6744): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6744): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  973): Killing 6578:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  973): failed to open /acct/uid_10014/pid_6578/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/AppUp4:AppBoxCP( 6779): onCreate
,W/AppUp4:DB( 6779):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6779):  setFingerPrint start
I/AppUp4:DB( 6779):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6779):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6779):  SDK version = 0
I/AppUp4:DB( 6779):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6779): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6779): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6779): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6779): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6779): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6779): onReceive
I/AppUp4:CustModeStarterReceiver( 6779): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6779): Context : android.app.ReceiverRestrictedContext@2c298628
D/AppUp4:CustFacade( 6779): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6779): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6779): begin check event
I/AppUp4:CustModeStarterReceiver( 6779): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6779): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6779): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6779): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6779): handleAsyncCustNotification do not startCustService
I/ActivityManager(  973): Killing 6497:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  973): failed to open /acct/uid_1000/pid_6497/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3169): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3169): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3169): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 6639): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6639): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3242): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  973): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6804 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 298us total 23.974ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.526ms
,V/DownloadManager( 3242): DownloadService onCreate
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 28.123ms
,I/NotificationManager( 3242): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3242): in removeSpuriousFiles
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@26d00d15 on behalf of 3242
I/DownloadManager( 3242): in trimDatabase
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@1dd0282a on behalf of 3242
,V/DownloadManager( 3242): DownloadService onStartCommand
V/DownloadManager( 3242): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@35316591 on behalf of 3242
I/ActivityManager(  973): Killing 6534:com.lge.sync/1000 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_1000/pid_6534/cgroup.procs: No such file or directory
,V/DownloadManager( 3242): DownloadService onDestroy
D/WeatherAncestor( 2722): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:17:57
D/UpdateThreadPoolManager( 2722): 2 : This is isUpdating : false
D/WeatherAncestor( 2722): connectivity changed - connection : true
D/Weather_cast( 2722): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2722): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:17:57
D/WeatherService( 2722): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  973): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6834 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  973): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2722): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2722): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2722): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6834): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6834): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6834): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6834): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6834): MmsConfig.loadFromDatabase
E/Babel_SMS( 6834): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6834): MmsConfig.loadFromResources
,E/Babel_SMS( 6834): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6834): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6834): CheckpointMarkThreadRoots callback created = 0xb042d880
,I/art     ( 6834): CheckpointMarkThreadRoots callback created = 0xb042d860
,D/SensorManager( 6834): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6834): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6834): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6834): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6834): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6834): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6834): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6834): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6834): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6834): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6834): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6834): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6834): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6834): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6834): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6834): found sensor: Motion Accel, handle=46
,W/Settings( 6834): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6834): startup - clean
I/Babel   ( 6834): deleted: false for 0
,I/ActivityManager(  973): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6869 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6834): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6834): Unsupported mime audio/adpcm
W/AudioCapabilities( 6834): Unsupported mime audio/g726
,W/AudioCapabilities( 6834): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6834): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6834): Unsupported mime video/mjpg
W/VideoCapabilities( 6834): Unsupported mime video/theora
,W/AudioCapabilities( 6834): Unsupported mime audio/evrc
,W/AudioCapabilities( 6834): Unsupported mime audio/qcelp
W/VideoCapabilities( 6834): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6834): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6834): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6834): Unsupported mime audio/evrc
W/VideoCapabilities( 6834): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6834): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6834): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6834): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6834): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6834): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6834): onServiceConnected
,W/Babel   ( 6834): Attempted to change video mute state without an active call.
I/NotificationManager( 6834): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 6834): propertyValue:false
,I/Babel   ( 6834): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  973): Killing 6614:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6558): android.os.DeadObjectException
,W/System.err( 6558): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6558): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6558): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6558): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6558): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6558): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6558): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6558): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6558): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6558): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6558): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6558): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6558): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6558): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6558): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6558): android.os.DeadObjectException
W/System.err( 6558): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6558): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6558): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6558): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6558): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6558): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6558): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6558): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6558): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6558): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6558): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6558): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6558): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6558): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6558): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  973): failed to open /acct/uid_10089/pid_6614/cgroup.procs: No such file or directory
W/ActivityManager(  973): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  973): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6901 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6869): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6869): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6869): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 6869): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6869):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6869):   adb logcat -s GAv4
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6869): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/UEI.SmartControl( 6901): Quickset Services start...
I/UEI.SmartControl( 6901): Manufacture = LGE
,D/UEI.SmartControl( 6901): File observer start...
E/UEI.SmartControl( 6901): IR Port is disabled: false
D/UEI.SmartControl( 6901): Starting file observer...
D/UEI.SmartControl( 6901): Extracting JNI libs...
D/UEI.SmartControl( 6901): --- this system supports 32-bit or 64-bit only
W/GAv4    ( 6869): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/UEI.SmartControl( 6901): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6901): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6901): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/GAv4    ( 6869): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6869): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/UEI.SmartControl( 6901): --- Selecting new region: 2
I/UEI.SmartControl( 6901): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6901): Platform has CIR...
D/UEI.SmartControl( 6901): NO CIR support, need to check package...
I/UEI.SmartControl( 6901): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6901): QS Service created
E/UEI.SmartControl( 6901): QS start get config
,D/UEI.SmartControl( 6901): Loading JNI Libs...
D/UEI.SmartControl( 6901):  configuring local db...
,I/CheckinService( 5601): Done disabling old GoogleServicesFramework version
,D/UEI.SmartControl( 6901):  ---- Has DB8: true
I/WebViewFactory( 6869): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/UEI.SmartControl( 6901): QS start statue = true Error code = 0
D/UEI.SmartControl( 6901): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6901): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6901): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6901): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6901): IrrcClient ++ 
D/irrcClient( 6901): getIrrcService ++ 
D/irrcClient( 6901): getIrrcService -- 
D/irrcClient( 6901): IrrcClient -- 
,W/irrc_jni( 6901): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6901): Services init done
I/UEI.SmartControl( 6901): Device manager: loading config....
D/UEI.SmartControl( 6901): QS Service init finished
D/UEI.SmartControl( 6901): QS Service version name: 0.1.73
D/UEI.SmartControl( 6901): QS Service version code: 1073
D/UEI.SmartControl( 6901): Service requested: Control
,D/UEI.SmartControl( 6901): Config is loaded...
I/LibraryLoader( 6869): Time to load native libraries: 2 ms (timestamps 6601-6603)
,I/LibraryLoader( 6869): Expected native library version number "",actual native library version number ""
D/UEI.SmartControl( 6901):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6901): Notify AllClients services are ready: 0
V/WebViewChromiumFactoryProvider( 6869): Binding Chromium to main looper Looper (main, tid 1) {1f0f6585}
,I/LibraryLoader( 6869): Expected native library version number "",actual native library version number ""
I/chromium( 6869): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/UEI.SmartControl( 6901): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6901): Internal service binding...
D/UEI.SmartControl( 6901): -----IControl: 11
D/UEI.SmartControl( 6901): Caller: com.lge.qremote
D/UEI.SmartControl( 6901): ------------ IControl registerCallback...
I/UEI.SmartControl( 6901): Registering callback...
D/UEI.SmartControl( 6901): -----IControl: 19
D/UEI.SmartControl( 6901): Caller: com.lge.qremote
I/UEI.SmartControl( 6901): Registering Services Ready callback...
I/BrowserStartupController( 6869): Initializing chromium process, singleProcess=true
I/UEI.SmartControl( 6901): Notify client services are ready...
W/art     ( 6869): Attempt to remove local handle scope entry from IRT, ignoring
D/UEI.SmartControl( 6901): -----IControl: 8
,E/SysUtils( 6869): ApplicationContext is null in ApplicationStatus
D/UEI.SmartControl( 6901): Caller: com.lge.qremote
W/chromium( 6869): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6869): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6869): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6869): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6869): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6869): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6869): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6869): Remote Branch: 
I/Adreno-EGL( 6869): Local Patches: 
I/Adreno-EGL( 6869): Reconstruct Branch: 
,I/NSApplication( 6869): Starting up...
,V/AudioPolicyService(  284): registerClient() client 0xb4027260, uid 10079
,W/AudioManagerAndroid( 6869): Requires BLUETOOTH permission
I/ActivityManager(  973): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6973 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  973): Killing 6668:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/ActivityManager(  973): Killing 6558:com.lge.qremote/u0a106 (adj 15): empty #12
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  973): failed to open /acct/uid_10081/pid_6668/cgroup.procs: No such file or directory
,W/libprocessgroup(  973): failed to open /acct/uid_10106/pid_6558/cgroup.procs: No such file or directory
I/ActivityManager(  973): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6995 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  973): Killing 6709:com.lge.email/u0a21 (adj 15): empty #11
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
,I/[SystemUI]Clock( 1371): called onTimeUpdated()
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
,I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
W/libprocessgroup(  973): failed to open /acct/uid_10021/pid_6709/cgroup.procs: No such file or directory
,D/WeatherService( 2722): 2 : TimeTick Intent has been received, Time(hour:min:sec) 20:18:0
,D/WeatherService( 2722): 2 : TimeTick Intent And Screen On
D/WeatherService( 2722): 2 : SDK version : 21
W/ActivityManager(  973): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2722): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2722): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2722): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2722): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2722): 2 : This is isUpdating : false
D/WeatherService( 2722): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2722): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2722): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2722): 2 : Fixed theme : optimus
D/WeatherReflect( 2722): 2 : Map key string is -2
,D/lim     ( 2722): 2 : time = 20:18
I/WeatherReflect( 2722): Model Name : LG-D722
,D/WeatherTheme( 2722): 2 : Different view - status_min_formatted : 17 != 18
D/WeatherTheme( 2722): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
W/ResourcesManager( 6995): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/WeatherReflect( 2722): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2722): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2722): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2722): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2722): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2722): forecast size is 0
,D/Theme   ( 2722): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2722): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2722): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2722): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2722): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2722): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2722): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2722): url is : null
D/Theme   ( 2722): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2722): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2722): 2 : update view, appWidgetId: 2
D/WeatherService( 2722): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 20:18:0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/art     (  973): Explicit concurrent mark sweep GC freed 19295(991KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 1.935ms total 144.815ms
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/iu.SyncManager( 5601): SYNC; picasa accounts
,D/NetworkLogImpl( 5601): Loaded NetworkSpeedPredictor
I/iu.Environment( 5601): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  973): Killing 6744:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/iu.UploadsManager( 5601): num queued entries: 0
I/iu.UploadsManager( 5601): num updated entries: 0
I/iu.SyncManager( 5601): NEXT; no task
,W/libprocessgroup(  973): failed to open /acct/uid_1000/pid_6744/cgroup.procs: No such file or directory
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  973): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7037 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7037): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7037): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7037): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7037): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7037): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7037): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7037): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7037): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7037): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@10b573c4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7037): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7037): GMSCore installation verified
,I/ConfigStore( 7037): Config Database version: 1
,I/MediaRouter( 7037): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7037): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 7037): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7037): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  973): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7072 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7037): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7037): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 7072): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7072): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7072): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  973): Killing 6779:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/jxcore-log( 5642): Test app app.js loaded
I/jxcore-log( 5642): 
,W/libprocessgroup(  973): failed to open /acct/uid_10011/pid_6779/cgroup.procs: No such file or directory
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5642): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f3df72 added. We now have 1 listener(s)
D/BluetoothAdapterService(544039463)( 1967): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@ab25035
I/NotificationManager( 7037): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7072): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/jxcore-log( 5642): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5642): 
,D/LGEmail ( 7072): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/chromium( 5642): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/eas_req ( 7072): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  973): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7098 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7072): JNI_OnLoad()
I/HubEmail( 7072): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7072): registerNatives()
I/HubEmail( 7072): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7072): registerNativeMethods()
I/HubEmail( 7072): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7072): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7072): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  973): Killing 6639:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10038/pid_6639/cgroup.procs: No such file or directory
D/LGDMClient( 7098): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7098): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7098): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7098): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7098): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7098): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7098): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7098): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  973): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7122 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7098): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7098): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7098): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 7098): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7098): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7098): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  973): Killing 6804:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10051/pid_6804/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7122): onCreate
W/AppUp4:DB( 7122):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7122):  setFingerPrint start
I/AppUp4:DB( 7122):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7122):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7122):  SDK version = 0
I/AppUp4:DB( 7122):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7122): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7122): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7122): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7122): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7122): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7122): onReceive
I/AppUp4:CustModeStarterReceiver( 7122): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7122): Context : android.app.ReceiverRestrictedContext@2c298628
D/AppUp4:CustFacade( 7122): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7122): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7122): begin check event
I/AppUp4:CustModeStarterReceiver( 7122): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7122): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 7122): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7122): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7122): handleAsyncCustNotification do not startCustService
I/ActivityManager(  973): Killing 6834:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  973): failed to open /acct/uid_10061/pid_6834/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3169): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3169): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3169): networkInfo.isConnected() = false
I/ActivityManager(  973): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7141 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PhoneMonitor( 7141): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7141): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7141): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  973): Killing 6869:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10079/pid_6869/cgroup.procs: No such file or directory
,V/DownloadManager( 3242): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3242): DownloadService onCreate
I/CheckinService( 5601): Checkin interval check for package: unspecified last checkin: 1454440650932 min interval config: 0 actual interval: 31927
,I/NotificationManager( 3242): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3242): in removeSpuriousFiles
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@3f9f8f7 on behalf of 3242
I/DownloadManager( 3242): in trimDatabase
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/PhoneMonitor( 7141): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7141): [loadFeatureFromXml] *** start feature loading from xml
I/ActivityManager(  973): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7168 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
D/TelephonyAutoProfiling( 7141): [parse] Load xml
V/DownloadManager( 3242): DownloadService onStartCommand
,V/TelephonyAutoProfiling( 7141): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7141): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3242): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/art     (  306): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 350us total 32.174ms
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@1a319282 on behalf of 3242
,I/art     (  306): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 26.406ms
,D/PhoneMonitor( 7141): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 5601): Checking schedule, now: 1454440682961 next: 1454440680885
I/CheckinService( 5601): active receiver: enabled
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.007ms
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@144b2d93 on behalf of 3242
,V/DownloadManager( 3242): DownloadService onDestroy
I/CheckinService( 5601): Preparing to send checkin request
,D/WeatherAncestor( 2722): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:18:3
D/UpdateThreadPoolManager( 2722): 2 : This is isUpdating : false
D/WeatherAncestor( 2722): connectivity changed - connection : true
D/Weather_cast( 2722): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2722): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:18:3
D/WeatherService( 2722): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/EventLogService( 5601): Accumulating logs since 1454440643280
,I/ActivityManager(  973): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7198 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  973): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2722): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2722): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2722): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7198): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5601): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5601): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 7198): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7198): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7198): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7198): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7198): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7198): MmsConfig.loadFromResources
E/Babel_SMS( 7198): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7198): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7198): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 7198): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7198): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7198): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7198): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7198): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7198): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7198): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7198): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7198): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7198): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7198): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7198): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7198): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7198): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7198): found sensor: Motion Accel, handle=46
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 7198): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7198): startup - clean
I/Babel   ( 7198): deleted: false for 0
,I/art     ( 7198): CheckpointMarkThreadRoots callback created = 0xb042d910
,I/art     ( 7198): CheckpointMarkThreadRoots callback created = 0xb042d8f0
,I/ActivityManager(  973): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7236 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  973): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7243 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/AudioCapabilities( 7198): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 7198): Unsupported mime audio/adpcm
,W/AudioCapabilities( 7198): Unsupported mime audio/g726
W/AudioCapabilities( 7198): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7198): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7198): Unsupported mime video/mjpg
W/VideoCapabilities( 7198): Unsupported mime video/theora
,W/ResourcesManager( 7243): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7243): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/AudioCapabilities( 7198): Unsupported mime audio/evrc
W/AudioCapabilities( 7198): Unsupported mime audio/qcelp
W/VideoCapabilities( 7198): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7198): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7198): Unsupported mime audio/qcelp
W/AudioCapabilities( 7198): Unsupported mime audio/evrc
,W/VideoCapabilities( 7198): Unsupported mime video/mp4v-esdp
,I/MultiDex( 7243): VM with version 2.1.0 has multidex support
I/MultiDex( 7243): install
I/MultiDex( 7243): VM has multidex support, MultiDex support library is disabled.
,I/VideoCapabilities( 7198): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7198): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7198): Unrecognized profile 2130706433 for video/avc
V/JNIHelp ( 7243): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/VideoCapabilities( 7198): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7198): Unrecognized profile 2130706433 for video/avc
,W/ActivityThread( 7243): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7243): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26d00d15: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7243): Installed default security provider GmsCore_OpenSSL
I/art     (  973): Explicit concurrent mark sweep GC freed 16905(907KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.483ms total 166.354ms
,I/NotificationManager( 7243): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7243): com.google.android.gms: cancel(39789) by com.google.android.gms
I/vclib   ( 7198): onServiceConnected
W/Babel   ( 7198): Attempted to change video mute state without an active call.
I/NotificationManager( 7198): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/GAv4    ( 7236): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7236):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7236):   adb logcat -s GAv4
D/libc-netbsd( 7198): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7198): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7198): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7198): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7236): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7198): propertyValue:false
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7236): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7236): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/art     ( 7243): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7243): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7236): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7236): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7198): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 7236): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7236): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  973): Killing 6901:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,D/NativeLibraryUtils( 7243): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  973): failed to open /acct/uid_10089/pid_6901/cgroup.procs: No such file or directory
,D/WVCdm   (  284): Instantiating CDM.
,I/WVCdm   (  284): CdmEngine::OpenSession
I/WVCdm   (  284): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  284): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  284): Properties::GetOEMCryptoPath: null. applies level3
,W/WVCdm   (  284): L1 library not specified. Falling Back to L3
I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/WVCdm   (  284): PrepareKeyRequest: nonce=1635609214
I/WebViewFactory( 7236): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7236): Time to load native libraries: 2 ms (timestamps 1925-1927)
I/LibraryLoader( 7236): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7236): Binding Chromium to main looper Looper (main, tid 1) {1f0f6585}
I/LibraryLoader( 7236): Expected native library version number "",actual native library version number ""
I/chromium( 7236): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7236): Initializing chromium process, singleProcess=true
,W/art     ( 7236): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7236): ApplicationContext is null in ApplicationStatus
W/chromium( 7236): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7236): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7236): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7236): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7236): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7236): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7236): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7236): Remote Branch: 
I/Adreno-EGL( 7236): Local Patches: 
I/Adreno-EGL( 7236): Reconstruct Branch: 
V/AudioPolicyService(  284): registerClient() client 0xb3846c80, uid 10079
,W/AudioManagerAndroid( 7236): Requires BLUETOOTH permission
I/NSApplication( 7236): Starting up...
,I/ActivityManager(  973): Killing 7037:com.google.android.music:main/u0a81 (adj 15): empty #11
I/art     ( 7243): CheckpointMarkThreadRoots callback created = 0xb04ccef0
,I/art     ( 7243): CheckpointMarkThreadRoots callback created = 0xb04ccee0
,W/libprocessgroup(  973): failed to open /acct/uid_10081/pid_7037/cgroup.procs: No such file or directory
,I/ActivityManager(  973): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7331 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/dex2oat ( 7329): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7329): dex2oat took 103.167ms (threads: 4)
,I/Adreno-EGL( 7243): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7243): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7243): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7243): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7243): Remote Branch: 
I/Adreno-EGL( 7243): Local Patches: 
I/Adreno-EGL( 7243): Reconstruct Branch: 
,W/ActivityManager(  973): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7331): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 5496): Explicit concurrent mark sweep GC freed 2813(112KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 469us total 28.793ms
,I/ActivityManager(  973): Process com.lge.email (pid 7072) has died
,V/AlarmManager(  973): RTC_WAKEUP set : Alarm{150b8b36 type 0 when 1454440680885 com.google.android.gms} when 1454440680885
I/ActivityManager(  973): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7361 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  973): RTC_WAKEUP set : Alarm{1c18ea37 type 0 when 1454440684505 com.android.vending} when 1454440684505
W/ActivityManager(  973): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/GAV2    ( 7331): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  973): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/WVCdm   (  284): CdmEngine::OpenSession
I/Gmail   ( 7331): Observing account changes for notifications
,W/ActivityManager(  973): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 7331): Error finding the version of the Email provider.....
E/Gmail   ( 7331): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7331): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7331): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7331): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7331): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7331): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7331): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7331): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7331): We do not support migrating this version of the Email provider.
I/Gmail   ( 7331): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7361): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Gmail   ( 7331): notifyAccountChanged
I/Gmail   ( 7331): getAccountsCursor
,I/Gmail   ( 7331): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7331): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
I/Gmail   ( 7331): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7331): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  973): Process com.lge.appbox.client (pid 7122) has died
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7331): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7361): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7361): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7361): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7361): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@1d2235c9 on behalf of 7361
,D/Finsky  ( 7361): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7361): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7361): Skipping gmscore version check
I/ActivityManager(  973): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7419 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/Finsky  ( 7361): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7361): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ResourcesManager( 7419): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/WVCdm   (  284): CdmEngine::CloseSession
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
I/ActivityManager(  973): Process com.lge.lgdmsclient (pid 7098) has died
D/WVCdm   (  284): PrepareKeyRequest: nonce=1919181520
D/Finsky  ( 7361): [925] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7361): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/BluetoothManagerService(  973): Message: 20
,D/BluetoothManagerService(  973): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d1453e9:true
D/BluetoothAdapterService(544039463)( 1967): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@ab25035
D/BluetoothAdapterService(544039463)( 1967): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@ab25035
I/ActivityManager(  973): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7439 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/MusicStore( 7439): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7439): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7439): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7439): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7439): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7439): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7439): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7439): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7439): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@10b573c4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7439): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7439): GMSCore installation verified
I/ConfigStore( 7439): Config Database version: 1
,I/MediaRouter( 7439): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7439): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7439): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7439): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  973): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7470 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 7470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7470): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7470): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/GHttpClientFactory( 7439): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7439): Using platform SSLCertificateSocketFactory
,I/art     (  973): Explicit concurrent mark sweep GC freed 21400(986KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.433ms total 160.058ms
,I/LGEmail ( 7470): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7470): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/NotificationManager( 7439): com.google.android.music: cancel(1061) by com.google.android.music
,D/eas_req ( 7470): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 115001761209; DSPS: 3866760; Offset : -3012500325
,I/ActivityManager(  973): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7501 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7470): JNI_OnLoad()
I/HubEmail( 7470): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7470): registerNatives()
I/HubEmail( 7470): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7470): registerNativeMethods()
I/HubEmail( 7470): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7470): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7470): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  973): Killing 7141:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  973): failed to open /acct/uid_10038/pid_7141/cgroup.procs: No such file or directory
,D/LGDMClient( 7501): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7501): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7501): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7501): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7501): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7501): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7501): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7501): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  973): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7525 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7501): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7501): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7501): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7501): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7501): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 7501): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  973): Killing 7168:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10051/pid_7168/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7525): onCreate
W/AppUp4:DB( 7525):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7525):  setFingerPrint start
I/AppUp4:DB( 7525):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7525):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7525):  SDK version = 0
I/AppUp4:DB( 7525):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7525): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7525): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7525): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7525): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7525): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7525): onReceive
I/AppUp4:CustModeStarterReceiver( 7525): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 7525): Context : android.app.ReceiverRestrictedContext@2c298628
D/AppUp4:CustFacade( 7525): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7525): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7525): begin check event
I/AppUp4:CustModeStarterReceiver( 7525): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7525): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7525): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7525): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7525): handleAsyncCustNotification do not startCustService
I/ActivityManager(  973): Killing 7236:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
W/libprocessgroup(  973): failed to open /acct/uid_10079/pid_7236/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3169): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3169): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3169): networkInfo.isConnected() = true
D/PhoneState( 3169): setPdpRejectCasuse : false
I/ActivityManager(  973): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7544 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 21.531ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.756ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.475ms
,D/PhoneMonitor( 7544): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7544): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7544): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  973): Killing 6973:com.android.chrome/u0a48 (adj 15): empty #11
,D/PhoneMonitor( 7544): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7544): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7544): [parse] Load xml
V/TelephonyAutoProfiling( 7544): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7544): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7544): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/WVCdm   (  284): CdmEngine::CloseSession
,W/libprocessgroup(  973): failed to open /acct/uid_10048/pid_6973/cgroup.procs: No such file or directory
V/DownloadManager( 3242): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/WVCdm   (  284): L3 Terminate.
V/DownloadManager( 3242): DownloadService onCreate
I/NotificationManager( 3242): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/DownloadManager( 3242): in removeSpuriousFiles
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@36710fef on behalf of 3242
I/DownloadManager( 3242): in trimDatabase
V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@22d8cafc on behalf of 3242
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  973): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7567 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3242): DownloadService onStartCommand
V/DownloadManager( 3242): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 5601): Checkin interval check for package: unspecified last checkin: 1454440650932 min interval config: 0 actual interval: 37769
V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@345aefda on behalf of 3242
,V/DownloadManager( 3242): DownloadService onDestroy
,I/ActivityManager(  973): Killing 6995:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10086/pid_6995/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2722): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:18:8
D/UpdateThreadPoolManager( 2722): 2 : This is isUpdating : false
D/WeatherAncestor( 2722): connectivity changed - connection : true
D/Weather_cast( 2722): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2722): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:18:8
D/WeatherService( 2722): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  973): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2722): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2722): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2722): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/Adreno-EGL( 7243): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7243): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7243): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7243): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7243): Remote Branch: 
I/Adreno-EGL( 7243): Local Patches: 
I/Adreno-EGL( 7243): Reconstruct Branch: 
,I/ActivityManager(  973): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7590 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Adreno-EGL( 7243): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7243): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7243): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7243): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7243): Remote Branch: 
I/Adreno-EGL( 7243): Local Patches: 
I/Adreno-EGL( 7243): Reconstruct Branch: 
,I/MusicWidget( 2637): mDelayedStopHandler : unbind
,I/MusicBrowser( 2729): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2729): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2729): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2729): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2729): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
,D/MusicBrowser( 2729): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
,I/MusicBrowser( 2729): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2729): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  973):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2944bab1com.lge.music.MediaPlaybackService$6@190b9b96
,D/MusicBrowser( 2729): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2729): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2729): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2729): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2729): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@33a4dcd4
I/MusicBrowser( 2729): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2729): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
,I/MusicBrowser( 2729): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2729): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2729): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
,I/MusicBrowser( 2729): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2729): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2729): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2729): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2729): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2729): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2729): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2729): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2729): reset
V/MediaPlayer[Native]( 2729): setListener
,V/MediaPlayer[Native]( 2729): disconnect
V/MediaPlayer[Native]( 2729): destructor
V/AudioFlinger(  284): releasing 19 from 2729 for -1
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
V/MediaPlayer[Native]( 2729): disconnect
W/ContextImpl( 7590): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/MusicBrowser( 2729): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7590): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/CheckinRequestBuilder( 5601): Classify the device as Phone.
,I/SmartShareClient( 2729): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2729): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2729): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2729): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2729): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2729): [SmartShareManagerClient] unregisterListener: 526197527
W/SmartShareClient( 2729): [SmartShareManagerClient] unregisterListener invalid listener: 526197527
I/SmartShareClient( 2729): [SmartShareManagerClient] terminate service: 2729/MediaPlaybackService/525965594
I/GAv4    ( 7590): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7590):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7590):   adb logcat -s GAv4
E/HomeCloudIF( 2729): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2729): [SmartShareManagerClient] unbindService context:android.app.Application@36232304
,V/CloudHub( 2729): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2729): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
I/CloudHub( 2729): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
W/ContextImpl( 7590): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/MusicBrowser( 2729): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2729): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7590): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/CloudHub( 2729): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
I/ActivityManager(  973): Killing 7331:com.google.android.gm/u0a53 (adj 15): empty #11
W/GAv4    ( 7590): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  973): failed to open /acct/uid_10053/pid_7331/cgroup.procs: No such file or directory
,W/GAv4    ( 7590): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,D/libc-netbsd( 5601): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5601): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/GAv4    ( 7590): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/libc-netbsd( 5601): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5601): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 5601): propertyValue:false
D/libc-netbsd( 5601): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5601): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5601): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5601): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5601): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5601): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5601): Sending checkin request (9705 bytes)
,I/WebViewFactory( 7590): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7590): Time to load native libraries: 2 ms (timestamps 6763-6765)
,I/LibraryLoader( 7590): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7590): Binding Chromium to main looper Looper (main, tid 1) {1f0f6585}
I/LibraryLoader( 7590): Expected native library version number "",actual native library version number ""
I/chromium( 7590): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7590): Initializing chromium process, singleProcess=true
W/art     ( 7590): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7590): ApplicationContext is null in ApplicationStatus
W/chromium( 7590): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7590): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7590): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7590): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7590): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7590): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7590): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7590): Remote Branch: 
I/Adreno-EGL( 7590): Local Patches: 
I/Adreno-EGL( 7590): Reconstruct Branch: 
V/AudioPolicyService(  284): registerClient() client 0xb551c6a0, uid 10079
I/NSApplication( 7590): Starting up...
,W/AudioManagerAndroid( 7590): Requires BLUETOOTH permission
,I/ActivityManager(  973): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7666 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  973): Killing 7361:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  973): failed to open /acct/uid_10036/pid_7361/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 5601): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  973): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7685 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  973): Killing 7439:com.google.android.music:main/u0a81 (adj 15): empty #11
E/ActivityThread( 5601): Failed to find provider info for com.google.android.wearable.settings
W/libprocessgroup(  973): failed to open /acct/uid_10081/pid_7439/cgroup.procs: No such file or directory
,W/ResourcesManager( 7685): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinRequestBuilder( 5601): Classify the device as Phone.
,I/CheckinTask( 5601): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5601): Checking schedule, now: 1454440690044 next: 1454967939039
I/CheckinService( 5601): active receiver: disabled
,I/CheckinService( 5601): Checking schedule, now: 1454440690075 next: 1454967939039
I/CheckinService( 5601): active receiver: disabled
,D/CheckinService( 5601): Recording last checkin time for package unspecified as 1454440690084
I/ActivityManager(  973): Killing 7501:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/ActivityManager(  973): Killing 7470:com.lge.email/u0a21 (adj 15): empty #12
,W/libprocessgroup(  973): failed to open /acct/uid_1000/pid_7501/cgroup.procs: No such file or directory
,W/libprocessgroup(  973): failed to open /acct/uid_10021/pid_7470/cgroup.procs: No such file or directory
I/ActivityManager(  973): Killing 7525:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10011/pid_7525/cgroup.procs: No such file or directory
,I/art     ( 7685): CheckpointMarkThreadRoots callback created = 0xb042d480
I/art     ( 7685): CheckpointMarkThreadRoots callback created = 0xb042d460
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
D/LocationInitializer( 5601): Restart initialization of location
E/MDM     ( 1732): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  973): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7727 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,D/Finsky  ( 7727): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7727): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7727): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7727): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7727): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@3d659ae8 on behalf of 7727
D/Finsky  ( 7727): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7727): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7727): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 7727): Skipping gmscore version check
D/Finsky  ( 7727): [984] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7727): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  973): android: cancelAsUser(2) by android
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  973): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7780 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/LGMDMManager( 7419): Create singleton instance
,D/UEI.SmartControl( 7780): Quickset Services start...
I/UEI.SmartControl( 7780): Manufacture = LGE
I/art     (  973): Explicit concurrent mark sweep GC freed 25696(1209KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.514ms total 156.053ms
,D/UEI.SmartControl( 7780): File observer start...
E/UEI.SmartControl( 7780): IR Port is disabled: false
D/UEI.SmartControl( 7780): Starting file observer...
D/UEI.SmartControl( 7780): Extracting JNI libs...
D/UEI.SmartControl( 7780): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7419): getMode name:com.lge.qremote
,I/AudioManager( 7419): getMode name:com.lge.qremote
D/UEI.SmartControl( 7780): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7780): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7780): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/AudioManager( 7419): getMode name:com.lge.qremote
D/libc-netbsd( 7727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7727): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7727): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
,D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
E/MDM     ( 1732): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5601): Restart initialization of location
I/UEI.SmartControl( 7780): --- Selecting new region: 2
I/UEI.SmartControl( 7780): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7780): Platform has CIR...
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7780): NO CIR support, need to check package...
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
I/UEI.SmartControl( 7780): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7780): QS Service created
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 7727): propertyValue:false
,I/ActivityManager(  973): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7805 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,E/UEI.SmartControl( 7780): QS start get config
,D/UEI.SmartControl( 7780): Loading JNI Libs...
,D/UEI.SmartControl( 7780):  configuring local db...
W/ActivityManager(  973): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7805): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7805): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  973): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7805): Error finding the version of the Email provider.....
E/Gmail   ( 7805): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7805): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7805): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7805): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7805): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7805): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7805): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7805): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7805): We do not support migrating this version of the Email provider.
,W/ActivityManager(  973): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 7805): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinService( 5601): Checkin interval check for package: unspecified last checkin: 1454440690084 min interval config: 0 actual interval: 1574
,I/Gmail   ( 7805): Observing account changes for notifications
W/ActivityManager(  973): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/AudioManager( 7419): getMode name:com.lge.qremote
,I/CheckinService( 5601): Checking schedule, now: 1454440691677 next: 1454967939039
I/CheckinService( 5601): active receiver: disabled
W/ContextImpl( 3611): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/SetupWizard( 7544): Connected to Gservices successfully
,D/UEI.SmartControl( 7780):  ---- Has DB8: true
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7780): QS start statue = true Error code = 0
D/UEI.SmartControl( 7780): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7780): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/UEI.SmartControl( 7780): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7780): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7780): IrrcClient ++ 
,D/irrcClient( 7780): getIrrcService ++ 
D/irrcClient( 7780): getIrrcService -- 
D/irrcClient( 7780): IrrcClient -- 
W/irrc_jni( 7780): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7780): Services init done
D/UEI.SmartControl( 7780): QS Service init finished
I/UEI.SmartControl( 7780): Device manager: loading config....
D/UEI.SmartControl( 7780): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7780): QS Service version code: 1073
D/UEI.SmartControl( 7780): Service requested: Control
,D/UEI.SmartControl( 7780): Config is loaded...
D/UEI.SmartControl( 7780): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7780): Internal service binding...
D/UEI.SmartControl( 7780): -----IControl: 11
D/UEI.SmartControl( 7780): Caller: com.lge.qremote
D/UEI.SmartControl( 7780): ------------ IControl registerCallback...
I/UEI.SmartControl( 7780): Registering callback...
D/UEI.SmartControl( 7780): -----IControl: 19
D/UEI.SmartControl( 7780): Caller: com.lge.qremote
I/UEI.SmartControl( 7780): Registering Services Ready callback...
,I/UEI.SmartControl( 7780): Notify client services are ready...
,D/UEI.SmartControl( 7780):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 7780): -----IControl: 8
D/UEI.SmartControl( 7780): Caller: com.lge.qremote
I/UEI.SmartControl( 7780): Notify AllClients services are ready: 0
I/AudioManager( 7419): getMode name:com.lge.qremote
,I/ActivityManager(  973): Killing 7198:com.google.android.talk/u0a61 (adj 15): empty #11
I/Gmail   ( 7805): notifyAccountChanged
,I/Gmail   ( 7805): getAccountsCursor
I/Gmail   ( 7805): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7805): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  973): Killing 7567:com.lge.drmservice/u0a51 (adj 15): empty #12
,I/Gmail   ( 7805): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7805): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  973): failed to open /acct/uid_10061/pid_7198/cgroup.procs: No such file or directory
,W/libprocessgroup(  973): failed to open /acct/uid_10051/pid_7567/cgroup.procs: No such file or directory
I/AudioManager( 7419): getMode name:com.lge.qremote
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 7419): getMode name:com.lge.qremote
,I/Gmail   ( 7805): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  973): Reconfiguring input devices.  changes=0x00000010
,I/art     (  306): Background concurrent mark sweep GC freed 785(33KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 15.403ms total 53.224ms
,I/ActivityManager(  973): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7890 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  973): Handling package changes for user 0
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
W/ResourcesManager( 7890): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 7890): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7890): MmsConfig.loadMmsSettings
I/Babel_SMS( 7890): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7890): MmsConfig.loadFromDatabase
I/NotificationService(  973): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  973): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  973): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  973): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,E/Babel_SMS( 7890): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7890): MmsConfig.loadFromResources
V/BackupManagerService(  973): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  973): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@236ee488
E/Babel_SMS( 7890): canonicalizeMccMnc: invalid mccmnc nullnull
W/ResourcesManager(  973): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Babel_SMS( 7890): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1785): getDefaultRoute
,D/SensorManager( 7890): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7890): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7890): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7890): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7890): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7890): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7890): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7890): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7890): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7890): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7890): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7890): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7890): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7890): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7890): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7890): found sensor: Motion Accel, handle=46
W/Settings( 7890): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Babel_Crash( 7890): startup - clean
I/art     ( 7890): CheckpointMarkThreadRoots callback created = 0xaaf45510
,I/Babel   ( 7890): deleted: false for 0
,I/art     ( 7890): CheckpointMarkThreadRoots callback created = 0xaaf454f0
W/ResourceType(  973): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/AudioCapabilities( 7890): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7890): Unsupported mime audio/adpcm
W/AudioCapabilities( 7890): Unsupported mime audio/g726
W/AudioCapabilities( 7890): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7890): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7890): Unsupported mime video/mjpg
W/VideoCapabilities( 7890): Unsupported mime video/theora
,W/AudioCapabilities( 7890): Unsupported mime audio/evrc
,W/AudioCapabilities( 7890): Unsupported mime audio/qcelp
W/VideoCapabilities( 7890): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  973): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7926 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/AudioCapabilities( 7890): Unsupported mime audio/amr-wb-plus
D/LocationProviderProxy(  973): applying state to connected service
W/AudioCapabilities( 7890): Unsupported mime audio/qcelp
,W/AudioCapabilities( 7890): Unsupported mime audio/evrc
,W/VideoCapabilities( 7890): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7890): Unsupported profile 4 for video/mp4v-es
,I/AppUp4:AppBoxCP( 7926): onCreate
W/AppUp4:DB( 7926):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7926):  setFingerPrint start
I/AppUp4:DB( 7926):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,W/VideoCapabilities( 7890): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7890): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 7926):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7926):  SDK version = 0
I/AppUp4:DB( 7926):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7926): AppBoxApplication onCreate()
W/VideoCapabilities( 7890): Unrecognized profile 2130706433 for video/avc
I/AppUp4:CustModeStarterReceiver( 7926): onReceive
,I/AppUp4:CustModeStarterReceiver( 7926): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
W/art     ( 7890): Suspending all threads took: 5.847ms
D/AppUp4:CustFacade( 7926): Context : android.app.ReceiverRestrictedContext@2a25ebc5
W/VideoCapabilities( 7890): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 7926): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7926): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7926): begin check event
I/AppUp4:CustModeStarterReceiver( 7926): Event For Nothing, skip.
I/ActivityManager(  973): Killing 2729:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  284): 2729 died, releasing its sessions
V/AudioFlinger(  284):  pid 1751 @ 0
V/AudioFlinger(  284):  pid 3169 @ 1
V/AudioFlinger(  284):  pid 3169 @ 2
,W/libprocessgroup(  973): failed to open /acct/uid_10028/pid_2729/cgroup.procs: No such file or directory
,I/ActivityManager(  973): Killing 7590:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10079/pid_7590/cgroup.procs: No such file or directory
,I/ActivityManager(  973): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7948 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 7890): onServiceConnected
W/Babel   ( 7890): Attempted to change video mute state without an active call.
I/NotificationManager( 7890): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7890): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7890): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 7948): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7948): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7948): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 7890): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7890): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7890): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7890): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 7948): Total System Memory = 906309632
,I/GalleryUtils( 7948): Application Heap = 96 MB
I/AppConfig( 7948): App Tier : NOT_DEF
D/SystemHelper( 7948): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  973): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7973 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  973): Killing 7666:com.android.chrome/u0a48 (adj 15): empty #11
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.253ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.061ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.701ms
,W/libprocessgroup(  973): failed to open /acct/uid_10048/pid_7666/cgroup.procs: No such file or directory
W/ResourcesManager( 7973): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7973): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7973): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7973): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7973): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     (  973): Explicit concurrent mark sweep GC freed 23513(1193KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.225ms total 149.387ms
,I/SystemConfig( 7973): BUILD Country: EU
I/SystemConfig( 7973): BUILD Operator: OPEN
,I/ActivityManager(  973): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7995 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  973): Killing 7685:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10086/pid_7685/cgroup.procs: No such file or directory
,I/SystemConfig( 7973): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7973): existFile = false
,I/SystemConfig( 7973): canReadFile = false
I/SystemConfig( 7973): systemFeature RCS result false
D/SystemConfig( 7973): refreshRcsSupport() :false
I/LockScreenSettings( 7995): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7995): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7995): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7995): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7995): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7995): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  973): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=8012 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  973): Killing 7727:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  973): failed to open /acct/uid_10036/pid_7727/cgroup.procs: No such file or directory
,W/ResourcesManager( 8012): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1932): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  973): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8037 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  973): Killing 7544:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1932): UpdateCorporaTask done [took 108 ms] updated apps [took 108 ms] 
,W/libprocessgroup(  973): failed to open /acct/uid_10038/pid_7544/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Finsky  ( 8037): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 8037): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 8037): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 8037): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 8037): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3242): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3242): created cursor android.database.sqlite.SQLiteCursor@10e5d501 on behalf of 8037
,D/Ads     ( 8037): Skipping gmscore version check
I/ActivityManager(  973): Killing 7805:com.google.android.gm/u0a53 (adj 15): empty #11
,D/Finsky  ( 8037): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 8037): [1] Libraries$2.run: Finished loading 1 libraries.
W/libprocessgroup(  973): failed to open /acct/uid_10053/pid_7805/cgroup.procs: No such file or directory
D/Finsky  ( 8037): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 5601): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 5601): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5601): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 8037): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 7780): Internal timer expired: 1
,I/Icing   ( 5601): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5601): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  973): Killing 7926:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10011/pid_7926/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  973): Killing 7243:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  973): failed to open /acct/uid_10006/pid_7243/cgroup.procs: No such file or directory
,D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
,W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 135008299587; DSPS: 4522335; Offset : -3012523563
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  973): RTC_WAKEUP set : Alarm{4041d1d type 0 when 1454440699114 com.google.android.gms} when 1454440699114
V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{180d6b92 type 2 when 146123 com.google.android.gms} when 146123
,I/EventLogService( 5601): Aggregate from 1454440683159 (log), 1454438899041 (data)
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1732): Vacuum at: now=1454440719075 tag=VacuumService
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 33528(2MB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 13MB/22MB, paused 1.610ms total 110.478ms
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 2205 seconds from now (1454440719640)
,D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/LocationManagerService(  973): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  973): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/LocationManagerService(  973): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  973): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  973): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  973): ALS enabled for SRE
,D/PowerManagerServiceEx(  973): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (30832 ms ago)
D/qdlights(  973): set_light_backlight: 253
,D/qdlights(  973): set_light_backlight: 250
D/qdlights(  973): set_light_backlight: 246
,D/qdlights(  973): set_light_backlight: 243
,D/qdlights(  973): set_light_backlight: 240
,D/qdlights(  973): set_light_backlight: 236
,D/qdlights(  973): set_light_backlight: 233
,D/qdlights(  973): set_light_backlight: 230
,D/qdlights(  973): set_light_backlight: 226
,D/qdlights(  973): set_light_backlight: 223
,D/qdlights(  973): set_light_backlight: 220
,D/qdlights(  973): set_light_backlight: 216
,D/qdlights(  973): set_light_backlight: 213
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  973): set_light_backlight: 210
,D/qdlights(  973): set_light_backlight: 206
,D/qdlights(  973): set_light_backlight: 203
,D/qdlights(  973): set_light_backlight: 200
,D/qdlights(  973): set_light_backlight: 196
,D/qdlights(  973): set_light_backlight: 193
,D/qdlights(  973): set_light_backlight: 189
,D/qdlights(  973): set_light_backlight: 186
,D/qdlights(  973): set_light_backlight: 183
,D/qdlights(  973): set_light_backlight: 179
,D/qdlights(  973): set_light_backlight: 176
,D/qdlights(  973): set_light_backlight: 173
,D/qdlights(  973): set_light_backlight: 169
,D/qdlights(  973): set_light_backlight: 166
,D/qdlights(  973): set_light_backlight: 163
,D/qdlights(  973): set_light_backlight: 159
,D/qdlights(  973): set_light_backlight: 156
,D/qdlights(  973): set_light_backlight: 153
,D/qdlights(  973): set_light_backlight: 149
,D/qdlights(  973): set_light_backlight: 146
,D/qdlights(  973): set_light_backlight: 143
,D/qdlights(  973): set_light_backlight: 139
,D/qdlights(  973): set_light_backlight: 136
,D/qdlights(  973): set_light_backlight: 133
,D/qdlights(  973): set_light_backlight: 129
,D/qdlights(  973): set_light_backlight: 126
,D/qdlights(  973): set_light_backlight: 123
,D/qdlights(  973): set_light_backlight: 119
,D/qdlights(  973): set_light_backlight: 116
,D/qdlights(  973): set_light_backlight: 113
,D/qdlights(  973): set_light_backlight: 109
,D/qdlights(  973): set_light_backlight: 106
,D/qdlights(  973): set_light_backlight: 103
,D/qdlights(  973): set_light_backlight: 99
,D/qdlights(  973): set_light_backlight: 96
,D/qdlights(  973): set_light_backlight: 93
,D/qdlights(  973): set_light_backlight: 89
,D/qdlights(  973): set_light_backlight: 86
,D/qdlights(  973): set_light_backlight: 83
,D/qdlights(  973): set_light_backlight: 79
,D/qdlights(  973): set_light_backlight: 76
,D/qdlights(  973): set_light_backlight: 73
,D/qdlights(  973): set_light_backlight: 69
,D/qdlights(  973): set_light_backlight: 66
,D/qdlights(  973): set_light_backlight: 63
,D/qdlights(  973): set_light_backlight: 59
,D/qdlights(  973): set_light_backlight: 56
,D/qdlights(  973): set_light_backlight: 53
,D/qdlights(  973): set_light_backlight: 49
,D/qdlights(  973): set_light_backlight: 46
,D/qdlights(  973): set_light_backlight: 43
,D/qdlights(  973): set_light_backlight: 39
,D/qdlights(  973): set_light_backlight: 36
,D/qdlights(  973): set_light_backlight: 33
,D/qdlights(  973): set_light_backlight: 29
,D/qdlights(  973): set_light_backlight: 26
,D/qdlights(  973): set_light_backlight: 23
,D/qdlights(  973): set_light_backlight: 19
,D/qdlights(  973): set_light_backlight: 16
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,D/qdlights(  973): set_light_backlight: 13
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  973): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 155008998485; DSPS: 5177718; Offset : -3012526778
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  973): ALS enabled for SRE
D/PowerManagerServiceEx(  973): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (37818 ms ago)
I/PowerManagerService(  973): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  973): ALS enabled for SRE
D/PowerManagerServiceEx(  973): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (37833 ms ago)
,W/ContextImpl(  973): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  973): Sleeping (uid 1000)...
D/LPWGController(  973): [updateScreenState] screen on = false
,D/LPWGController(  973): disable proximity sensor
D/LPWGController(  973): enable proximity sensor
,I/SensorManager(  973): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@14c7e66] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  973): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  973): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  973): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  973): activate: handle is 48, enable
,V/sensors_hal_Ctx(  973): activate sensors is 1400000000000
D/sensors_hal_Thresh(  973): enable: handle=48
I/sensors_hal_SAM(  973): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  973): waitForResponse: timeout=1000
V/sensors_hal_SAM(  973): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  973): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  973): enable: Received response: 0
D/PowerManagerServiceEx(  973): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (37898 ms ago)
I/Adreno-EGL(  973): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  973): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  973): Build Date: 03/02/15 Mon
I/Adreno-EGL(  973): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  973): Remote Branch: 
I/Adreno-EGL(  973): Local Patches: 
I/Adreno-EGL(  973): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1004 us)
,I/Sensors (  425): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  973): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  973): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  973): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  973): processInd: handle 48, count=1
V/sensors_hal_Thresh(  973): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  973): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  973): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  973): poll: count: 256
I/sensors_hal_Ctx(  973): poll: released wakelock sensor_ind
D/sensors_hal_Util(  973): waitForResponse: timeout=0
D/LPWGController(  973): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  973): current mode = 1  value = 1 1
I/LPWGController(  973): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  973): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/qdlights(  973): set_light_backlight: 0
,I/SensorManager(  973): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  973): activate: handle is 46, disable
V/sensors_hal_Ctx(  973): activate sensors is 1000000000000
D/sensors_hal_LP2(  973): enable: handle=46
D/sensors_hal_LP2(  973): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  973): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  973): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  973): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  973): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,V/ActivityManager(  973): Display changed displayId=0
,D/DSDPConnection( 1751): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  973): Excessive delay in setPowerMode(): 208ms
I/QCOM PowerHAL(  973): Got set_interactive hint
,D/KeyguardViewMediator( 1371): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1371): notifyScreenOffLocked
D/KeyguardViewMediator( 1371): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1371): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1371): unregisterProximitySensor
,D/WifiServerServiceExt(  973): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1371): onScreenTurnedOff why = 3
,V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=on, calling pid 973
,I/WifiServerServiceExt(  973): set CMD_KT_SCAN_INTERVAL
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: enter: screen_state=on
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  284): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
,D/GpsLocationProvider(  973): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1794): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1794): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/LEDService( 1794): stopPatternFlashing()
D/Cliptray Service( 1794): lockStatus = 0
D/qdlights( 1794): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
I/LEDService( 1794): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1794): set_light_notifications: 0,0,0,0,3
I/LEDService( 1794): updateLightsLocked : turn off led
D/qdlights( 1794): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1794): RESTART MSG
D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
,D/Ulp_jni (  973): JNI:system_update. Event-0
D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1785): isRequireNfcCRouting() return true
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
D/SplitWindow(  973): check instance of lgWin Window{36ba6dfd u0 SearchPanel}
,D/InputDispatcher(  973): Window went away: Window{2b3f7599 u0 SearchPanel}
,I/[SystemUI]Clock( 1371): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1371): time changed, timezoneChanged : false
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2722): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 20:18:51
,D/WeatherService( 2722): 2 : ACTION screen on
D/WeatherService( 2722): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2722): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2722): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 20:18:51
,W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): ACTION_SCREEN_ON
D/AppCleanupService( 4081): android.intent.action.SCREEN_ON
,V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=off, calling pid 973
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: enter: screen_state=off
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
,D/WifiController(  973): CMD_SCREEN_OFF 
D/WifiController(  973): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  973): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1794): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1794): stopPatternFlashing()
D/qdlights( 1794): set_light_notifications: 0,0,0,0,3
I/LEDService( 1794): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1794): set_light_notifications: 0,0,0,0,3
I/LEDService( 1794): updateLightsLocked : turn on led
D/VolumeVibrator( 1794): clear
E/LEDService( 1794): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
I/Cliptray Service( 1794): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
E/LEDService( 1794): Can't handle this request of patternId:0
D/LEDHandler( 1794): RESTART MSG
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2722): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 20:18:52
D/WeatherService( 2722): 2 : ACTION screen off
D/WeatherService( 2722): 2 : TimeTick Receiver Unregister
D/WeatherService( 2722): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 20:18:52
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  973): ACTION_SCREEN_OFF
,D/AppCleanupService( 4081): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4081): AppUsageStatsSaveTask
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
,I/Sensors (  425): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1371): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{29921af2 type 2 when 163791 com.android.systemui} when 163791
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1751): getCallState : 0
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1371): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1371): doKeyguard: not showing because lockscreen is off
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 175009871758; DSPS: 5833107; Offset : -3012538255
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  973): acquireWakeLockInternal: lock=9921859, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=973
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{3622b7c0 type 2 when 183847 android} when 183847
D/PowerManagerServiceEx(  973): releaseWakeLockInternal: lock=9921859 [*alarm*], flags=0x0
,D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{3f44ecf9 type 2 when 189372 com.google.android.gms} when 189372
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 195010914668; DSPS: 6488501; Offset : -3012533359
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 215011580963; DSPS: 7143883; Offset : -3012538112
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  486): init target 500000
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 235012249497; DSPS: 7799265; Offset : -3012541252
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  486): init target 500000
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 255012993239; DSPS: 8454649; Offset : -3012529644
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 275013742710; DSPS: 9110033; Offset : -3012512283
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 295014419161; DSPS: 9765416; Offset : -3012538023
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  973): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 315015093268; DSPS: 10420798; Offset : -3012535564
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 335015825395; DSPS: 11076182; Offset : -3012535520
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/LocationManagerService(  973): remove 20b63e49
D/LocationManagerService(  973): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  973): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  973): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  973): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  973): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  973): acquireWakeLockInternal: lock=9921859, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=973
,D/PowerManagerServiceEx(  973): releaseWakeLockInternal: lock=9921859 [*alarm*], flags=0x0
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 355016474607; DSPS: 11731563; Offset : -3012527020
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 375017172724; DSPS: 12386946; Offset : -3012531095
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 395017816883; DSPS: 13042327; Offset : -3012527727
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 415018534323; DSPS: 13697710; Offset : -3012512164
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 435019285982; DSPS: 14353095; Offset : -3012523419
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 455019937329; DSPS: 15008477; Offset : -3012543537
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 475020885551; DSPS: 15663868; Offset : -3012541412
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 495021639033; DSPS: 16319252; Offset : -3012520195
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 515022286213; DSPS: 16974634; Offset : -3012544845
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 535023031205; DSPS: 17630018; Offset : -3012532041
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 555023747239; DSPS: 18285401; Offset : -3012517807
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 575024404106; DSPS: 18940783; Offset : -3012532326
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 595025132901; DSPS: 19596167; Offset : -3012535719
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 615025891331; DSPS: 20251552; Offset : -3012540488
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 635026540177; DSPS: 20906933; Offset : -3012532876
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 655027267825; DSPS: 21562317; Offset : -3012538562
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 675028015110; DSPS: 22217701; Offset : -3012522371
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 695028651404; DSPS: 22873082; Offset : -3012527102
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 715029395979; DSPS: 23528466; Offset : -3012514740
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  973): battery changed pluggedType: 2
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 735030454671; DSPS: 24183861; Offset : -3012524320
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 755031106069; DSPS: 24839242; Offset : -3012513661
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 775031827104; DSPS: 25494626; Offset : -3012524761
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 795032562252; DSPS: 26150010; Offset : -3012522687
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 815033205577; DSPS: 26805391; Offset : -3012520047
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 835033966612; DSPS: 27460776; Offset : -3012521744
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 855034713322; DSPS: 28116161; Offset : -3012537948
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 875035422012; DSPS: 28771544; Offset : -3012531084
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 895036114036; DSPS: 29426927; Offset : -3012541147
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 915036872674; DSPS: 30082311; Offset : -3012514827
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 935037529073; DSPS: 30737693; Offset : -3012530152
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  973): acquireWakeLockInternal: lock=9921859, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=973
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{3222f43e type 2 when 952359 com.android.bluetooth} when 952359
W/bt-smp  ( 1967): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1967): Plain text(LSB ~ MSB) = a7 03 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1967): Encrypted text(LSB ~ MSB) = 99 94 59 17 32 04 56 95 a8 ee 39 bb 93 fc 32 29 
W/bt-btm  ( 1967): Stopping oneshot timer
I/ActivityManager(  973): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8318 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 8318): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8318): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@2a25ebc5
I/ActivityManager(  973): Killing 7890:com.google.android.talk/u0a61 (adj 15): empty #11
D/PowerManagerServiceEx(  973): releaseWakeLockInternal: lock=9921859 [*alarm*], flags=0x0
W/libprocessgroup(  973): failed to open /acct/uid_10061/pid_7890/cgroup.procs: No such file or directory
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 955038255576; DSPS: 31393077; Offset : -3012536097
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  973): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 975038932912; DSPS: 32048459; Offset : -3012529549
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,V/AlarmManager(  973): ELAPSED_WAKEUP set : Alarm{2541129f type 2 when 992626 com.google.android.gms} when 992626
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 995039654102; DSPS: 32703843; Offset : -3012540677
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1015040684408; DSPS: 33359236; Offset : -3012517477
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1035041358566; DSPS: 34014618; Offset : -3012515435
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1055042012622; DSPS: 34670000; Offset : -3012532531
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1075042803707; DSPS: 35325386; Offset : -3012534408
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1095043542294; DSPS: 35980770; Offset : -3012528764
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1115044202130; DSPS: 36636152; Offset : -3012540289
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1135044903424; DSPS: 37291535; Offset : -3012540821
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1155045577635; DSPS: 37946917; Offset : -3012537685
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1175046309607; DSPS: 38602301; Offset : -3012538004
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1195047039755; DSPS: 39257685; Offset : -3012540538
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1794): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1794): Battery Level Remaining: 100%
D/LEDHandler( 1794): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1967): Disconnected process message: 10, size: 0
W/Settings(  973): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  973): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  973): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1215047741831; DSPS: 39913068; Offset : -3012540236
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  973): User[0] Flushing usage stats to disk
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1235048504479; DSPS: 40568453; Offset : -3012542194
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1255049230981; DSPS: 41223836; Offset : -3012516217
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  486): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1794): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1275049905714; DSPS: 41879218; Offset : -3012512766
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
D/AndroidRuntime( 8391): 
D/AndroidRuntime( 8391): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8391): CheckJNI is OFF
D/sensors_hal_Time(  973): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  973): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  973): tsOffsetIs: Apps: 1295052276488; DSPS: 42534656; Offset : -3012524030
D/AndroidRuntime( 8391): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  973): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  973): Killing 5642:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  973): WIN DEATH: Window{82ae3c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  973): Skipping PackageSetting{2a3b7b25 com.example.hello/10317} due to missing metadata
D/InputDispatcher(  973): Focus left window: Window{82ae3c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  973): Window went away: Window{82ae3c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  973):   Force finishing activity ActivityRecord{1b0c66a1 u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  973): Display changed displayId=0
D/DSDPConnection( 1751): Display #0 changed.
W/ActivityManager(  973): Spurious death for ProcessRecord{365b8fec 5642:com.test.thalitest/u0a316}, curProc for 5642: null
I/ActivityManager(  973): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  973):   Force finishing activity ActivityRecord{1b0c66a1 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  973): Duplicate finish request for ActivityRecord{1b0c66a1 u0 com.test.thalitest/.MainActivity t222 f}
I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
I/art     ( 1932): Explicit concurrent mark sweep GC freed 7449(425KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/21MB, paused 1.557ms total 72.699ms
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  973): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
W/System.err( 3611): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3611): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3611): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3611): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3611): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3611): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3611): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3611): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3611): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3611): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3611): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3611): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 5601): Explicit concurrent mark sweep GC freed 7388(412KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 13MB/18MB, paused 973us total 138.398ms
W/SQLiteConnectionPool( 5601): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/ActivityManager(  973): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8424 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
I/Activity( 1877): Activity.onPostResume() called 
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
W/ResourcesManager( 1371): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1371): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/art     (  973): Explicit concurrent mark sweep GC freed 71737(4MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 23MB/35MB, paused 3.512ms total 234.005ms
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 1371): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
I/art     (  973): WaitForGcToComplete blocked for 203.283ms for cause Explicit
W/ResourcesManager( 1371): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1371): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1371): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/SystemUI[Framework](  973): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  973): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  973): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  973): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  973): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33b449b0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  973): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  973): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  973): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  973): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  973): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  973): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@33b449b0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  973): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
D/InputDispatcher(  973): Focus entered window: Window{161b4714 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1371): handleShortcutListChanged...
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
D/administrator(  973): Handling package changes for user 0
W/InputMethodManagerService(  973): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/InputMethodManagerService(  973): Got RemoteException sending setActive(false) notification to pid 5642 uid 10316
W/ResourcesManager( 8424): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8424): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8424): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): handleShortcutListChanged...
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  973): Timeline: Activity_windows_visible id: ActivityRecord{350b3192 u0 com.lge.launcher2/.Launcher t221} time:1296082
W/IInputConnectionWrapper( 1877): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1624): Unable to connect to the editor to retrieve text... will retry later
I/LGEmail ( 8424): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
D/LGEmail ( 8424): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/NotificationService(  973): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  973): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  973): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
D/TaskPersister(  973): removeObsoleteFile: deleting file=222_task.xml
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1877): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/art     (  973): Explicit concurrent mark sweep GC freed 9487(561KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.642ms total 365.201ms
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/PackageChangeReceiver( 8424): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/AndroidRuntime( 8391): Shutting down VM
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  973): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8451 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  973): Killing 7948:com.android.gallery3d/u0a23 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  973): failed to open /acct/uid_10023/pid_7948/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppUp4:AppBoxCP( 8451): onCreate
W/AppUp4:DB( 8451):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 8451):  setFingerPrint start
I/AppUp4:DB( 8451):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8451):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8451):  SDK version = 0
I/AppUp4:DB( 8451):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8451): AppBoxApplication onCreate()
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
D/AppUp4:PreloadHelper( 8451): added Exclude : com.test.thalitest
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  973): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8470 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  973): Killing 7973:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  973): failed to open /acct/uid_10018/pid_7973/cgroup.procs: No such file or directory
I/Timeline( 1877): Timeline: Activity_idle id: android.os.BinderProxy@90d0071 time:1296751
E/SharedPreferencesImpl( 1877): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak
I/art     ( 1877): Explicit concurrent mark sweep GC freed 28064(1522KB) AllocSpace objects, 18(2MB) LOS objects, 40% free, 15MB/25MB, paused 961us total 59.693ms

```
