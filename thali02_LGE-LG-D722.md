#### Test 57972094912017a_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,D/Finsky  ( 5443): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 5443): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5443): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5443): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@2dd28063 on behalf of 5443
I/NotificationManager( 5443): com.android.vending: cancel(1003285959) by com.android.vending
D/Ads     ( 5443): Skipping gmscore version check
D/Finsky  ( 5443): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5443): [1] Libraries$2.run: Finished loading 1 libraries.
--------- beginning of system
I/ActivityManager(  865): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5494 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/ActivityManager(  865): Killing 5213:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10021/pid_5213/cgroup.procs: No such file or directory
D/Finsky  ( 5443): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 5443): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5443): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  865): Killing 5239:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/ResourcesManager( 5494): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5494): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  865): failed to open /acct/uid_10009/pid_5239/cgroup.procs: No such file or directory
I/MultiDex( 5494): VM with version 2.1.0 has multidex support
I/MultiDex( 5494): install
I/MultiDex( 5494): VM has multidex support, MultiDex support library is disabled.
D/AndroidRuntime( 5490): 
D/AndroidRuntime( 5490): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5490): CheckJNI is OFF
V/JNIHelp ( 5494): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 5494): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5494): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@270c5df2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5494): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5494): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5494): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5494): Reading stored module config
D/PackageBroadcastService( 5494): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 5494): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5494): Loading module APK com.google.android.play.games
D/AndroidRuntime( 5490): Calling main entry com.android.commands.am.Am
I/ActivityManager(  865): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  865): setTaskToReturnTo : TaskRecord{118d81e5 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  865): setTaskToReturnTo : TaskRecord{118d81e5 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/NativeLibraryUtils( 5494): Install completed successfully. count=14 extracted=0
D/WindowStateEx(  865): AppWindowTokenEx init.. 
D/ContextHelper(  865): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1881): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  865): Focus left window: Window{13f1480a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5490): Shutting down VM
D/SplitWindow(  865): check instance of lgWin Window{bb34747 u0 Starting com.test.thalitest}
I/art     ( 5494): CheckpointMarkThreadRoots callback created = 0xb002d4a0
I/ActivityManager(  865): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5537 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     ( 5494): CheckpointMarkThreadRoots callback created = 0xb002d480
I/[LGHome]EVENT( 1881): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/WindowStateAnimator(  865): Starting window displayed
I/HotwordDetector( 1947): Closing mic
I/SystemUI[Framework](  865): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  865): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  865): setLGSystemUiVisibility(0x0)
I/[LGHome]EVENT( 1881): [Launcher.java:5214:onStop()]onStop
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
D/StatusBarManagerServiceEx(  865): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  865): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d329440,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  865): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
I/MicrophoneInputStream( 1947): mic_close com.google.android.apps.gsa.speech.audio.u@1eca4cb2
V/AudioRecord( 1947): stop()
D/AudioRecord( 1947): AudioRecord->stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
D/BarTransitions( 1375): draw background and invalidate : color = f000000
D/BarTransitions( 1375): draw background and invalidate : color = 100f0f0f
V/AudioFlinger(  285): Record stopped OK
V/AudioPolicyManager(  285): stopInput() input 17
V/AudioPolicyService(  285): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  285): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  285): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  285): ThreadBase::setParameters() routing=0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3a65000
,D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  285): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  285): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  285): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  285): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  285): disable_audio_route: exit
E/audio_hw_primary(  285): disable_snd_device: enter 144
D/hardware_info(  285): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  285): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  285): stop_input_stream: exit: status(0)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyManager(  285): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  285): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  285): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  285): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioPolicyService(  285): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  285): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  285): setParameters(): io 17, keyvalue hotword_active=0, calling pid 285
V/AudioFlinger(  285): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  285): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioFlinger(  285): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  285): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  285): in_set_parameters: exit: status(0)
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3a65000
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioRecord( 1947): stop()
V/AudioRecord( 1947): stop()
V/AudioRecord( 1947): stop()
V/AudioFlinger(  285): releasing 16 from 1947 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
V/AudioPolicyManager(  285): releaseInput() 17
V/AudioPolicyManager(  285): closeInput(17)
V/AudioFlinger(  285): closeInput() 17
V/AudioSystem(  285): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): ThreadBase::exit
V/AudioFlinger(  285): RecordThread: loop starting
V/AudioSystem( 1995): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): RecordThread 0xb3a65000 exiting
D/audio_hw_primary(  285): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioSystem( 1375): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  285): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  285): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  285): releaseInput() exit
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioPolicyService(  285): AudioCommandThread() processing update audio port list
V/AudioSystem(  865): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3177): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1947): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  285): removeClient_l() pid 1947, calling pid 285
V/AudioSystem( 1751): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioSystem( 2734): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1947): Hotword detection finished
I/HotwordRecognitionRnr( 1947): Stopping hotword detection.
D/ChimeraCfgMgr( 5494): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5494): Module APK com.google.android.play.games already loaded
D/ContextHelper( 5537): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/ChimeraCfgMgr( 5494): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 5494): Submit a task: k
D/ChimeraCfgMgr( 5494): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5494): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 5494): Processing package: com.test.thalitest
D/GassUtils( 5494): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5494): Found info for package com.test.thalitest in db.
I/PeopleDatabaseHelper( 5494): cleanUpNonGplusAccounts done.
I/WebViewFactory( 5537): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/WearableService( 1736): callingUid 10006, callindPid: 1736
I/Icing   ( 5494): Storage manager: low false usage 1.75MB avail 2.37GB capacity 4.06GB
D/LocationInitializer( 5494): Restart initialization of location
E/MDM     ( 1736): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/BaseAppContext( 5494): Using Auth Proxy for data requests.
I/LibraryLoader( 5537): Time to load native libraries: 5 ms (timestamps 3423-3428)
I/LibraryLoader( 5537): Expected native library version number "",actual native library version number ""
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1736): com.google.android.gms: cancel(0) by com.google.android.gms
V/WebViewChromiumFactoryProvider( 5537): Binding Chromium to main looper Looper (main, tid 1) {37d79eda}
I/LibraryLoader( 5537): Expected native library version number "",actual native library version number ""
I/chromium( 5537): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5537): Initializing chromium process, singleProcess=true
W/art     ( 5537): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5537): ApplicationContext is null in ApplicationStatus
W/chromium( 5537): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/art     ( 5494): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5494): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/libEGL  ( 5537): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5537): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/ActivityManager(  865): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5587 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Adreno-EGL( 5537): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5537): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5537): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5537): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5537): Remote Branch: 
I/Adreno-EGL( 5537): Local Patches: 
I/Adreno-EGL( 5537): Reconstruct Branch: 
I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 23.289ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.388ms
E/BaseAppContext( 5494): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 5494): Using Auth Proxy for data requests.
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 23.302ms
I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
W/BaseAppContext( 5494): Using Auth Proxy for data requests.
V/AudioPolicyService(  285): registerClient() client 0xb4027780, uid 10316
,D/BluetoothManagerService(  865): Message: 20
D/BluetoothManagerService(  865): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27c5197d:true
,W/BaseAppContext( 5494): Using Auth Proxy for data requests.
D/BluetoothAdapterService(681627302)( 1995): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ef2022c
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/BaseAppContext( 5494): Using Auth Proxy for data requests.
W/BaseAppContext( 5494): Using Auth Proxy for data requests.
W/BaseAppContext( 5494): Using Auth Proxy for data requests.
,W/IcingInternalCorpora( 5494): getNumBytesRead when not calculated.
,W/GCoreFlp( 1736): No location to return for getLastLocation()
,W/FusedLocationProvider( 1736): location=null
W/art     ( 5537): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5537): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5537): CordovaWebView is running on device made by: LGE
,W/art     ( 5537): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5537): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Activity( 5537): Activity.onPostResume() called 
,D/OpenGLRenderer( 5537): Render dirty regions requested: true
I/OpenGLRenderer( 5537): Initialized EGL, version 1.4
D/OpenGLRenderer( 5537): Enabling debug mode 0
,D/Atlas   ( 5537): Validating map...
,D/SplitWindow(  865): check instance of lgWin Window{4b45bed u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5537): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  865): Focus entered window: Window{4b45bed u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/Gmail   ( 5587): getAccountsCursor
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/InputMethodManagerService(  865): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  865): Displayed com.test.thalitest/.MainActivity: +1s518ms
I/Timeline(  865): Timeline: Activity_windows_visible id: ActivityRecord{32f244ba u0 com.test.thalitest/.MainActivity t222} time:84355
W/GAV2    ( 5587): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Timeline( 5537): Timeline: Activity_idle id: android.os.BinderProxy@1f9d7b71 time:84394
,I/Icing   ( 5494): updateResources: need to parse f{com.google.android.gms}
,W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5587): Error finding the version of the Email provider.....
E/Gmail   ( 5587): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5587): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5587): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5587): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5587): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5587): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5587): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5587): We do not support migrating this version of the Email provider.
,W/BindingManager( 5537): Cannot call determinedVisibility() - never saw a connection for the pid: 5537
I/Gmail   ( 5587): getAccountsCursor
,W/ActivityManager(  865): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  865): Killing 5262:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/Gmail   ( 5587): Observing account changes for notifications
,D/ChimeraCfgMgr( 5494): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5494): Module APK com.google.android.play.games already loaded
,W/libprocessgroup(  865): failed to open /acct/uid_10011/pid_5262/cgroup.procs: No such file or directory
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1736): No location to return for getLastLocation()
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/FusedLocationProvider( 1736): location=null
,D/JsMessageQueue( 5537): Set native->JS mode to OnlineEventsBridgeMode
,V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@15510460 on behalf of 5494
W/InstanceID/Rpc( 5494): Found 10006
,I/art     ( 5418): Explicit concurrent mark sweep GC freed 7914(397KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.280ms total 79.494ms
,I/ActivityManager(  865): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5675 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Gmail   ( 5587): notifyAccountChanged
,I/Gmail   ( 5587): getAccountsCursor
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5587): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5587): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@5144d19 on behalf of 5494
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 5494): Internal init done: storage state 0
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@1378a1de on behalf of 5494
I/Gmail   ( 5587): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5587): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Icing   ( 5494): Post-init done
I/NotificationManager( 5494): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/PhoneMonitor( 5675): Register our PhoneStateListener
,I/art     ( 5494): Background sticky concurrent mark sweep GC freed 10028(734KB) AllocSpace objects, 9(144KB) LOS objects, 5% free, 13MB/14MB, paused 10.344ms total 101.606ms
,I/ActivityManager(  865): Killing 5279:com.android.gallery3d/u0a23 (adj 15): empty #11
,D/PhoneMonitor( 5675): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 5675): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5675): [parse] Load xml
,V/TelephonyAutoProfiling( 5675): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5675): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
W/libprocessgroup(  865): failed to open /acct/uid_10023/pid_5279/cgroup.procs: No such file or directory
,D/PhoneMonitor( 5675): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 5494): Checkin interval check for package: unspecified last checkin: 1454420771924 min interval config: 0 actual interval: 7252
,I/CheckinService( 5494): Disabling old GoogleServicesFramework version
,I/Gmail   ( 5587): getAccountsCursor
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/jxcore_app_log( 5537): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426151936
I/ActivityManager(  865): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5705 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/lowmemorykiller(  243): Error opening /proc/5119/oom_score_adj; errno=2
,I/chromium( 5537): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/InitAlarmsService( 3802): Clearing and rescheduling alarms.
,I/ActivityManager(  865): Process com.lge.bnr (pid 5119) has died
,W/ResourcesManager( 5705): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  865): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5722 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 5537): CheckpointMarkThreadRoots callback created = 0xb00fcd90
,I/CheckinService( 5494): Checking schedule, now: 1454420779478 next: 1454420801886
I/CheckinService( 5494): active receiver: disabled
,I/art     ( 5537): CheckpointMarkThreadRoots callback created = 0xb00fcd60
,W/ResourcesManager( 5722): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5722): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@151d90c9
,D/CalendarProvider2( 5722): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5722): Created com.android.providers.calendar.CalendarAlarmManager@37d79eda(com.android.providers.calendar.CalendarProvider2@151d90c9)
D/CalendarProvider2( 5722): Scheduling check of next Alarm
,D/CalendarProvider2( 5722): SCHEDULE_ALARM_REMOVE
,I/art     (  865): Explicit concurrent mark sweep GC freed 35571(1684KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.283ms total 202.336ms
I/Babel_SMS( 5705): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5705): MmsConfig.loadMmsSettings
I/ActivityManager(  865): Process com.android.contacts (pid 5298) has died
,I/Babel_SMS( 5705): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5705): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5705): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5705): MmsConfig.loadFromResources
E/Babel_SMS( 5705): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5705): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5705): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5705): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5705): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5705): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5705): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5705): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5705): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5705): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5705): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5705): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5705): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5705): found sensor: LGE Orientation Sensor, handle=49
,D/SensorManager( 5705): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5705): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5705): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5705): found sensor: Motion Accel, handle=46
W/Settings( 5705): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5705): startup - clean
I/Babel   ( 5705): deleted: false for 0
,I/art     ( 5705): CheckpointMarkThreadRoots callback created = 0xb002d520
,I/art     ( 5705): CheckpointMarkThreadRoots callback created = 0xb002d500
,I/Icing   ( 5494): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,W/AudioCapabilities( 5705): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5705): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5705): Unsupported mime audio/g726
W/AudioCapabilities( 5705): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5705): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5705): Unsupported mime video/mjpg
W/VideoCapabilities( 5705): Unsupported mime video/theora
,D/Icing   ( 5494): Loaded CLD2 Version V2.0 - 20141016
,W/AudioCapabilities( 5705): Unsupported mime audio/evrc
W/AudioCapabilities( 5705): Unsupported mime audio/qcelp
W/VideoCapabilities( 5705): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5705): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5705): Unsupported mime audio/qcelp
W/AudioCapabilities( 5705): Unsupported mime audio/evrc
,W/VideoCapabilities( 5705): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5705): Unsupported profile 4 for video/mp4v-es
,I/Icing   ( 5494): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/VideoCapabilities( 5705): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5705): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5705): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5705): Unrecognized profile 2130706433 for video/avc
W/art     ( 5705): Suspending all threads took: 6.450ms
,I/vclib   ( 5705): onServiceConnected
W/Babel   ( 5705): Attempted to change video mute state without an active call.
,W/ResourcesManager( 5705): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5705): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5705): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  865): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5755 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CalendarProvider2( 5722): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5722): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/AudioManager( 5092): getMode name:com.lge.qremote
,I/AudioManager( 5092): getMode name:com.lge.qremote
,I/AudioManager( 5092): getMode name:com.lge.qremote
,W/System  ( 5705): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5705): Installed default security provider GmsCore_OpenSSL
D/UEI.SmartControl( 5755): Quickset Services start...
I/UEI.SmartControl( 5755): Manufacture = LGE
,D/UEI.SmartControl( 5755): File observer start...
E/UEI.SmartControl( 5755): IR Port is disabled: false
D/UEI.SmartControl( 5755): Starting file observer...
D/UEI.SmartControl( 5755): Extracting JNI libs...
D/UEI.SmartControl( 5755): --- this system supports 32-bit or 64-bit only
I/NotificationManager( 5705): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AudioManager( 5092): getMode name:com.lge.qremote
I/AudioManager( 5092): getMode name:com.lge.qremote
,I/ActivityManager(  865): Process com.google.android.apps.docs (pid 5351) has died
,E/MDM     ( 1736): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5494): Restart initialization of location
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1736): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5092): getMode name:com.lge.qremote
W/GCoreFlp( 1736): No location to return for getLastLocation()
W/FusedLocationProvider( 1736): location=null
,I/NotificationManager( 5705): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  865): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5782 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 5782): onCreate
,W/AppUp4:DB( 5782):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5782):  setFingerPrint start
,I/AppUp4:DB( 5782):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5782):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5782):  SDK version = 0
I/AppUp4:DB( 5782):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5782): AppBoxApplication onCreate()
D/UEI.SmartControl( 5755): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5755): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5755): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/AppUp4:CustModeStarterReceiver( 5782): onReceive
I/AppUp4:CustModeStarterReceiver( 5782): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5782): Context : android.app.ReceiverRestrictedContext@3d6421fc
D/AppUp4:CustFacade( 5782): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5782): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5782): begin check event
I/AppUp4:CustModeStarterReceiver( 5782): Event For Nothing, skip.
I/UEI.SmartControl( 5755): --- Selecting new region: 2
I/UEI.SmartControl( 5755): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5755): Platform has CIR...
D/UEI.SmartControl( 5755): NO CIR support, need to check package...
I/UEI.SmartControl( 5755): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5755): QS Service created
,W/jxcore-log( 5537): Initializing JXcore engine
,W/jxcore-log( 5537): JXcore engine is ready
I/ActivityManager(  865): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5801 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
E/UEI.SmartControl( 5755): QS start get config
,W/ResourcesManager( 5801): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5801): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5801): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5755): Loading JNI Libs...
,D/UEI.SmartControl( 5755):  configuring local db...
W/Thread-676( 5704): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7292]" dev="sockfs" ino=7292 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-676( 5704): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-676( 5704): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9254]" dev="sockfs" ino=9254 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-676( 5704): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-676( 5704): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-676( 5704): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26730]" dev="sockfs" ino=26730 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5537): Starting JXcore engine
,I/AppConfig( 5801): Total System Memory = 906309632
,I/GalleryUtils( 5801): Application Heap = 96 MB
I/AppConfig( 5801): App Tier : NOT_DEF
D/SystemHelper( 5801): region [EU], country [EU], operator [OPEN], sub-operator []
,W/jxcore-log( 5537): Platform android
W/jxcore-log( 5537): 
W/jxcore-log( 5537): Process ARCH arm
W/jxcore-log( 5537): 
,I/ActivityManager(  865): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5820 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/UEI.SmartControl( 5755):  ---- Has DB8: true
I/ActivityManager(  865): Killing 3802:com.android.calendar/u0a13 (adj 15): empty #11
D/UEI.SmartControl( 5755): QS start statue = true Error code = 0
D/UEI.SmartControl( 5755): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5755): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5755): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5755): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5755): IrrcClient ++ 
D/irrcClient( 5755): getIrrcService ++ 
D/irrcClient( 5755): getIrrcService -- 
D/irrcClient( 5755): IrrcClient -- 
W/irrc_jni( 5755): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 5755): Services init done
I/UEI.SmartControl( 5755): Device manager: loading config....
D/UEI.SmartControl( 5755): Config is loaded...
,D/UEI.SmartControl( 5755):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5755): Notify AllClients services are ready: 0
,W/libprocessgroup(  865): failed to open /acct/uid_10013/pid_3802/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 5755): QS Service init finished
D/UEI.SmartControl( 5755): QS Service version name: 0.1.73
D/UEI.SmartControl( 5755): QS Service version code: 1073
D/UEI.SmartControl( 5755): Service requested: Control
,D/UEI.SmartControl( 5755): Internal service binding...
D/UEI.SmartControl( 5755): -----IControl: 11
D/UEI.SmartControl( 5755): Caller: com.lge.qremote
D/UEI.SmartControl( 5755): ------------ IControl registerCallback...
,I/UEI.SmartControl( 5755): Registering callback...
D/UEI.SmartControl( 5755): -----IControl: 19
D/UEI.SmartControl( 5755): Caller: com.lge.qremote
I/UEI.SmartControl( 5755): Registering Services Ready callback...
I/UEI.SmartControl( 5755): Notify client services are ready...
D/UEI.SmartControl( 5755): -----IControl: 8
D/UEI.SmartControl( 5755): Caller: com.lge.qremote
W/ResourcesManager( 5820): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5820): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5820): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/ActivityManager(  865): Killing 5334:com.lge.eula/1000 (adj 15): empty #11
,W/ResourcesManager( 5820): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5820): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  865): Killing 5317:com.lge.lockscreensettings/u0a69 (adj 15): empty #12
,W/libprocessgroup(  865): failed to open /acct/uid_1000/pid_5334/cgroup.procs: No such file or directory
,W/libprocessgroup(  865): failed to open /acct/uid_10069/pid_5317/cgroup.procs: No such file or directory
V/AlarmManager(  865): RTC_WAKEUP set : Alarm{a8ca590 type 0 when 1454420781870 com.google.android.googlequicksearchbox} when 1454420781870
I/SystemConfig( 5820): BUILD Country: EU
,I/SystemConfig( 5820): BUILD Operator: OPEN
I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/QCNEJ   ( 1843): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  865): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator(  865): Handling package changes for user 0
,I/SystemConfig( 5820): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 5820): existFile = false
I/SystemConfig( 5820): canReadFile = false
I/SystemConfig( 5820): systemFeature RCS result false
D/SystemConfig( 5820): refreshRcsSupport() :false
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  865): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5848 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  865): Killing 5382:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/jxcore-log( 5537): JXcore Cordova bridge is ready!
I/jxcore-log( 5537): 
W/jxcore-log( 5537): JXcore engine is started
I/NotificationService(  865): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  865): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  865): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/libprocessgroup(  865): failed to open /acct/uid_10086/pid_5382/cgroup.procs: No such file or directory
,I/BackupManagerService(  865): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  865): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  865): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@d3a8405
,W/ResourcesManager(  865): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/LockScreenSettings( 5848): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5848): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 5848): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5848): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5848): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5848): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
W/ResourceType(  865): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  865): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5865 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  865): Killing 5443:com.android.vending/u0a36 (adj 15): empty #11
I/jxcore-log( 5537): Toggling radios to true
I/jxcore-log( 5537): 
,D/BluetoothAdapter( 5537): enable(): BT is already enabled..!
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
W/libprocessgroup(  865): failed to open /acct/uid_10036/pid_5443/cgroup.procs: No such file or directory
D/WifiServiceImplEx(  865): setWifiEnabled: true pid=5537, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/WifiService(  865): setWifiEnabled: true pid=5537, uid=10316
D/WifiServiceImplEx(  865): disconnect pid=5537, uid=10316, packageName=com.test.thalitest
,I/GCoreNlp( 1736): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/WifiServiceImplEx(  865): reconnect pid=5537, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5537): Radios toggled
I/jxcore-log( 5537): 
I/jxcore-log( 5537): My device name is: LGE-LG-D722
I/jxcore-log( 5537): 
,D/LCardEmulationManager( 1790): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1790): getDefaultRoute
I/wpa_supplicant( 2825): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,E/WifiStateMachine(  865): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2825): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
W/ResourcesManager( 5865): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/WifiConfigStore(  865): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1807): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
D/LGWifiP2pService(  865): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  865): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  865): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/LocationProviderProxy(  865): applying state to connected service
D/CommandListener(  281): Clearing all IP addresses on wlan0
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1736): Read error: ssl=0xaaee0000: I/O error during system call, Connection timed out
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  865): hidePasspointNotification off =false
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine(  865): Start Disconnecting Watchdog 1
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  865): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  865): ignoring duplicate network state non-change
D/WifiHS20(  865): hidePasspointNotification off =false
I/wpa_supplicant( 2825): wlan0: CTRL-EVENT-SCAN-STARTED 
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:22.593 DNS addrs= 0.0.0.0, 0.0.0.0, 
V/NativeCrypto( 1736): SSL shutdown failed: ssl=0xaaee0000: I/O error during system call, Broken pipe
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:22.594 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  865): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/LGWifiP2pService(  865): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  865): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  281): Clearing all IP addresses on wlan0
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:22.601 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  865): hidePasspointNotification off =false
,W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiServiceExtension( 1807): isInternetCheckAvailable return false
D/WifiHS20(  865): hidePasspointNotification off =false
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:22.619 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  865): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:22.621 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiNetworkAgent(  865): NetworkAgent: NetworkAgent channel lost
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  865): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  865): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  865): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  865): setSupplicantStateSCANNING
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): ValidatedState{ when=-3ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): DefaultState{ when=-5ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): Forcing reevaluation
D/WifiServiceExtension( 1807): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
,I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  865): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  865): disableDataServiceNotify
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/DSQN    (  865): stop dsqn bin
,D/ConnectivityService(  865): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  865):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  865):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  865): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): Disconnected - quitting
D/Nat464Xlat(  865): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker(  865): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::a239:f7ff:fe70:1280/64,192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
,D/CSLegacyTypeTracker(  865): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  865): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  865): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  865): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  865): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  865): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1843): |CORE| No family connected
D/ConnectivityService(  865): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  865): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  865): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  865): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  865):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/Tethering(  865): MasterInitialState.processMessage what=3
V/NetworkPolicy(  865): [LG_RESTRICTED] !!!isConnected  type  :1
D/TelephonyNetworkFactory-1( 1751): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
W/QCNEJ   ( 1843): |CORE| No family connected
I/QCNEJ   ( 1843): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  865): Removing idletimer
I/QCNEJ   ( 1843): |CORE| sendDefaultNwMsg: default = -1
W/Settings(  865): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
,D/DhcpStateMachine(  865): StoppedState
D/DhcpStateMachine(  865): StoppedState{ when=-170ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/UpdateIcingCorporaServi( 1947): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  865): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5896 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1947): UpdateCorporaTask done [took 98 ms] updated apps [took 98 ms] 
,I/ActivityManager(  865): Killing 5587:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10053/pid_5587/cgroup.procs: No such file or directory
,I/ActivityManager(  865): Process com.lge.qremote (pid 5092) has died
,D/Finsky  ( 5896): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5896): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5896): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5896): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5896): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@1b62bfbf on behalf of 5896
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2825): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/Ads     ( 5896): Skipping gmscore version check
D/Finsky  ( 5896): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5896): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 5896): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 5494): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5896): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2825): wlan0: Associated with c0:ff:d4:d3:aa:48
I/ActivityManager(  865): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5956 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/wpa_supplicant( 2825): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2825): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 4
I/PackageBroadcastService( 5494): Null package name or gms related package.  Ignoreing.
,D/LocSvc_java(  865): onReceive
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 309us total 22.513ms
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/WifiServiceExtension(  865): setVHTCapabilityType  : false
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 805us total 22.183ms
,I/WifiServerServiceExt(  865): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  865): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  865): setSecurityType  : 2
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 21.069ms
,I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:23.891 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:23.895 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:23.897 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:23.899 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:23.901 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:23.902 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyO,nly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  865): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  865): Got NetworkAgent Messenger
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  865): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  865): NetworkAgent connected
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1807): isInternetCheckAvailable return false
E/WifiConfigStore(  865): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
E/WifiConfigStore(  865): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  281): Setting iface cfg
E/WifiStateMachine(  865): Start Dhcp Watchdog 2
D/DhcpStateMachine(  865): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  865): WaitBeforeStartState
I/ActivityManager(  865): Process com.uei.lg.quicksetsdk.lite (pid 5755) has died
,D/WifiServerServiceExt(  865): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  865): setSupplicantStateASSOCIATED
,D/WifiServerServiceExt(  865): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  865): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  865): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  865): setSupplicantStateGROUP_HANDSHAKE
I/Icing   ( 5494): updateResources: need to parse f{com.google.android.gms}
,D/ConnectivityService(  865): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
W/ResourcesManager( 5956): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,E/WifiStateMachine(  865): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  865): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  865): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@10d185b2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  865): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@10d185b2 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  865): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  865): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/BluetoothManagerService(  865): Message: 20
D/BluetoothManagerService(  865): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@274dee4b:true
D/DhcpStateMachine(  865): DHCP Start wake lock is acquired.
D/CommandListener(  281): Setting iface cfg
I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  281): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  865): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/WifiServerServiceExt(  865): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  865): setSupplicantStateCOMPLETED
,D/WifiServerServiceExt(  865): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  865): setSupplicantStateCOMPLETED
D/ConnectivityService(  865): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/BluetoothAdapterService(681627302)( 1995): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ef2022c
D/LGWifiP2pService(  865): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  865): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapterService(681627302)( 1995): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ef2022c
,E/WifiStateMachine(  865): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  865): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService(  865): ignoring duplicate network state non-change
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1807): isInternetCheckAvailable return false
D/ConnectivityService(  865): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  865): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
,D/WifiServiceExtension( 1807): isInternetCheckAvailable return false
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:24.226 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:24.228 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
E/WifiStateMachine(  865): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:24.24 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1843): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  865): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  865): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:24.247 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1843): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/ConnectivityService(  865): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  865): Adding Route [fe80::/64 -> :: wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  865): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 2
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  281): netlink response contains error (File exists)
D/ConnectivityService(  865): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  281): [get,addrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/ConnectivityService(  865): addLocalRoutetoDefaultNetwork
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  865): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  865): Setting Dns servers for network 101 to [/192.168.1.1]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/Nat464Xlat(  865): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  865): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  865): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 2
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  865): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  865):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  865):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  865):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  865):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  865):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  865): currentScore = 0, newScore = 20
D/ConnectivityService(  865):    accepting network in place of null
D/ConnectivityService(  865): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1751): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  865): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  865):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): [LWD] Start DNSResolver start to wait
E/ConnectivityService(  865): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  865): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  865): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  865): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  865): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  865): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/Tethering(  865): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1843): |CORE| No family connected
I/QCNEJ   ( 1843): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1843): |CORE| sendDefaultNwMsg: default = 1
,V/NetworkPolicy(  865): [LG_RESTRICTED] checkMobilePolicy_type()
D/ConnectivityService(  865): validation of new default Network = false
D/ConnectivityService(  865): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  865): enableDataServiceNotify 
D/DSQN    (  865): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): [LWD] wait 500ms before dns check
D/ConnectivityService(  865): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  865):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  865):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,D/ConnectivityService(  865): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/CheckinService( 5494): Checkin interval check for package: unspecified last checkin: 1454420771924 min interval config: 0 actual interval: 12380
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/DSQN    ( 5981): DSQN samuel.seo ver 141203
E/DSQN    ( 5981): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5981): created command queue thread
I/DSQN    ( 5981): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5981): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/ActivityManager(  865): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5986 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/CheckinService( 5494): Checking schedule, now: 1454420784372 next: 1454420801886
I/CheckinService( 5494): active receiver: disabled
,V/LGMDMManager( 5956): Create singleton instance
,D/DhcpStateMachine(  865): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  865): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  865): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5992): version 5.5.6 starting
,E/dhcpcd  ( 5992): get_duid: Read-only file system
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/dhcpcd  ( 5992): wlan0: rebinding lease of 192.168.1.134
,I/AudioManager( 5956): getMode name:com.lge.qremote
,I/AudioManager( 5956): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5986): Quickset Services start...
I/UEI.SmartControl( 5986): Manufacture = LGE
,D/UEI.SmartControl( 5986): File observer start...
E/UEI.SmartControl( 5986): IR Port is disabled: false
D/UEI.SmartControl( 5986): Starting file observer...
D/UEI.SmartControl( 5986): Extracting JNI libs...
D/UEI.SmartControl( 5986): --- this system supports 32-bit or 64-bit only
V/SetupWizard( 5675): Connected to Gservices successfully
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{239fcc6c type 2 when 90811 com.android.providers.calendar} when 90811
,D/UEI.SmartControl( 5986): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5986): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5986): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/art     ( 5494): Background sticky concurrent mark sweep GC freed 4297(244KB) AllocSpace objects, 0(0B) LOS objects, 2% free, 14MB/14MB, paused 8.390ms total 30.719ms
,I/UEI.SmartControl( 5986): --- Selecting new region: 2
I/UEI.SmartControl( 5986): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5986): Platform has CIR...
,D/UEI.SmartControl( 5986): NO CIR support, need to check package...
I/UEI.SmartControl( 5986): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5986): QS Service created
D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/LocationInitializer( 5494): Restart initialization of location
,D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/MDM     ( 1736): [120] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/NotificationManager( 1736): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1736): No location to return for getLastLocation()
W/FusedLocationProvider( 1736): location=null
E/UEI.SmartControl( 5986): QS start get config
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 1736): propertyValue:false
,I/ActivityManager(  865): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6022 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 5986): Loading JNI Libs...
I/DSQN    ( 5981): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5981): restart monitoring
D/LGDataListener(  281): argv[0]=dsqncommand
D/LGDataListener(  281): argv[1]=wlan0
D/LGDataListener(  281): argv[2]=1
D/LGDataListener(  281): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5981): dsqn report finish
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): [LWD] DNSResolver start dns
D/DSQN    (  865): DSQM DsqnNotification wlan0  1
D/DSQN    (  865): start to monitor internet connection
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/UEI.SmartControl( 5986):  configuring local db...
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     (  865): Explicit concurrent mark sweep GC freed 70019(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 4.082ms total 235.305ms
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out(  865): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 13:46:24 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454420784875], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454420784857]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1807): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  865): Validated
D/ConnectivityService(  865): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  865): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  865):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  865):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  865):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  865): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  865): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  865):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  865):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  865): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  865): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  865): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiDataContinuityService(  865): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
D/WIFI    (  865): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  865):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/WifiServerServiceExt(  865): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyNetworkFactory-1( 1751): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1751):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/UEI.SmartControl( 5986):  ---- Has DB8: true
,D/UEI.SmartControl( 5986): QS start statue = true Error code = 0
D/UEI.SmartControl( 5986): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5986): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5986): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5986): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5986): IrrcClient ++ 
D/irrcClient( 5986): getIrrcService ++ 
,D/irrcClient( 5986): getIrrcService -- 
D/irrcClient( 5986): IrrcClient -- 
W/irrc_jni( 5986): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5986): Services init done
,I/UEI.SmartControl( 5986): Device manager: loading config....
D/UEI.SmartControl( 5986): QS Service init finished
D/UEI.SmartControl( 5986): QS Service version name: 0.1.73
D/UEI.SmartControl( 5986): QS Service version code: 1073
D/UEI.SmartControl( 5986): Config is loaded...
,D/UEI.SmartControl( 5986): Service requested: Control
D/UEI.SmartControl( 5986): Internal service binding...
D/UEI.SmartControl( 5986): -----IControl: 11
,D/UEI.SmartControl( 5986): Caller: com.lge.qremote
D/UEI.SmartControl( 5986): ------------ IControl registerCallback...
I/UEI.SmartControl( 5986): Registering callback...
D/UEI.SmartControl( 5986): -----IControl: 19
D/UEI.SmartControl( 5986): Caller: com.lge.qremote
I/UEI.SmartControl( 5986): Registering Services Ready callback...
I/UEI.SmartControl( 5986): Notify client services are ready...
D/UEI.SmartControl( 5986): -----IControl: 8
D/UEI.SmartControl( 5986): Caller: com.lge.qremote
,D/UEI.SmartControl( 5986):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5986): Notify AllClients services are ready: 0
I/Gmail   ( 6022): getAccountsCursor
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Netd    (  281): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  865): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
,D/ConnectivityService(  865): identical MTU - not setting
D/Nat464Xlat(  865): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  865): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  865):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  865):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  865): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524295
D/ConnectivityService(  865): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  865): enableDataServiceNotify 
D/DSQN    (  865): start dsqn bin
I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:25.28 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/Icing   ( 5494): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/DSQN    (  865): dsqn is running restart
,D/ConnectivityService(  865): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,W/GAV2    ( 6022): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/DSQN    ( 6055): DSQN samuel.seo ver 141203
E/DSQN    ( 6055): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6055): created command queue thread
I/DSQN    ( 6055): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6055): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/art     ( 1736): Explicit concurrent mark sweep GC freed 29164(1797KB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 13MB/22MB, paused 1.424ms total 150.246ms
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  865): Killing 5722:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/Icing   ( 5494): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/libprocessgroup(  865): failed to open /acct/uid_10014/pid_5722/cgroup.procs: No such file or directory
,W/ActivityManager(  865): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 6022): Error finding the version of the Email provider.....
E/Gmail   ( 6022): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6022): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6022): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6022): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6022): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6022): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6022): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6022): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6022): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6022): getAccountsCursor
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  865): Killing 5782:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Gmail   ( 6022): Observing account changes for notifications
W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup(  865): failed to open /acct/uid_10011/pid_5782/cgroup.procs: No such file or directory
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  865): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  865): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  865): onReceive
D/LocSvc_java(  865): got connectivity action
D/LocSvc_java(  865): broadcast - no network connections
D/LocSvc_java(  865): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  865): Sending msg: 4 arg1:0 arg2:1
D/GpsLocationProvider(  865): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  865): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  865): onReceive
D/LocSvc_java(  865): got connectivity action
D/LocSvc_java(  865): broadcast - no network connections
D/LocSvc_java(  865): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  865): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  865): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  865): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  865): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  865): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  865): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  865): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  865): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  865): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  865): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6072 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 6022): notifyAccountChanged
,I/Gmail   ( 6022): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6022): getAccountsCursor
,I/Gmail   ( 6022): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6072): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Gmail   ( 6022): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6022): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/CalendarApplication( 6072): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6072): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6072): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@374762ef, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3d6421fc, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2ae57085, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@37d79eda, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2fd13f0b, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2acf61e8, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@b919001, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@28a0cea6, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@5d2c0e7, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@b2cb494, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1f862b3d, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3b7b2f32, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@e808483, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@156a8600, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@372f3e39, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3d290c7e, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@33bce5df, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3ef2022c, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@23bc84f5, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@3245728a, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@313400fb, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@8931518, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1f9d7b71, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1c102d56, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@737b1d7, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2e306ac4, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2bd5dad, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3df9c8e2, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3f5b9473, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@252b6f30, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3e7f27a9, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2fef912e, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1ed104cf, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@15904e5c, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1d799565, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@967923a, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@22831eeb, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3a01f448, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2f322e1, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@312c9806, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@20f2bec7, lg_preferences_rece,nt_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@12660cf
,D/GeneralPreferenceUtils( 6072): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6072): [init]
,I/Config  ( 6072): LGCalendar ver.4.40.17
I/Config  ( 6072): start check model
I/Config  ( 6072): start check native_ca
I/Config  ( 6072): Config Operator=OPEN, Country=EU
D/Config  ( 6072): [setDefaultValuesToPref]
D/Config  ( 6072): [parseProfiles]
D/ProfilesParser( 6072): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6072): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6072): [updateProfiletoCountryInfo]
D/GeneralPreference( 6072): [checkAndMigrateOldPreference]
I/Gmail   ( 6022): getAccountsCursor
,I/dhcpcd  ( 5992): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AlertReceiver( 6072): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6072): Start InitializeAlertRingtoneService.onHandleIntent
I/ActivityManager(  865): Killing 5705:com.google.android.talk/u0a61 (adj 15): empty #11
,I/AlertUtils( 6072): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/dhcpcd  ( 5992): wlan0: leased 192.168.1.134 for 86400 seconds
W/libprocessgroup(  865): failed to open /acct/uid_10061/pid_5705/cgroup.procs: No such file or directory
,I/AlertUtils( 6072): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
W/HolidayIntentService( 6072): onHandleIntent
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
D/HolidayDataLoader( 6072): readJsonAsset : holiday.json
,I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,D/AlertService( 6072): 0 Action = android.intent.action.PROVIDER_CHANGED
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,E/AgendaWidgetManager( 6072): [updateWidgets] 
D/MonthWidgetProvider( 6072): [onReceive]
D/CalendarWidgetProvider( 6072): [onReceive]
D/CalendarWidgetProvider( 6072): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,D/CalendarTypeController( 6072): [onCreate] mContext.getPackageName() = com.android.calendar
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6072): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,D/WeekWidgetProvider( 6072): [onReceive]
D/CalendarWidgetProvider( 6072): [onReceive]
D/CalendarWidgetProvider( 6072): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/AlertUtils( 6072): set default noti to content://media/internal/audio/media/38
D/CalendarTypeController( 6072): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5956): getMode name:com.lge.qremote
,I/InitNotificationRingtoneService( 6072): End InitializeAlertRingtoneService.onHandleIntent
E/HolidayIntentService( 6072): onHandleIntent:holiday data empty
,I/ActivityManager(  865): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6121 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  865): DHCPV4 succeeded on wlan0
,D/LgDhcpStateMachineHelper(  865): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  865): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  865): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  865): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  865): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  865): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  865): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  865): RunningState
W/ResourcesManager( 6121): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6121): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6121): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6121): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6121): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6121): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6121): MmsConfig.loadFromResources
E/Babel_SMS( 6121): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6121): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6121): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6121): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6121): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 6121): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6121): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6121): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6121): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6121): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6121): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6121): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6121): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6121): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6121): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6121): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6121): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6121): found sensor: Motion Accel, handle=46
W/Settings( 6121): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6121): startup - clean
I/ActivityManager(  865): Process com.android.contacts (pid 5820) has died
,I/art     ( 6121): CheckpointMarkThreadRoots callback created = 0xb002d520
I/Babel   ( 6121): deleted: false for 0
I/art     ( 6121): CheckpointMarkThreadRoots callback created = 0xb002d500
,I/NotificationManager( 1947): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,W/AudioCapabilities( 6121): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6121): Unsupported mime audio/adpcm
W/AudioCapabilities( 6121): Unsupported mime audio/g726
W/AudioCapabilities( 6121): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6121): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6121): Unsupported mime video/mjpg
I/ActivityManager(  865): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6158 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/QCNEJ   ( 1843): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1843): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-64 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 14:46:27.128 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/VideoCapabilities( 6121): Unsupported mime video/theora
,W/AudioCapabilities( 6121): Unsupported mime audio/evrc
,W/AudioCapabilities( 6121): Unsupported mime audio/qcelp
W/VideoCapabilities( 6121): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6121): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6121): Unsupported mime audio/qcelp
W/AudioCapabilities( 6121): Unsupported mime audio/evrc
I/AppUp4:AppBoxCP( 6158): onCreate
W/AppUp4:DB( 6158):  [AppBoxDatabaseHelper] construct
,W/VideoCapabilities( 6121): Unsupported mime video/mp4v-esdp
V/WifiInternetCheck(  865): Single check msg out of sync, ignoring.
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/AppUp4:DB( 6158):  setFingerPrint start
I/AppUp4:DB( 6158):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/ConnectivityService(  865): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  865): onReceive
D/LocSvc_java(  865): got connectivity action
D/LocSvc_java(  865): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  865): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  865): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  865): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  865): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  865): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  865): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/AppUp4:DB( 6158):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6158):  SDK version = 0
I/AppUp4:DB( 6158):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6158): AppBoxApplication onCreate()
,I/VideoCapabilities( 6121): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6121): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6121): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6121): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6121): Unrecognized profile 2130706433 for video/avc
I/AppUp4:CustModeStarterReceiver( 6158): onReceive
I/AppUp4:CustModeStarterReceiver( 6158): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6158): Context : android.app.ReceiverRestrictedContext@3d6421fc
,D/AppUp4:CustFacade( 6158): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6158): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6158): begin check event
I/AppUp4:CustModeStarterReceiver( 6158): Event For Nothing, skip.
I/ActivityManager(  865): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6181 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/vclib   ( 6121): onServiceConnected
,W/Babel   ( 6121): Attempted to change video mute state without an active call.
I/NotificationManager( 6121): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 6121): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6121): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6181): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6181): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6181): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6181): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6181): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,V/JNIHelp ( 6121): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/SystemConfig( 6181): BUILD Country: EU
I/SystemConfig( 6181): BUILD Operator: OPEN
,W/System  ( 6121): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6121): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6121): com.google.android.talk: cancel(10436) by com.google.android.talk
E/lowmemorykiller(  243): Error writing /proc/6022/oom_score_adj; errno=22
,I/art     (  865): Explicit concurrent mark sweep GC freed 38416(1935KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.511ms total 149.181ms
,I/ActivityManager(  865): Process com.google.android.gm (pid 6022) has died
,I/SystemConfig( 6181): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6181): existFile = false
,I/SystemConfig( 6181): canReadFile = false
I/SystemConfig( 6181): systemFeature RCS result false
D/SystemConfig( 6181): refreshRcsSupport() :false
D/LockScreenSettings( 5848): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5848): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5848): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5848): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5848): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
V/AlarmManager(  865): RTC_WAKEUP set : Alarm{2d6c7ea9 type 0 when 1454420787947 com.android.vending} when 1454420787947
D/Finsky  ( 5896): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/UpdateIcingCorporaServi( 1947): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/PackageBroadcastService( 5494): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 1947): UpdateCorporaTask done [took 48 ms] updated apps [took 48 ms] 
I/ActivityManager(  865): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6209 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/PackageBroadcastService( 5494): Null package name or gms related package.  Ignoreing.
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 5494): updateResources: need to parse f{com.google.android.gms}
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  865): android: cancelAsUser(2) by android
,W/ResourcesManager( 6209): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6209): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6209): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6209): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6209): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/lowmemorykiller(  243): Error writing /proc/5956/oom_score_adj; errno=22
,I/IndexDatabaseHelper( 6209): Using schema version: 115
I/IndexDatabaseHelper( 6209): Index is fine
,I/ActivityManager(  865): Process com.lge.qremote (pid 5956) has died
,D/libc-netbsd( 5896): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5896): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5896): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5896): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out( 5896): propertyValue:false
D/libc-netbsd( 5896): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5896): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 6055): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6055): restart monitoring
,D/LGDataListener(  281): argv[0]=dsqncommand
D/LGDataListener(  281): argv[1]=wlan0
D/LGDataListener(  281): argv[2]=1
D/LGDataListener(  281): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  865): DSQM DsqnNotification wlan0  1
D/DSQN    (  865): start to monitor internet connection
I/DSQN    ( 6055): dsqn report finish
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/libc-netbsd( 5896): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5896): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
,I/System.out(  865): propertyValue:false
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  865): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  865): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out(  865): propertyValue:false
D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
V/WifiInternetCheck(  865): isHttpConnectionAvailable - We got a valid response : 204
,I/ActivityManager(  865): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6238 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 94847846531; DSPS: 3199355; Offset : -2801230724
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  865): android: cancelAsUser(2) by android
,I/PCSuite ( 6238): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6238): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6238): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/qtaguid ( 5896): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5896): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5896): untagSocket(41) failed with errno -22
D/Finsky  ( 5896): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  865): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6262 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 6262): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  865): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6280 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  865): android: cancelAsUser(2) by android
,W/ResourcesManager( 6280): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6280): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/BluetoothManagerService(  865): Message: 20
D/BluetoothManagerService(  865): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2c407854:true
,D/BluetoothAdapterService(681627302)( 1995): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ef2022c
D/BluetoothAdapterService(681627302)( 1995): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ef2022c
,V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
I/PCSuite ( 6238): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6238): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6238): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/MultiDex( 6280): VM with version 2.1.0 has multidex support
I/MultiDex( 6280): install
I/MultiDex( 6280): VM has multidex support, MultiDex support library is disabled.
D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
I/PCSuite ( 6238): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6238): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6238): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/qtaguid ( 5896): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5896): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5896): untagSocket(41) failed with errno -22
D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
,I/PCSuite ( 6238): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6238): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6238): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
V/JNIHelp ( 6280): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6209): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/ActivityThread( 6280): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6280): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c32068c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6280): Installed default security provider GmsCore_OpenSSL
D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
I/NotificationManager( 6280): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6280): com.google.android.gms: cancel(39789) by com.google.android.gms
V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
D/ChimeraCfgMgr( 6280): Reading stored module config
,I/Icing   ( 5494): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  865): Process com.uei.lg.quicksetsdk.lite (pid 5986) has died
,D/ChimeraCfgMgr( 6280): Loading module com.google.android.gms.car from APK com.google.android.gms
,V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/art     ( 5896): CheckpointMarkThreadRoots callback created = 0xb002d950
D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
D/NativeLibraryUtils( 6280): Install completed successfully. count=14 extracted=0
I/PCSuite ( 6238): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
I/Icing   ( 5494): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/PCSuite ( 6238): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6209): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6209): MCCMNC not supported: null
I/PCSuite ( 6238): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6238): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/art     ( 5896): CheckpointMarkThreadRoots callback created = 0xaaeecc90
D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/CAR.SERVICE( 6280): Connecting to CarCallService...
,I/ActivityManager(  865): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6313 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 23.968ms
,V/LGMDMManager( 6262): Create singleton instance
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.691ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.239ms
,I/art     ( 6280): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6280): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/UEI.SmartControl( 6313): Quickset Services start...
I/UEI.SmartControl( 6313): Manufacture = LGE
,I/AudioManager( 6262): getMode name:com.lge.qremote
D/UEI.SmartControl( 6313): File observer start...
E/UEI.SmartControl( 6313): IR Port is disabled: false
D/UEI.SmartControl( 6313): Starting file observer...
D/UEI.SmartControl( 6313): Extracting JNI libs...
,D/UEI.SmartControl( 6313): --- this system supports 32-bit or 64-bit only
D/CAR.SERVICE( 6280): com.google.android.projection.gearhead isn't installed.
I/ActivityManager(  865): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6333 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6313): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6313): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6313): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,D/CAR.TEL.Service( 6280): Creating a new CarCallService.
W/ResourcesManager( 6333): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/UEI.SmartControl( 6313): --- Selecting new region: 2
I/UEI.SmartControl( 6313): -- Running on KitKat(19) and above! JNI will be used.
D/CAR.TEL.PhoneAdapter( 6280): Creating a new PhoneAdapter instance
W/ActivityManager(  865): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6280): setListener: com.google.android.gms.car.dn@2de26ecb
W/ActivityManager(  865): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6280): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6280): Starting CarCallService with initial phone null
D/UEI.SmartControl( 6313): Platform has CIR...
,D/UEI.SmartControl( 6313): NO CIR support, need to check package...
I/UEI.SmartControl( 6313): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6313): QS Service created
,D/CalendarProvider2( 6333): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@151d90c9
I/NotificationManager( 6280): com.google.android.gms: cancel(10436) by com.google.android.gms
,E/UEI.SmartControl( 6313): QS start get config
,D/CalendarProvider2( 6333): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6333): Created com.android.providers.calendar.CalendarAlarmManager@37d79eda(com.android.providers.calendar.CalendarProvider2@151d90c9)
D/CalendarProviderBroadcastReceiver( 6333): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6333): [IntentService] WakeLock acquire, start IntentSerivce
D/CAR.SERVICE( 6280): Package validated; name: com.android.vending
,D/UEI.SmartControl( 6313): Loading JNI Libs...
D/UEI.SmartControl( 6313):  configuring local db...
,D/CalendarProvider2( 6333): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6333): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6333): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  865): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6354 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager( 5896): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5896): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/ActivityManager(  865): Process com.android.contacts (pid 6181) has died
,D/CalendarProvider2( 6333): [IntentService] Release Lock
,D/CalendarProvider2( 6333): CalendarProviderIntentService.onDestroy()
D/UEI.SmartControl( 6313):  ---- Has DB8: true
,D/UEI.SmartControl( 6313): QS start statue = true Error code = 0
D/UEI.SmartControl( 6313): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6313): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6313): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6313): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6313): IrrcClient ++ 
,D/irrcClient( 6313): getIrrcService ++ 
D/irrcClient( 6313): getIrrcService -- 
D/irrcClient( 6313): IrrcClient -- 
W/irrc_jni( 6313): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6313): Services init done
,D/UEI.SmartControl( 6313): QS Service init finished
I/UEI.SmartControl( 6313): Device manager: loading config....
D/UEI.SmartControl( 6313): QS Service version name: 0.1.73
D/UEI.SmartControl( 6313): QS Service version code: 1073
D/UEI.SmartControl( 6313): Service requested: Control
D/UEI.SmartControl( 6313): Config is loaded...
W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/UEI.SmartControl( 6313):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 6313): Request IControl service: devices are loaded...
,I/UEI.SmartControl( 6313): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6313): Internal service binding...
D/UEI.SmartControl( 6313): -----IControl: 11
D/UEI.SmartControl( 6313): Caller: com.lge.qremote
D/UEI.SmartControl( 6313): ------------ IControl registerCallback...
I/UEI.SmartControl( 6313): Registering callback...
,D/UEI.SmartControl( 6313): -----IControl: 19
D/UEI.SmartControl( 6313): Caller: com.lge.qremote
I/UEI.SmartControl( 6313): Registering Services Ready callback...
I/UEI.SmartControl( 6313): Notify client services are ready...
D/UEI.SmartControl( 6313): -----IControl: 8
D/UEI.SmartControl( 6313): Caller: com.lge.qremote
I/ActivityManager(  865): Process com.android.gallery3d (pid 5801) has died
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  865): android: cancelAsUser(2) by android
,I/Gmail   ( 6354): getAccountsCursor
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6354): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  865): Killing 6158:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/qtaguid ( 5896): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5896): Untagging socket 41 failed errno=-22
,W/NetworkManagementSocketTagger( 5896): untagSocket(41) failed with errno -22
W/libprocessgroup(  865): failed to open /acct/uid_10011/pid_6158/cgroup.procs: No such file or directory
,W/ActivityManager(  865): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6354): Observing account changes for notifications
E/Gmail   ( 6354): Error finding the version of the Email provider.....
E/Gmail   ( 6354): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6354): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6354): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6354): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6354): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6354): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6354): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6354): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AudioManager( 6262): getMode name:com.lge.qremote
W/EmailMigration( 6354): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6354): getAccountsCursor
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  865): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6407 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AlertService( 6072): Beginning updateAlertNotification
,I/ActivityManager(  865): Killing 5848:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/ResourcesManager( 5896): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5896): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5896): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  865): Explicit concurrent mark sweep GC freed 18651(895KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.199ms total 161.196ms
,W/libprocessgroup(  865): failed to open /acct/uid_10069/pid_5848/cgroup.procs: No such file or directory
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5896): [1] DailyHygiene.access$600: Logging device features
D/AlertService( 6072): No fired or scheduled alerts
,V/AlarmManager(  865): RTC_WAKEUP set : Alarm{8667d8b type 0 when 1454420791462 com.android.vending} when 1454420791462
I/NotificationManager( 6072): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(11) by com.android.calendar
,I/NotificationManager( 6072): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(20) by com.android.calendar
D/WearableService( 1736): callingUid 10006, callindPid: 1736
,I/jxcore-log( 5537): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5537): 
D/AlertService( 6072): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/DeviceConnectionService( 1736): client connected with version: 8296000
,D/Finsky  ( 5896): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5896): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/ActivityManager(  865): Killing 5865:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/AlarmScheduler( 6072): No events found starting within 1 week.
,I/Gmail   ( 6354): notifyAccountChanged
,I/Gmail   ( 6354): getAccountsCursor
I/Gmail   ( 6354): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/libprocessgroup(  865): failed to open /acct/uid_10086/pid_5865/cgroup.procs: No such file or directory
I/ActivityManager(  865): Killing 6209:com.android.settings/1000 (adj 15): empty #11
,I/Gmail   ( 6354): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6354): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6354): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/MusicStore( 6407): Database version: 120
,W/libprocessgroup(  865): failed to open /acct/uid_1000/pid_6209/cgroup.procs: No such file or directory
I/ActivityManager(  865): Killing 6072:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10013/pid_6072/cgroup.procs: No such file or directory
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6407): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Gmail   ( 6354): getAccountsCursor
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6407): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6407): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6407): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6407): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6407): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6407): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6407): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@125e8d97: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6407): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6407): GMSCore installation verified
I/ConfigStore( 6407): Config Database version: 1
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MediaRouter( 6407): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6407): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6407): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6407): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  865): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6444 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/GHttpClientFactory( 6407): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6407): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  865): Killing 6238:com.lge.sync/1000 (adj 15): empty #11
,W/ResourcesManager( 6444): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6444): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6444): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/jxcore-log( 5537): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5537): 
,W/libprocessgroup(  865): failed to open /acct/uid_1000/pid_6238/cgroup.procs: No such file or directory
,I/NotificationManager( 6407): com.google.android.music: cancel(1061) by com.google.android.music
V/AlarmManager(  865): RTC_WAKEUP set : Alarm{3d1a2d4b type 0 when 1454420792724 com.google.android.googlequicksearchbox} when 1454420792724
,I/jxcore-log( 5537): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5537): 
,I/LGEmail ( 6444): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/jxcore-log( 5537): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5537): 
D/LGEmail ( 6444): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  865): Killing 5675:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/jxcore-log( 5537): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5537): 
,I/jxcore-log( 5537): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5537): 
,I/jxcore-log( 5537): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5537): 
I/jxcore-log( 5537): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5537): 
,W/libprocessgroup(  865): failed to open /acct/uid_10038/pid_5675/cgroup.procs: No such file or directory
,D/eas_req ( 6444): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  865): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6481 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6444): JNI_OnLoad()
I/HubEmail( 6444): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6444): registerNatives()
I/HubEmail( 6444): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6444): registerNativeMethods()
I/HubEmail( 6444): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6444): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  865): Killing 6333:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10014/pid_6333/cgroup.procs: No such file or directory
W/Settings( 6444): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6481): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6481): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6481): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6481): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6481): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6481): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6481): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6481): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  865): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6509 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6481): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6481): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6481): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6481): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6481): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6481): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  865): Killing 6121:com.google.android.talk/u0a61 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6509): onCreate
,W/AppUp4:DB( 6509):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6509):  setFingerPrint start
I/AppUp4:DB( 6509):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6509):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6509):  SDK version = 0
I/AppUp4:DB( 6509):  beforefinger == newfinger no write in DB
W/libprocessgroup(  865): failed to open /acct/uid_10061/pid_6121/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6509): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 6509): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6509): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6509): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6509): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6509): onReceive
I/AppUp4:CustModeStarterReceiver( 6509): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6509): Context : android.app.ReceiverRestrictedContext@2fd13f0b
D/AppUp4:CustFacade( 6509): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6509): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6509): begin check event
I/AppUp4:CustModeStarterReceiver( 6509): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6509): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6509): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6509): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6509): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  865): Killing 6313:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6262): android.os.DeadObjectException
,W/System.err( 6262): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6262): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6262): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6262): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6262): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6262): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6262): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6262): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6262): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6262): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6262): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6262): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6262): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6262): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6262): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6262): android.os.DeadObjectException
W/System.err( 6262): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6262): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6262): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6262): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6262): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6262): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6262): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6262): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6262): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6262): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6262): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6262): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6262): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6262): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6262): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
E/libprocessgroup(  865): failed to kill 1 processes for processgroup 6313
,I/LgeMiscReceiver( 3177): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3177): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3177): networkInfo.isConnected() = false
,W/ActivityManager(  865): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  865): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6532 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  865): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6548 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6548): Quickset Services start...
,I/UEI.SmartControl( 6548): Manufacture = LGE
D/UEI.SmartControl( 6548): File observer start...
E/UEI.SmartControl( 6548): IR Port is disabled: false
D/UEI.SmartControl( 6548): Starting file observer...
D/UEI.SmartControl( 6548): Extracting JNI libs...
D/UEI.SmartControl( 6548): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6548): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6548): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6548): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6548): --- Selecting new region: 2
,I/UEI.SmartControl( 6548): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6548): Platform has CIR...
D/PhoneMonitor( 6532): Register our PhoneStateListener
D/UEI.SmartControl( 6548): NO CIR support, need to check package...
I/UEI.SmartControl( 6548): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6548): QS Service created
D/MobileConnectivityChangeReceiver( 6532): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6532): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  865): Killing 6262:com.lge.qremote/u0a106 (adj 15): empty #11
E/UEI.SmartControl( 6548): QS start get config
,D/UEI.SmartControl( 6548): Loading JNI Libs...
,D/UEI.SmartControl( 6548):  configuring local db...
W/libprocessgroup(  865): failed to open /acct/uid_10106/pid_6262/cgroup.procs: No such file or directory
,V/DownloadManager( 3199): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/CheckinService( 5494): Checkin interval check for package: unspecified last checkin: 1454420771924 min interval config: 0 actual interval: 22730
V/DownloadManager( 3199): DownloadService onCreate
I/DownloadManager( 3199): in removeSpuriousFiles
D/PhoneMonitor( 6532): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/DownloadManager( 3199): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 3199): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@c32068c on behalf of 3199
V/TelephonyAutoProfiling( 6532): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6532): [parse] Load xml
I/DownloadManager( 3199): in trimDatabase
V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/TelephonyAutoProfiling( 6532): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6532): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@b93a1d5 on behalf of 3199
,I/ActivityManager(  865): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6585 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3199): DownloadService onStartCommand
D/UEI.SmartControl( 6548):  ---- Has DB8: true
,D/UEI.SmartControl( 6548): QS start statue = true Error code = 0
D/UEI.SmartControl( 6548): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6548): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6548): IRRCDataComm has AudioManager!!!!.
,V/DownloadManager( 3199): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
W/irrc_jni( 6548): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6548): IrrcClient ++ 
D/irrcClient( 6548): getIrrcService ++ 
D/irrcClient( 6548): getIrrcService -- 
D/irrcClient( 6548): IrrcClient -- 
W/irrc_jni( 6548): IRRCPlayer_nativeInit -- 
,D/PhoneMonitor( 6532): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@63eff78 on behalf of 3199
D/UEI.SmartControl( 6548): Services init done
,D/UEI.SmartControl( 6548): QS Service init finished
D/UEI.SmartControl( 6548): QS Service version name: 0.1.73
D/UEI.SmartControl( 6548): QS Service version code: 1073
D/UEI.SmartControl( 6548): Service requested: Control
,I/UEI.SmartControl( 6548): Device manager: loading config....
D/UEI.SmartControl( 6548): Config is loaded...
,D/UEI.SmartControl( 6548):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6548): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6548): Request IControl service: devices are loaded...
,V/DownloadManager( 3199): DownloadService onDestroy
D/UEI.SmartControl( 6548): Service.onUnbind: IControl
D/UEI.SmartControl( 6548): Service.onDestroy
D/UEI.SmartControl( 6548): Shutdown IRRCPlayer... 
W/irrc_jni( 6548): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6548): ~IrrcClient ++ 
D/irrcClient( 6548): ~IrrcClient -- 
W/irrc_jni( 6548): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6548): Blaster closed
D/UEI.SmartControl( 6548): Blaster closed
D/UEI.SmartControl( 6548): Shut down QS...
D/UEI.SmartControl( 6548): Stopped file observer...
,I/UEI.SmartControl( 6548): QS lib stop result = true
D/UEI.SmartControl( 6548): QS shutdown complete
D/UEI.SmartControl( 6548): QS Service created
E/UEI.SmartControl( 6548): QS start get config
,I/art     ( 5494): WaitForGcToComplete blocked for 6.120ms for cause DisableMovingGc
I/CheckinService( 5494): Checking schedule, now: 1454420794873 next: 1454420801886
I/CheckinService( 5494): active receiver: disabled
D/WeatherAncestor( 2715): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:46:34
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
,D/WeatherAncestor( 2715): connectivity changed - connection : true
D/Weather_cast( 2715): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2715): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:46:34
D/WeatherService( 2715): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/UEI.SmartControl( 6548):  configuring local db...
,I/ActivityManager(  865): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6605 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  865): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/ActivityManager(  865): Killing 6354:com.google.android.gm/u0a53 (adj 15): empty #11
D/UEI.SmartControl( 6548):  ---- Has DB8: true
,D/UEI.SmartControl( 6548): QS start statue = true Error code = 0
D/UEI.SmartControl( 6548): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6548): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6548): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6548): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6548): IrrcClient ++ 
D/irrcClient( 6548): getIrrcService ++ 
D/irrcClient( 6548): getIrrcService -- 
D/irrcClient( 6548): IrrcClient -- 
W/irrc_jni( 6548): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6548): Services init done
I/UEI.SmartControl( 6548): Device manager: loading config....
D/UEI.SmartControl( 6548): Config is loaded...
D/UEI.SmartControl( 6548):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6548): Notify AllClients services are ready: 0
,W/libprocessgroup(  865): failed to open /acct/uid_10053/pid_6354/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6548): QS Service init finished
D/UEI.SmartControl( 6548): QS Service version name: 0.1.73
D/UEI.SmartControl( 6548): QS Service version code: 1073
D/UEI.SmartControl( 6548): Service requested: Control
I/ActivityManager(  865): Killing 6280:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/ResourcesManager( 6605): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/libprocessgroup(  865): failed to open /acct/uid_10006/pid_6280/cgroup.procs: No such file or directory
E/ActivityThread( 6548): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@28a0cea6 that was originally bound here
E/ActivityThread( 6548): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@28a0cea6 that was originally bound here
E/ActivityThread( 6548): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6548): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6548): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6548): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6548): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6548): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6548): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6548): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6548): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6548): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6548): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6548): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6548): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6548): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6548): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6548): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6548): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6548): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  865): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
D/UEI.SmartControl( 6548): Internal service binding...
,I/Babel_SMS( 6605): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6605): MmsConfig.loadMmsSettings
I/Babel_SMS( 6605): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6605): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6605): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6605): MmsConfig.loadFromResources
E/Babel_SMS( 6605): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6605): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6605): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6605): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6605): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6605): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6605): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6605): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6605): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6605): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6605): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6605): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6605): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6605): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6605): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6605): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6605): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6605): found sensor: Motion Accel, handle=46
,W/Settings( 6605): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6605): startup - clean
I/Babel   ( 6605): deleted: false for 0
,I/art     ( 6605): CheckpointMarkThreadRoots callback created = 0xb002d510
,I/art     ( 6605): CheckpointMarkThreadRoots callback created = 0xb002d4f0
,I/ActivityManager(  865): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6643 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 343us total 21.185ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.595ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 21.088ms
,W/AudioCapabilities( 6605): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6605): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6605): Unsupported mime audio/g726
W/AudioCapabilities( 6605): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6605): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6605): Unsupported mime video/mjpg
W/VideoCapabilities( 6605): Unsupported mime video/theora
,W/AudioCapabilities( 6605): Unsupported mime audio/evrc
W/AudioCapabilities( 6605): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6605): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6605): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6605): Unsupported mime audio/qcelp
W/AudioCapabilities( 6605): Unsupported mime audio/evrc
W/VideoCapabilities( 6605): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6605): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6605): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6605): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6605): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6605): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6605): onServiceConnected
W/Babel   ( 6605): Attempted to change video mute state without an active call.
I/NotificationManager( 6605): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6605): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6605): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6605): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6605): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  281): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 6605): propertyValue:false
I/Babel   ( 6605): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  865): Killing 5896:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10036/pid_5896/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6643): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6643): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6643): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6643): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6643): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6643):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6643):   adb logcat -s GAv4
,I/rmt_storage(  278): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  278): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  278): wakelock acquired: 1, error no: 42
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/art     (  865): Explicit concurrent mark sweep GC freed 16149(774KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.994ms total 149.374ms
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  278): 
W/GAv4    ( 6643): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/rmt_storage(  278): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/GAv4    ( 6643): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6643): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6643): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6643): Time to load native libraries: 2 ms (timestamps 3151-3153)
I/LibraryLoader( 6643): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6643): Binding Chromium to main looper Looper (main, tid 1) {108a2abc}
,I/LibraryLoader( 6643): Expected native library version number "",actual native library version number ""
I/chromium( 6643): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6643): Initializing chromium process, singleProcess=true
W/art     ( 6643): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6643): ApplicationContext is null in ApplicationStatus
,W/chromium( 6643): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6643): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6643): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6643): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6643): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6643): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6643): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6643): Remote Branch: 
I/Adreno-EGL( 6643): Local Patches: 
I/Adreno-EGL( 6643): Reconstruct Branch: 
V/AudioPolicyService(  285): registerClient() client 0xb4027820, uid 10079
,W/AudioManagerAndroid( 6643): Requires BLUETOOTH permission
I/NSApplication( 6643): Starting up...
,I/ActivityManager(  865): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6715 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  865): Killing 6407:com.google.android.music:main/u0a81 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  865): failed to open /acct/uid_10081/pid_6407/cgroup.procs: No such file or directory
I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/ActivityManager(  865): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6735 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  865): Killing 6444:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10021/pid_6444/cgroup.procs: No such file or directory
,W/ResourcesManager( 6735): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 5494): SYNC; picasa accounts
,D/NetworkLogImpl( 5494): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5494): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager(  865): Killing 6481:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/iu.UploadsManager( 5494): num queued entries: 0
I/iu.UploadsManager( 5494): num updated entries: 0
I/iu.SyncManager( 5494): NEXT; no task
,W/libprocessgroup(  865): failed to open /acct/uid_1000/pid_6481/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  865): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6762 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 6762): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6762): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6762): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6762): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6762): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6762): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6762): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6762): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6762): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@125e8d97: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6762): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6762): GMSCore installation verified
,I/ConfigStore( 6762): Config Database version: 1
,I/MediaRouter( 6762): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6762): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6762): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6762): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  865): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6791 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6762): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6762): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  865): Killing 6509:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6791): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6791): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6791): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/libprocessgroup(  865): failed to open /acct/uid_10011/pid_6509/cgroup.procs: No such file or directory
,I/NotificationManager( 6762): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6791): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/CheckinService( 5494): Done disabling old GoogleServicesFramework version
,D/LGEmail ( 6791): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,E/UEI.SmartControl( 6548): file observer is disposed!
,D/eas_req ( 6791): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  865): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6821 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6791): JNI_OnLoad()
I/HubEmail( 6791): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6791): registerNatives()
I/HubEmail( 6791): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6791): registerNativeMethods()
I/HubEmail( 6791): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6791): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  865): Killing 6532:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/Settings( 6791): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/libprocessgroup(  865): failed to open /acct/uid_10038/pid_6532/cgroup.procs: No such file or directory
D/LGDMClient( 6821): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6821): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6821): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6821): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6821): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6821): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6821): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6821): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  865): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6848 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6821): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6821): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6821): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6821): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6821): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6821): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  865): Killing 6548:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6848): onCreate
,W/AppUp4:DB( 6848):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6848):  setFingerPrint start
I/AppUp4:DB( 6848):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6848):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6848):  SDK version = 0
I/AppUp4:DB( 6848):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  865): failed to open /acct/uid_10089/pid_6548/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6848): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6848): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6848): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6848): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6848): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6848): onReceive
I/AppUp4:CustModeStarterReceiver( 6848): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6848): Context : android.app.ReceiverRestrictedContext@2fd13f0b
D/AppUp4:CustFacade( 6848): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6848): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6848): begin check event
I/AppUp4:CustModeStarterReceiver( 6848): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6848): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6848): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6848): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6848): handleAsyncCustNotification do not startCustService
I/ActivityManager(  865): Killing 6585:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10051/pid_6585/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3177): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3177): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3177): networkInfo.isConnected() = false
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  865): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6880 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6880): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6880): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6880): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  865): Killing 6605:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 6880): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6880): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6880): [parse] Load xml
V/TelephonyAutoProfiling( 6880): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6880): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6880): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,W/libprocessgroup(  865): failed to open /acct/uid_10061/pid_6605/cgroup.procs: No such file or directory
,V/DownloadManager( 3199): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3199): DownloadService onCreate
I/NotificationManager( 3199): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3199): in removeSpuriousFiles
V/DownloadManager( 3199): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@23510eb6 on behalf of 3199
I/DownloadManager( 3199): in trimDatabase
V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@e209b24 on behalf of 3199
I/ActivityManager(  865): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6902 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3199): DownloadService onStartCommand
V/DownloadManager( 3199): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@31576042 on behalf of 3199
I/CheckinService( 5494): Checkin interval check for package: unspecified last checkin: 1454420771924 min interval config: 0 actual interval: 28680
,I/CheckinService( 5494): Checking schedule, now: 1454420800645 next: 1454420801886
I/CheckinService( 5494): active receiver: disabled
,V/DownloadManager( 3199): DownloadService onDestroy
I/ActivityManager(  865): Killing 6643:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,E/libprocessgroup(  865): failed to kill 1 processes for processgroup 6643
,D/WeatherAncestor( 2715): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:46:40
,D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
D/WeatherAncestor( 2715): connectivity changed - connection : true
D/Weather_cast( 2715): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2715): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:46:41
D/WeatherService( 2715): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  865): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6930 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  865): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6930): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Babel_SMS( 6930): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6930): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6930): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 6930): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6930): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6930): MmsConfig.loadFromResources
E/Babel_SMS( 6930): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6930): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6930): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6930): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6930): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6930): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 6930): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6930): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6930): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6930): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6930): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6930): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6930): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6930): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6930): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6930): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6930): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6930): found sensor: Motion Accel, handle=46
W/Settings( 6930): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6930): startup - clean
,I/art     ( 6930): CheckpointMarkThreadRoots callback created = 0xaaf4da40
I/Babel   ( 6930): deleted: false for 0
,I/art     ( 6930): CheckpointMarkThreadRoots callback created = 0xaaf4da10
,I/ActivityManager(  865): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6965 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6930): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6930): Unsupported mime audio/adpcm
W/AudioCapabilities( 6930): Unsupported mime audio/g726
W/AudioCapabilities( 6930): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6930): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6930): Unsupported mime video/mjpg
,W/VideoCapabilities( 6930): Unsupported mime video/theora
W/AudioCapabilities( 6930): Unsupported mime audio/evrc
,W/AudioCapabilities( 6930): Unsupported mime audio/qcelp
W/VideoCapabilities( 6930): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6930): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6930): Unsupported mime audio/qcelp
W/AudioCapabilities( 6930): Unsupported mime audio/evrc
,W/VideoCapabilities( 6930): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6930): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6930): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6930): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6930): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6930): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6930): onServiceConnected
W/Babel   ( 6930): Attempted to change video mute state without an active call.
D/libc-netbsd( 6930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6930): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6930): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  281): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 6930): propertyValue:false
I/NotificationManager( 6930): com.google.android.talk: cancel(10436) by com.google.android.talk
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6965): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 6965): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6965):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6965):   adb logcat -s GAv4
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6965): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6965): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6965): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6965): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 6930): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  865): Killing 6715:com.android.chrome/u0a48 (adj 15): empty #11
W/GAv4    ( 6965): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6965): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  865): failed to open /acct/uid_10048/pid_6715/cgroup.procs: No such file or directory
,I/WebViewFactory( 6965): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     (  865): Explicit concurrent mark sweep GC freed 19207(960KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 7.293ms total 165.146ms
I/LibraryLoader( 6965): Time to load native libraries: 2 ms (timestamps 8550-8552)
I/LibraryLoader( 6965): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6965): Binding Chromium to main looper Looper (main, tid 1) {108a2abc}
I/LibraryLoader( 6965): Expected native library version number "",actual native library version number ""
I/chromium( 6965): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6965): Initializing chromium process, singleProcess=true
,W/art     ( 6965): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6965): ApplicationContext is null in ApplicationStatus
W/chromium( 6965): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6965): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6965): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6965): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6965): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6965): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6965): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6965): Remote Branch: 
I/Adreno-EGL( 6965): Local Patches: 
I/Adreno-EGL( 6965): Reconstruct Branch: 
V/AudioPolicyService(  285): registerClient() client 0xb551c7c0, uid 10079
,W/AudioManagerAndroid( 6965): Requires BLUETOOTH permission
I/NSApplication( 6965): Starting up...
I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
I/jxcore-log( 5537): Test app app.js loaded
I/jxcore-log( 5537): 
,I/ActivityManager(  865): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7035 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  865): Killing 6735:com.google.android.apps.plus/u0a86 (adj 15): empty #11
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5537): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5537): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5537): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5537): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5537): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5537): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5537): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5537): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5537): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5537): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5e76e7 added. We now have 1 listener(s)
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 21.889ms
D/BluetoothAdapterService(681627302)( 1995): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ef2022c
I/jxcore-log( 5537): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5537): 
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 22.078ms
,W/libprocessgroup(  865): failed to open /acct/uid_10086/pid_6735/cgroup.procs: No such file or directory
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.137ms
,I/chromium( 5537): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  865): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7056 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  865): Killing 6762:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10081/pid_6762/cgroup.procs: No such file or directory
,W/ResourcesManager( 7056): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  865): Killing 6791:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10021/pid_6791/cgroup.procs: No such file or directory
,I/ActivityManager(  865): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7086 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7086): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  865): Message: 20
D/BluetoothManagerService(  865): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22b65c61:true
,D/BluetoothAdapterService(681627302)( 1995): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ef2022c
D/BluetoothAdapterService(681627302)( 1995): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ef2022c
I/AudioManager( 7086): getMode name:com.lge.qremote
,I/AudioManager( 7086): getMode name:com.lge.qremote
,I/ActivityManager(  865): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7104 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 7104): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7104): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7104): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7104): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7104): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7104): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7104): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7104): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7104): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@125e8d97: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7104): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7104): GMSCore installation verified
I/ConfigStore( 7104): Config Database version: 1
,I/MediaRouter( 7104): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7104): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7104): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7104): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  865): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7132 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7104): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7104): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  865): Killing 6821:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/ResourcesManager( 7132): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7132): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7132): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  865): failed to open /acct/uid_1000/pid_6821/cgroup.procs: No such file or directory
,I/NotificationManager( 7104): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7132): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7132): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7132): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  865): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7160 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7132): JNI_OnLoad()
I/HubEmail( 7132): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/HubEmail( 7132): registerNatives()
I/HubEmail( 7132): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7132): registerNativeMethods()
I/HubEmail( 7132): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7132): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  865): Killing 6848:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10011/pid_6848/cgroup.procs: No such file or directory
W/Settings( 7132): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7160): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7160): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7160): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7160): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7160): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7160): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7160): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7160): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  865): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7187 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7160): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7160): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7160): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7160): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7160): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 7160): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  865): Killing 6880:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10038/pid_6880/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7187): onCreate
,W/AppUp4:DB( 7187):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7187):  setFingerPrint start
,I/AppUp4:DB( 7187):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7187):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7187):  SDK version = 0
I/AppUp4:DB( 7187):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7187): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7187): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7187): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 7187): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7187): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7187): onReceive
,I/AppUp4:CustModeStarterReceiver( 7187): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7187): Context : android.app.ReceiverRestrictedContext@2fd13f0b
D/AppUp4:CustFacade( 7187): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7187): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7187): begin check event
I/AppUp4:CustModeStarterReceiver( 7187): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7187): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7187): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7187): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7187): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  865): Killing 6902:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10051/pid_6902/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3177): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3177): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3177): networkInfo.isConnected() = true
,D/PhoneState( 3177): setPdpRejectCasuse : false
,I/ActivityManager(  865): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7206 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7206): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7206): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7206): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  865): Killing 6930:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7206): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7206): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7206): [parse] Load xml
V/TelephonyAutoProfiling( 7206): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7206): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7206): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  865): failed to open /acct/uid_10061/pid_6930/cgroup.procs: No such file or directory
V/DownloadManager( 3199): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3199): DownloadService onCreate
I/NotificationManager( 3199): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3199): in removeSpuriousFiles
V/DownloadManager( 3199): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@e5e4590 on behalf of 3199
,I/DownloadManager( 3199): in trimDatabase
V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@137f3e8e on behalf of 3199
I/ActivityManager(  865): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7228 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3199): DownloadService onStartCommand
,I/CheckinService( 5494): Checkin interval check for package: unspecified last checkin: 1454420771924 min interval config: 0 actual interval: 33058
V/DownloadManager( 3199): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@108a2abc on behalf of 3199
I/CheckinService( 5494): Checking schedule, now: 1454420804993 next: 1454420801886
I/CheckinService( 5494): active receiver: enabled
,I/CheckinService( 5494): Preparing to send checkin request
V/DownloadManager( 3199): DownloadService onDestroy
I/EventLogService( 5494): Accumulating logs since 1454420764303
,D/WeatherAncestor( 2715): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:46:45
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
D/WeatherAncestor( 2715): connectivity changed - connection : true
D/Weather_cast( 2715): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 2715): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:46:45
D/WeatherService( 2715): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  865): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7252 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  865): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/art     ( 5418): Explicit concurrent mark sweep GC freed 2515(97KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 366us total 33.973ms
,W/ResourcesManager( 7252): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5494): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5494): Failed to find provider info for com.google.android.wearable.settings
,V/AlarmManager(  865): RTC_WAKEUP set : Alarm{25214d93 type 0 when 1454420801886 com.google.android.gms} when 1454420801886
,I/ActivityManager(  865): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7273 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  865): RTC_WAKEUP set : Alarm{78301d0 type 0 when 1454420805367 com.android.vending} when 1454420805367
,I/art     (  865): Explicit concurrent mark sweep GC freed 15151(741KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.441ms total 149.126ms
,I/art     ( 7252): CheckpointMarkThreadRoots callback created = 0xb002d480
,I/Babel_SMS( 7252): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7252): MmsConfig.loadMmsSettings
I/Babel_SMS( 7252): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7252): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7252): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7252): MmsConfig.loadFromResources
E/Babel_SMS( 7252): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7252): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7252): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7252): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7252): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7252): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7252): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7252): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7252): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7252): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7252): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7252): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7252): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7252): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7252): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7252): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7252): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7252): found sensor: Motion Accel, handle=46
I/art     ( 7252): CheckpointMarkThreadRoots callback created = 0xb002d460
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Settings( 7252): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Finsky  ( 7273): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/Babel_Crash( 7252): startup - clean
I/Babel   ( 7252): deleted: false for 0
,I/ActivityManager(  865): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7314 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 318us total 21.643ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 297us total 20.811ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 21.380ms
,W/AudioCapabilities( 7252): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7252): Unsupported mime audio/adpcm
W/AudioCapabilities( 7252): Unsupported mime audio/g726
W/AudioCapabilities( 7252): Unsupported mime audio/x-ms-wma
,D/Finsky  ( 7273): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/AudioCapabilities( 7252): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7252): Unsupported mime video/mjpg
W/ResourcesManager( 7314): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7314): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/VideoCapabilities( 7252): Unsupported mime video/theora
,W/Settings( 7273): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7273): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/art     ( 7056): CheckpointMarkThreadRoots callback created = 0xb002d490
,I/NotificationManager( 7273): com.android.vending: cancel(-1050172287) by com.android.vending
,W/AudioCapabilities( 7252): Unsupported mime audio/evrc
I/art     ( 7056): CheckpointMarkThreadRoots callback created = 0xb002d460
,W/AudioCapabilities( 7252): Unsupported mime audio/qcelp
W/VideoCapabilities( 7252): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7252): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7252): Unsupported mime audio/qcelp
W/AudioCapabilities( 7252): Unsupported mime audio/evrc
,D/Finsky  ( 7273): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7273): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7273): Skipping gmscore version check
V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@3d34b59a on behalf of 7273
I/MultiDex( 7314): VM with version 2.1.0 has multidex support
I/MultiDex( 7314): install
I/MultiDex( 7314): VM has multidex support, MultiDex support library is disabled.
,W/VideoCapabilities( 7252): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 7252): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7252): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  865): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7348 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/VideoCapabilities( 7252): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7252): Unrecognized profile 2130706433 for video/avc
,V/LGMDMManager( 7086): Create singleton instance
,W/VideoCapabilities( 7252): Unrecognized profile 2130706433 for video/avc
,V/JNIHelp ( 7314): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/vclib   ( 7252): onServiceConnected
W/Babel   ( 7252): Attempted to change video mute state without an active call.
I/NotificationManager( 7252): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 7252): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7252): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7252): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 7252): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  281): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
D/Finsky  ( 7273): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/System.out( 7252): propertyValue:false
D/Finsky  ( 7273): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/UEI.SmartControl( 7348): Quickset Services start...
I/UEI.SmartControl( 7348): Manufacture = LGE
D/UEI.SmartControl( 7348): File observer start...
E/UEI.SmartControl( 7348): IR Port is disabled: false
D/UEI.SmartControl( 7348): Starting file observer...
D/UEI.SmartControl( 7348): Extracting JNI libs...
,D/UEI.SmartControl( 7348): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7086): getMode name:com.lge.qremote
I/Babel   ( 7252): connection state changed from UNKNOWN to CONNECTED
,D/WearableService( 1736): callingUid 10006, callindPid: 1736
,W/ActivityThread( 7314): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7314): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@c32068c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7314): Installed default security provider GmsCore_OpenSSL
E/MDM     ( 1736): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5494): Restart initialization of location
I/NotificationManager( 7314): com.google.android.gms: cancel(10436) by com.google.android.gms
D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/NotificationManager( 7314): com.google.android.gms: cancel(39789) by com.google.android.gms
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1736): com.google.android.gms: cancel(0) by com.google.android.gms
D/UEI.SmartControl( 7348): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7348): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7348): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/art     ( 7314): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7314): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  865): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7378 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UEI.SmartControl( 7348): --- Selecting new region: 2
I/UEI.SmartControl( 7348): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7348): Platform has CIR...
D/UEI.SmartControl( 7348): NO CIR support, need to check package...
W/GCoreFlp( 1736): No location to return for getLastLocation()
,W/FusedLocationProvider( 1736): location=null
I/UEI.SmartControl( 7348): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 7348): QS Service created
I/ActivityManager(  865): Process com.google.android.music:main (pid 7104) has died
,E/UEI.SmartControl( 7348): QS start get config
,D/NativeLibraryUtils( 7314): Install completed successfully. count=14 extracted=0
,D/UEI.SmartControl( 7348): Loading JNI Libs...
,D/UEI.SmartControl( 7348):  configuring local db...
D/Finsky  ( 7273): [950] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7273): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  865): Killing 7132:com.lge.email/u0a21 (adj 15): empty #11
D/WVCdm   (  285): Instantiating CDM.
,I/WVCdm   (  285): CdmEngine::OpenSession
I/WVCdm   (  285): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  285): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  285): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  285): L1 library not specified. Falling Back to L3
,I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
W/libprocessgroup(  865): failed to open /acct/uid_10021/pid_7132/cgroup.procs: No such file or directory
W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/WVCdm   (  285): PrepareKeyRequest: nonce=2180824931
D/UEI.SmartControl( 7348):  ---- Has DB8: true
,D/UEI.SmartControl( 7348): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7348): QS version = v2.7.11.1_RC1
I/Gmail   ( 7378): getAccountsCursor
D/UEI.SmartControl( 7348): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7348): IRRCDataComm has AudioManager!!!!.
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/irrc_jni( 7348): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7348): IrrcClient ++ 
D/irrcClient( 7348): getIrrcService ++ 
D/irrcClient( 7348): getIrrcService -- 
D/irrcClient( 7348): IrrcClient -- 
W/irrc_jni( 7348): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7348): Services init done
D/UEI.SmartControl( 7348): QS Service init finished
D/UEI.SmartControl( 7348): QS Service version name: 0.1.73
D/UEI.SmartControl( 7348): QS Service version code: 1073
D/UEI.SmartControl( 7348): Service requested: Control
I/UEI.SmartControl( 7348): Device manager: loading config....
D/UEI.SmartControl( 7348): Config is loaded...
W/GAV2    ( 7378): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/UEI.SmartControl( 7348):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7348): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7348): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7348): Internal service binding...
D/UEI.SmartControl( 7348): -----IControl: 11
D/UEI.SmartControl( 7348): Caller: com.lge.qremote
,D/UEI.SmartControl( 7348): ------------ IControl registerCallback...
I/UEI.SmartControl( 7348): Registering callback...
D/UEI.SmartControl( 7348): -----IControl: 19
D/UEI.SmartControl( 7348): Caller: com.lge.qremote
I/UEI.SmartControl( 7348): Registering Services Ready callback...
I/UEI.SmartControl( 7348): Notify client services are ready...
I/AudioManager( 7086): getMode name:com.lge.qremote
,W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 7378): Error finding the version of the Email provider.....
E/Gmail   ( 7378): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7378): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7378): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7378): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7378): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7378): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7378): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7378): We do not support migrating this version of the Email provider.
D/UEI.SmartControl( 7348): -----IControl: 8
,D/UEI.SmartControl( 7348): Caller: com.lge.qremote
I/ActivityManager(  865): Killing 7187:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/Gmail   ( 7378): getAccountsCursor
,I/ActivityManager(  865): Killing 7160:com.lge.lgdmsclient/1000 (adj 15): empty #12
,W/libprocessgroup(  865): failed to open /acct/uid_10011/pid_7187/cgroup.procs: No such file or directory
,W/ActivityManager(  865): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/libprocessgroup(  865): failed to open /acct/uid_1000/pid_7160/cgroup.procs: No such file or directory
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  865): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7378): Observing account changes for notifications
I/AudioManager( 7086): getMode name:com.lge.qremote
I/AudioManager( 7086): getMode name:com.lge.qremote
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 7273): [955] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/NotificationManager(  865): android: cancelAsUser(2) by android
D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 7086): getMode name:com.lge.qremote
I/WVCdm   (  285): CdmEngine::OpenSession
I/CheckinService( 5494): Checkin interval check for package: unspecified last checkin: 1454420771924 min interval config: 0 actual interval: 35457
,E/MDM     ( 1736): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1736): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5494): Restart initialization of location
V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1736): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1736): No location to return for getLastLocation()
W/FusedLocationProvider( 1736): location=null
,D/libc-netbsd( 7273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7273): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7273): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,I/AudioManager( 7086): getMode name:com.lge.qremote
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
I/ThermalEngine(  295): Sensor:pa_therm0:34000 mC
I/AudioManager( 7086): getMode name:com.lge.qremote
,W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/AudioManager( 7086): getMode name:com.lge.qremote
,I/AudioManager( 7086): getMode name:com.lge.qremote
,D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 7273): propertyValue:false
I/Gmail   ( 7378): getAccountsCursor
I/Gmail   ( 7378): notifyAccountChanged
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7378): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7378): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7378): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7378): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/art     (  865): Explicit concurrent mark sweep GC freed 23782(1038KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.779ms total 161.209ms
,I/ActivityManager(  865): Killing 7228:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/Gmail   ( 7378): getAccountsCursor
W/libprocessgroup(  865): failed to open /acct/uid_10051/pid_7228/cgroup.procs: No such file or directory
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 114848580325; DSPS: 3854739; Offset : -2801230392
,I/WVCdm   (  285): CdmEngine::CloseSession
,I/WVCdm   (  285): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  285): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  285): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  285): CdmEngine::GenerateKeyRequest
D/WVCdm   (  285): PrepareKeyRequest: nonce=3665840445
I/MusicWidget( 2637): mDelayedStopHandler : unbind
,I/MusicBrowser( 2734): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2734): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2734): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2734): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2734): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2734): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2734): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2734): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  865):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@8931518com.lge.music.MediaPlaybackService$6@1f9d7b71
,D/MusicBrowser( 2734): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2734): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2734): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2734): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2734): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@5d2c0e7
,I/MusicBrowser( 2734): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2734): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2734): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2734): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2734): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2734): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2734): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2734): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2734): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2734): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2734): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2734): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2734): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2734): reset
V/MediaPlayer[Native]( 2734): setListener
,V/MediaPlayer[Native]( 2734): disconnect
V/MediaPlayer[Native]( 2734): destructor
V/AudioFlinger(  285): releasing 19 from 2734 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/MediaPlayer[Native]( 2734): disconnect
D/MusicBrowser( 2734): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2734): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2734): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2734): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2734): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2734): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2734): [SmartShareManagerClient] unregisterListener: 470822230
W/SmartShareClient( 2734): [SmartShareManagerClient] unregisterListener invalid listener: 470822230
I/SmartShareClient( 2734): [SmartShareManagerClient] terminate service: 2734/MediaPlaybackService/719679621
,E/HomeCloudIF( 2734): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2734): [SmartShareManagerClient] unbindService context:android.app.Application@737b1d7
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/CloudHub( 2734): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2734): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2734): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer,
I/MusicBrowser( 2734): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2734): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  865): Killing 7252:com.google.android.talk/u0a61 (adj 15): empty #11
,I/CloudHub( 2734): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29977
W/libprocessgroup(  865): failed to open /acct/uid_10061/pid_7252/cgroup.procs: No such file or directory
,I/WVCdm   (  285): CdmEngine::CloseSession
,I/WVCdm   (  285): L3 Terminate.
I/art     ( 7314): CheckpointMarkThreadRoots callback created = 0xaaf43e50
,I/art     ( 7314): CheckpointMarkThreadRoots callback created = 0xaaf43e40
,I/dex2oat ( 7471): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7471): dex2oat took 97.093ms (threads: 4)
,I/Adreno-EGL( 7314): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7314): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7314): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7314): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7314): Remote Branch: 
I/Adreno-EGL( 7314): Local Patches: 
I/Adreno-EGL( 7314): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Adreno-EGL( 7314): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7314): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7314): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7314): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7314): Remote Branch: 
I/Adreno-EGL( 7314): Local Patches: 
I/Adreno-EGL( 7314): Reconstruct Branch: 
,I/Adreno-EGL( 7314): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7314): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7314): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7314): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7314): Remote Branch: 
I/Adreno-EGL( 7314): Local Patches: 
I/Adreno-EGL( 7314): Reconstruct Branch: 
,D/UEI.SmartControl( 7348): Internal timer expired: 1
,I/GAV2    ( 7378): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 5494): Google Analytics 8.4.89 is starting up.
,I/CheckinRequestBuilder( 5494): Classify the device as Phone.
,D/libc-netbsd( 5494): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5494): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5494): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5494): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 5494): propertyValue:false
D/libc-netbsd( 5494): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5494): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5494): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5494): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5494): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5494): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5494): Sending checkin request (9766 bytes)
,I/ThermalEngine(  295): Sensor:pa_therm0:34000 mC
,I/CheckinRequestBuilder( 5494): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5494): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5494): Classify the device as Phone.
,I/CheckinTask( 5494): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5494): Checking schedule, now: 1454420813023 next: 1454948062018
I/CheckinService( 5494): active receiver: disabled
,I/CheckinService( 5494): Checking schedule, now: 1454420813057 next: 1454948062018
I/CheckinService( 5494): active receiver: disabled
,D/CheckinService( 5494): Recording last checkin time for package unspecified as 1454420813066
,I/ActivityManager(  865): Killing 6965:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10079/pid_6965/cgroup.procs: No such file or directory
,V/SetupWizard( 7206): Connected to Gservices successfully
,I/ActivityManager(  865): Killing 7035:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10048/pid_7035/cgroup.procs: No such file or directory
,D/GCM     ( 1736): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/QCNEJ   ( 1843): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  865): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  865): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7518 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms,
,D/administrator(  865): Handling package changes for user 0
I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
W/ResourcesManager( 7518): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationService(  865): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  865): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  865): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  865): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  865): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  865): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@125856e0
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ResourcesManager(  865): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Babel_SMS( 7518): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7518): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7518): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7518): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7518): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7518): MmsConfig.loadFromResources
E/Babel_SMS( 7518): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7518): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/LCardEmulationManager( 1790): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1790): getDefaultRoute
D/SensorManager( 7518): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7518): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7518): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 7518): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7518): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7518): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7518): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7518): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7518): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7518): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7518): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7518): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7518): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7518): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7518): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7518): found sensor: Motion Accel, handle=46
,W/Settings( 7518): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7518): startup - clean
,I/art     ( 7518): CheckpointMarkThreadRoots callback created = 0xb002d8c0
,W/ResourceType(  865): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/Babel   ( 7518): deleted: false for 0
,I/art     ( 7518): CheckpointMarkThreadRoots callback created = 0xb002d8a0
,I/ActivityManager(  865): Process com.google.android.apps.plus (pid 7056) has died
,I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1736): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/AudioCapabilities( 7518): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7518): Unsupported mime audio/adpcm
W/AudioCapabilities( 7518): Unsupported mime audio/g726
W/AudioCapabilities( 7518): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7518): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7518): Unsupported mime video/mjpg
W/VideoCapabilities( 7518): Unsupported mime video/theora
,I/ActivityManager(  865): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7556 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LocationProviderProxy(  865): applying state to connected service
W/AudioCapabilities( 7518): Unsupported mime audio/evrc
,W/AudioCapabilities( 7518): Unsupported mime audio/qcelp
,W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7518): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7518): Unsupported mime audio/qcelp
W/AudioCapabilities( 7518): Unsupported mime audio/evrc
W/VideoCapabilities( 7518): Unsupported mime video/mp4v-esdp
I/AppUp4:AppBoxCP( 7556): onCreate
,W/AppUp4:DB( 7556):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7556):  setFingerPrint start
I/AppUp4:DB( 7556):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/VideoCapabilities( 7518): Unsupported profile 4 for video/mp4v-es
I/AppUp4:DB( 7556):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7556):  SDK version = 0
,I/AppUp4:DB( 7556):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7556): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7556): onReceive
I/AppUp4:CustModeStarterReceiver( 7556): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 7556): Context : android.app.ReceiverRestrictedContext@3d6421fc
D/AppUp4:CustFacade( 7556): isCustomizationCompleted : false
,W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 7556): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7556): begin check event
I/AppUp4:CustModeStarterReceiver( 7556): Event For Nothing, skip.
W/VideoCapabilities( 7518): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  865): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7575 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationManager( 7518): com.google.android.talk: cancel(8) by com.google.android.talk
I/vclib   ( 7518): onServiceConnected
W/Babel   ( 7518): Attempted to change video mute state without an active call.
W/ResourcesManager( 7575): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7575): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7575): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/ResourcesManager( 7518): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7518): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7518): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7518): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7518): Installed default security provider GmsCore_OpenSSL
I/AppConfig( 7575): Total System Memory = 906309632
I/GalleryUtils( 7575): Application Heap = 96 MB
I/AppConfig( 7575): App Tier : NOT_DEF
I/NotificationManager( 7518): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/SystemHelper( 7575): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  865): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7602 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  865): Killing 7273:com.android.vending/u0a36 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/libprocessgroup(  865): failed to open /acct/uid_10036/pid_7273/cgroup.procs: No such file or directory
,W/ResourcesManager( 7602): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7602): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7602): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7602): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7602): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7602): BUILD Country: EU
I/SystemConfig( 7602): BUILD Operator: OPEN
,I/ActivityManager(  865): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7621 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  865): Killing 7378:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  865): failed to open /acct/uid_10053/pid_7378/cgroup.procs: No such file or directory
,I/SystemConfig( 7602): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7602): existFile = false
I/SystemConfig( 7602): canReadFile = false
I/SystemConfig( 7602): systemFeature RCS result false
D/SystemConfig( 7602): refreshRcsSupport() :false
I/LockScreenSettings( 7621): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7621): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7621): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7621): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7621): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7621): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  865): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7641 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  865): Killing 2734:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  285): 2734 died, releasing its sessions
V/AudioFlinger(  285):  pid 1751 @ 0
,V/AudioFlinger(  285):  pid 3177 @ 1
V/AudioFlinger(  285):  pid 3177 @ 2
,W/libprocessgroup(  865): failed to open /acct/uid_10028/pid_2734/cgroup.procs: No such file or directory
,W/ResourcesManager( 7641): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1947): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  865): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7666 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1947): UpdateCorporaTask done [took 62 ms] updated apps [took 62 ms] 
,I/art     ( 5418): Explicit concurrent mark sweep GC freed 3354(136KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 482us total 30.643ms
I/ActivityManager(  865): Killing 7348:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7086): android.os.DeadObjectException
,W/System.err( 7086): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7086): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7086): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7086): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7086): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7086): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7086): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7086): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7086): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7086): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7086): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7086): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7086): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7086): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7086): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7086): android.os.DeadObjectException
W/System.err( 7086): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7086): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7086): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7086): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7086): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7086): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7086): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7086): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7086): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7086): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7086): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7086): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7086): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7086): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7086): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/ThermalEngine(  295): Sensor:pa_therm0:34000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  865): failed to open /acct/uid_10089/pid_7348/cgroup.procs: No such file or directory
W/ActivityManager(  865): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  865): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7688 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7688): Quickset Services start...
I/UEI.SmartControl( 7688): Manufacture = LGE
D/UEI.SmartControl( 7688): File observer start...
E/UEI.SmartControl( 7688): IR Port is disabled: false
,D/UEI.SmartControl( 7688): Starting file observer...
D/UEI.SmartControl( 7688): Extracting JNI libs...
D/UEI.SmartControl( 7688): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7688): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7688): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7688): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7688): --- Selecting new region: 2
I/UEI.SmartControl( 7688): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7688): Platform has CIR...
D/UEI.SmartControl( 7688): NO CIR support, need to check package...
I/UEI.SmartControl( 7688): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7688): QS Service created
I/art     (  865): Explicit concurrent mark sweep GC freed 24101(1257KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 1.734ms total 150.738ms
,E/UEI.SmartControl( 7688): QS start get config
,D/Finsky  ( 7666): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 7688): Loading JNI Libs...
,D/UEI.SmartControl( 7688):  configuring local db...
,D/Finsky  ( 7666): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/UEI.SmartControl( 7688):  ---- Has DB8: true
,W/Settings( 7666): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7666): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7666): com.android.vending: cancel(-1050172287) by com.android.vending
D/UEI.SmartControl( 7688): QS start statue = true Error code = 0
D/UEI.SmartControl( 7688): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7688): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7688): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7688): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7688): IrrcClient ++ 
D/irrcClient( 7688): getIrrcService ++ 
D/irrcClient( 7688): getIrrcService -- 
D/irrcClient( 7688): IrrcClient -- 
W/irrc_jni( 7688): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7688): Services init done
,I/UEI.SmartControl( 7688): Device manager: loading config....
D/UEI.SmartControl( 7688): QS Service init finished
,D/UEI.SmartControl( 7688): QS Service version name: 0.1.73
D/UEI.SmartControl( 7688): QS Service version code: 1073
D/UEI.SmartControl( 7688): Config is loaded...
V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/UEI.SmartControl( 7688): Service requested: Control
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@2de26ecb on behalf of 7666
D/UEI.SmartControl( 7688): -----IControl: 11
D/UEI.SmartControl( 7688): Caller: com.lge.qremote
D/UEI.SmartControl( 7688): Internal service binding...
D/UEI.SmartControl( 7688): ------------ IControl registerCallback...
I/UEI.SmartControl( 7688): Registering callback...
D/UEI.SmartControl( 7688): -----IControl: 19
D/UEI.SmartControl( 7688): Caller: com.lge.qremote
,I/UEI.SmartControl( 7688): Registering Services Ready callback...
,I/UEI.SmartControl( 7688): Notify client services are ready...
D/Finsky  ( 7666): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 7666): Skipping gmscore version check
D/UEI.SmartControl( 7688): -----IControl: 8
D/Finsky  ( 7666): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  865): Killing 7086:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7688): Caller: com.lge.qremote
D/UEI.SmartControl( 7688):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7688): Notify AllClients services are ready: 0
W/libprocessgroup(  865): failed to open /acct/uid_10106/pid_7086/cgroup.procs: No such file or directory
,I/ActivityManager(  865): Killing 7206:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10038/pid_7206/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 5494): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Finsky  ( 7666): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/PackageBroadcastService( 5494): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5494): updateResources: need to parse f{com.google.android.gms}
D/Finsky  ( 7666): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 5494): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5494): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/PowerManagerServiceEx(  865): acquireWakeLockInternal: lock=570722295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=865
,D/WeatherService( 2715): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:47:0
,D/WeatherService( 2715): 2 : TimeTick Intent And Screen On
D/WeatherService( 2715): 2 : SDK version : 21
W/ActivityManager(  865): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2715): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
D/WeatherService( 2715): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2715): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2715): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2715): 2 : Fixed theme : optimus
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
D/WeatherReflect( 2715): 2 : Map key string is -2
,I/[SystemUI]Clock( 1375): called onTimeUpdated()
I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/lim     ( 2715): 2 : time = 14:47
,I/WeatherReflect( 2715): Model Name : LG-D722
D/WeatherTheme( 2715): 2 : Different view - status_min_formatted : 46 != 47
D/WeatherTheme( 2715): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2715): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2715): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/Weather4x2_optimus( 2715): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2715): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2715): forecast size is 0
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2715): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2715): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2715): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2715): url is : null
,D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2715): 2 : update view, appWidgetId: 2
D/WeatherService( 2715): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:47:0
D/PowerManagerServiceEx(  865): releaseWakeLockInternal: lock=570722295 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 304, mChargingStatus=5, mChargingStop=false
D/charger_monitor(  483): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 304
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1995): Disconnected process message: 10, size: 0
,D/WifiController(  865): battery changed pluggedType: 2
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 304
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,I/ActivityManager(  865): Killing 7314:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  865): failed to open /acct/uid_10006/pid_7314/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:34000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7688): Internal timer expired: 1
,D/UEI.SmartControl( 7688): Service.onUnbind: IControl
D/UEI.SmartControl( 7688): Service.onDestroy
W/System.err( 7688): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@28a0cea6
W/System.err( 7688): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7688): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7688): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7688): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7688): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7688): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7688): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7688): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7688): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7688): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7688): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7688): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7688): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7688): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7688): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7688): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@28a0cea6
D/UEI.SmartControl( 7688): Shutdown IRRCPlayer... 
,W/irrc_jni( 7688): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7688): ~IrrcClient ++ 
D/irrcClient( 7688): ~IrrcClient -- 
W/irrc_jni( 7688): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7688): Blaster closed
D/UEI.SmartControl( 7688): Blaster closed
D/UEI.SmartControl( 7688): Shut down QS...
D/UEI.SmartControl( 7688): Stopped file observer...
I/UEI.SmartControl( 7688): QS lib stop result = true
D/UEI.SmartControl( 7688): QS shutdown complete
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 134849823650; DSPS: 4510140; Offset : -2801238080
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{3d655664 type 2 when 145339 com.google.android.gms} when 145339
,I/art     ( 1736): Explicit concurrent mark sweep GC freed 32806(2MB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 13MB/22MB, paused 1.689ms total 99.915ms
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1736): Vacuum at: now=1454420839465 tag=VacuumService
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PhenotypeConfigurator( 1736): Scheduling Phenotype for one-off execution 7718 seconds from now (1454420839910)
,D/GetConfigurationSnapshotOperation( 1736): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1736): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1736): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  865): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  281): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  281): res_queryN name = xxxxx succeed
I/System.out( 1736): propertyValue:false
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1736): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1736): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  865): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  865): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  865): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1736): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  865): ALS enabled for SRE
,D/PowerManagerServiceEx(  865): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29775 ms ago)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/qdlights(  865): set_light_backlight: 252
,D/qdlights(  865): set_light_backlight: 249
D/qdlights(  865): set_light_backlight: 246
,D/qdlights(  865): set_light_backlight: 242
,D/qdlights(  865): set_light_backlight: 239
,D/qdlights(  865): set_light_backlight: 236
,D/qdlights(  865): set_light_backlight: 232
,D/qdlights(  865): set_light_backlight: 229
,D/qdlights(  865): set_light_backlight: 226
,D/qdlights(  865): set_light_backlight: 222
,D/qdlights(  865): set_light_backlight: 219
,D/qdlights(  865): set_light_backlight: 216
,D/qdlights(  865): set_light_backlight: 212
,D/qdlights(  865): set_light_backlight: 209
,D/qdlights(  865): set_light_backlight: 206
,D/qdlights(  865): set_light_backlight: 202
,D/qdlights(  865): set_light_backlight: 199
,D/qdlights(  865): set_light_backlight: 196
,D/qdlights(  865): set_light_backlight: 192
,D/qdlights(  865): set_light_backlight: 189
,D/qdlights(  865): set_light_backlight: 186
,D/qdlights(  865): set_light_backlight: 182
,D/qdlights(  865): set_light_backlight: 179
,D/qdlights(  865): set_light_backlight: 176
,D/qdlights(  865): set_light_backlight: 172
,D/qdlights(  865): set_light_backlight: 169
,D/qdlights(  865): set_light_backlight: 166
,D/qdlights(  865): set_light_backlight: 162
,D/qdlights(  865): set_light_backlight: 159
,D/qdlights(  865): set_light_backlight: 156
,D/qdlights(  865): set_light_backlight: 152
,D/qdlights(  865): set_light_backlight: 149
,D/qdlights(  865): set_light_backlight: 146
,D/qdlights(  865): set_light_backlight: 142
,D/qdlights(  865): set_light_backlight: 139
,D/qdlights(  865): set_light_backlight: 136
,D/qdlights(  865): set_light_backlight: 132
,D/qdlights(  865): set_light_backlight: 129
,D/qdlights(  865): set_light_backlight: 126
,D/qdlights(  865): set_light_backlight: 122
,D/qdlights(  865): set_light_backlight: 119
,D/qdlights(  865): set_light_backlight: 116
,D/qdlights(  865): set_light_backlight: 112
,D/qdlights(  865): set_light_backlight: 109
,D/qdlights(  865): set_light_backlight: 106
,D/qdlights(  865): set_light_backlight: 102
,D/qdlights(  865): set_light_backlight: 99
,D/qdlights(  865): set_light_backlight: 96
,D/qdlights(  865): set_light_backlight: 92
,D/qdlights(  865): set_light_backlight: 89
,D/qdlights(  865): set_light_backlight: 86
,D/qdlights(  865): set_light_backlight: 82
,D/qdlights(  865): set_light_backlight: 79
,D/qdlights(  865): set_light_backlight: 76
,D/qdlights(  865): set_light_backlight: 72
,D/qdlights(  865): set_light_backlight: 69
,D/qdlights(  865): set_light_backlight: 66
,D/qdlights(  865): set_light_backlight: 62
,D/qdlights(  865): set_light_backlight: 59
,D/qdlights(  865): set_light_backlight: 56
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  865): set_light_backlight: 52
,D/qdlights(  865): set_light_backlight: 49
,D/qdlights(  865): set_light_backlight: 46
,D/qdlights(  865): set_light_backlight: 42
,D/qdlights(  865): set_light_backlight: 39
,D/qdlights(  865): set_light_backlight: 36
,D/qdlights(  865): set_light_backlight: 32
,D/qdlights(  865): set_light_backlight: 29
,D/qdlights(  865): set_light_backlight: 26
,D/qdlights(  865): set_light_backlight: 22
,D/qdlights(  865): set_light_backlight: 19
,D/qdlights(  865): set_light_backlight: 16
,D/qdlights(  865): set_light_backlight: 12
,D/qdlights(  865): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 154850786352; DSPS: 5165531; Offset : -2801221604
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  865): ALS enabled for SRE
D/PowerManagerServiceEx(  865): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36761 ms ago)
I/PowerManagerService(  865): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  865): ALS enabled for SRE
D/PowerManagerServiceEx(  865): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36781 ms ago)
W/ContextImpl(  865): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  865): Sleeping (uid 1000)...
D/LPWGController(  865): [updateScreenState] screen on = false
D/LPWGController(  865): disable proximity sensor
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/LPWGController(  865): enable proximity sensor
I/SensorManager(  865): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2ae3ee2c] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  865): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  865): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  865): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  865): activate: handle is 48, enable
,V/sensors_hal_Ctx(  865): activate sensors is 1400000000000
D/sensors_hal_Thresh(  865): enable: handle=48
I/sensors_hal_SAM(  865): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  865): waitForResponse: timeout=1000
V/sensors_hal_SAM(  865): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  865): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  865): enable: Received response: 0
D/PowerManagerServiceEx(  865): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36875 ms ago)
I/Adreno-EGL(  865): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  865): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  865): Build Date: 03/02/15 Mon
I/Adreno-EGL(  865): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  865): Remote Branch: 
I/Adreno-EGL(  865): Local Patches: 
I/Adreno-EGL(  865): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1080 us)
,I/Sensors (  412): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  865): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  865): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  865): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  865): processInd: handle 48, count=1
V/sensors_hal_Thresh(  865): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  865): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  865): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  865): poll: count: 256
I/sensors_hal_Ctx(  865): poll: released wakelock sensor_ind
D/sensors_hal_Util(  865): waitForResponse: timeout=0
,D/LPWGController(  865): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  865): current mode = 1  value = 1 1
,I/LPWGController(  865): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
,I/LPWGController(  865): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  865): set_light_backlight: 0
,I/SensorManager(  865): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  865): activate: handle is 46, disable
V/sensors_hal_Ctx(  865): activate sensors is 1000000000000
D/sensors_hal_LP2(  865): enable: handle=46
D/sensors_hal_LP2(  865): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  865): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  865): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  865): Display changed displayId=0
,V/sensors_hal_SAM(  865): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  865): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1751): Display #0 changed.
D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  865): Excessive delay in setPowerMode(): 204ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  865): Got set_interactive hint
,D/KeyguardViewMediator( 1375): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1335): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1375): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1335): notifyScreenOffLocked
D/SmartCoverViewMediator( 1335): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1375): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1375): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1375): unregisterProximitySensor
,D/StatusBarWindowView( 1375): onScreenTurnedOff why = 3
D/WifiServerServiceExt(  865): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=on, calling pid 865
I/WifiServerServiceExt(  865): set CMD_KT_SCAN_INTERVAL
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=on
V/voice   (  285): voice_set_parameters: enter: screen_state=on
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  285): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/GpsLocationProvider(  865): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1843): |CORE| sendScreenState: state:true
I/LEDService( 1807): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1807): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/LEDService( 1807): stopPatternFlashing()
D/Cliptray Service( 1807): lockStatus = 0
D/LNfcService( 1790): action : android.intent.action.SCREEN_ON
D/qdlights( 1807): set_light_notifications: 0,0,0,0,3
I/LEDService( 1807): getCurrentHighestLGLedRecord : size = 1
,D/qdlights( 1807): set_light_notifications: 0,0,0,0,3
I/LEDService( 1807): updateLightsLocked : turn off led
D/qdlights( 1807): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1807): RESTART MSG
,D/NfcServiceNXP( 1790): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1790): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1790): isRequireNfcCRouting() return true
D/LNfcService( 1790): isHCERoutingtoHost() return : true
D/NfcService( 1790): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1790): mEnableLPD: true
D/NfcService( 1790): mEnableReader: false
D/NfcService( 1790): mEnableHostRouting: true
,D/NfcService( 1790): newParams.techmask= mTechMask: default
D/NfcService( 1790): mEnableLPD: true
D/NfcService( 1790): mEnableReader: false
D/NfcService( 1790): mEnableHostRouting: true
D/NfcService( 1790): screenState= 3
D/NfcService( 1790): Discovery configuration equal, not updating.
D/SplitWindow(  865): check instance of lgWin Window{288fdcfb u0 SearchPanel}
,D/InputDispatcher(  865): Window went away: Window{1b010d90 u0 SearchPanel}
,I/[SystemUI]Clock( 1375): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
,D/Ulp_jni (  865): JNI:system_update. Event-0
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2715): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:47:32
,D/WeatherService( 2715): 2 : ACTION screen on
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2715): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2715): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:47:32
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): ACTION_SCREEN_ON
,D/AppCleanupService( 4093): android.intent.action.SCREEN_ON
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=off, calling pid 865
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
V/voice   (  285): voice_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  285): voice_extn_compress_voip_set_parameters: exit
V/voice   (  285): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  285): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  285): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  285): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  285): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  285): adev_set_parameters: exit with code(0)
D/WifiController(  865): CMD_SCREEN_OFF 
D/WifiController(  865): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  865): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1843): |CORE| sendScreenState: state:false
,I/LEDService( 1807): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1807): stopPatternFlashing()
D/qdlights( 1807): set_light_notifications: 0,0,0,0,3
I/LEDService( 1807): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1807): set_light_notifications: 0,0,0,0,3
I/LEDService( 1807): updateLightsLocked : turn on led
E/LEDService( 1807): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1807): Can't handle this request of patternId:0
D/LEDHandler( 1807): RESTART MSG
D/VolumeVibrator( 1807): clear
I/Cliptray Service( 1807): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1790): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1790): mScreenState : 1, mInProvisionMode : false
,I/Sensors (  412): sns_pwr.c(301):releasing wakelock
I/[LGHome]EVENT( 1881): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2715): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:47:32
D/WeatherService( 2715): 2 : ACTION screen off
D/WeatherService( 2715): 2 : TimeTick Receiver Unregister
D/WeatherService( 2715): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:47:32
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  865): ACTION_SCREEN_OFF
,D/AppCleanupService( 4093): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4093): AppUsageStatsSaveTask
,E/NxpNfcJni( 1790): getReconnectState = 0x0
,D/LCardEmulationManager( 1790): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1790): getDefaultRoute
D/LNfcService( 1790): isRequireNfcCRouting() return true
D/LNfcService( 1790): isHCERoutingtoHost() return : true
D/NfcService( 1790): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1790): mEnableLPD: true
D/NfcService( 1790): mEnableReader: false
D/NfcService( 1790): mEnableHostRouting: true
D/NfcService( 1790): newParams.techmask= mTechMask: 0
D/NfcService( 1790): mEnableLPD: true
D/NfcService( 1790): mEnableReader: false
D/NfcService( 1790): mEnableHostRouting: true
D/NfcService( 1790): screenState= 1
I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,E/NxpNfcJni( 1790): getReconnectState = 0x0
,D/KeyguardViewMediator( 1375): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{3fb7c118 type 2 when 162701 com.android.systemui} when 162701
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1751): getCallState : 0
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1375): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1375): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:33000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 174851517125; DSPS: 5820915; Offset : -2801223436
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{ea2b771 type 2 when 184173 android} when 184173
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
,I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 300, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1995): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  865): battery changed pluggedType: 2
D/PowerManagerServiceEx(  865): acquireWakeLockInternal: lock=570722295, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=865
,V/AlarmManager(  865): ELAPSED_WAKEUP set : Alarm{2192b956 type 2 when 188645 com.google.android.gms} when 188645
D/PowerManagerServiceEx(  865): releaseWakeLockInternal: lock=570722295 [*alarm*], flags=0x0
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 194852317690; DSPS: 6476301; Offset : -2801215573
,I/ClearcutLoggerApiImpl( 1736): disconnect managed GoogleApiClient
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 214853053048; DSPS: 7131686; Offset : -2801243701
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 234853800071; DSPS: 7787070; Offset : -2801229386
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/HeadsetStateMachine( 1995): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 297, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  865): battery changed pluggedType: 2
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 254854469699; DSPS: 8442452; Offset : -2801230547
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 274855213076; DSPS: 9097836; Offset : -2801219565
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/PowerService( 1807): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1995): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/QCNEJ   ( 1843): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1843): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1807): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1807): Battery Level Remaining: 100%
D/LEDHandler( 1807): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  865): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  865): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  865): battery changed pluggedType: 2
I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  295): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  865): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  865): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  865): tsOffsetIs: Apps: 294856028173; DSPS: 9753223; Offset : -2801228313
,I/jxcore-log( 5537): --= Surplus to requirements =--
I/jxcore-log( 5537): 
I/jxcore-log( 5537): ****TEST TOOK:  ms ****
I/jxcore-log( 5537): 
I/jxcore-log( 5537): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5537): 
,D/AndroidRuntime( 7883): 
D/AndroidRuntime( 7883): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7883): CheckJNI is OFF
,D/AndroidRuntime( 7883): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  865): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  865): Killing 5537:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  865): WIN DEATH: Window{4b45bed u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/PackageSettings(  865): Skipping PackageSetting{3fc032dc com.example.hello/10317} due to missing metadata
D/InputDispatcher(  865): Focus left window: Window{4b45bed u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  865): Window went away: Window{4b45bed u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  865):   Force finishing activity ActivityRecord{32f244ba u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  865): Display changed displayId=0
D/DSDPConnection( 1751): Display #0 changed.
W/ActivityManager(  865): Spurious death for ProcessRecord{2e754dd7 5537:com.test.thalitest/u0a316}, curProc for 5537: null
,I/ActivityManager(  865): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  865):   Force finishing activity ActivityRecord{32f244ba u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  865): Duplicate finish request for ActivityRecord{32f244ba u0 com.test.thalitest/.MainActivity t222 f}
,I/[LGHome]EVENT( 1881): [Launcher.java:5203:onStart()]onStart
I/art     ( 1947): Explicit concurrent mark sweep GC freed 21851(1367KB) AllocSpace objects, 4(95KB) LOS objects, 39% free, 12MB/20MB, paused 3.690ms total 82.380ms
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/art     ( 5494): Explicit concurrent mark sweep GC freed 23384(1348KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 13MB/18MB, paused 791us total 88.687ms
,I/QCNEJ   ( 1843): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  865): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1736): Ignoring removeGeofence because network location is disabled.
,I/[LGHome]EVENT( 1881): [Launcher.java:776:onResume()]onResume
W/System.err( 3602): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 3602): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,W/System.err( 3602): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3602): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3602): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3602): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3602): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3602): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3602): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3602): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3602): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3602): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  865): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7915 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 25.400ms
,D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1375): createShortcutInfo...
,I/[LGHome]EVENT( 1881): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_REMOVED
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 427us total 24.467ms
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1881): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/[LGHome]EVENT( 1881): [Launcher.java:929:onResume()]onResume end
I/Activity( 1881): Activity.onPostResume() called 
,I/art     (  865): Explicit concurrent mark sweep GC freed 52003(2MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/35MB, paused 3.867ms total 216.470ms
I/art     (  865): WaitForGcToComplete blocked for 19.591ms for cause Explicit
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1881): [Launcher.java:986:onPause()]onPause
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 24.158ms
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1881): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1881): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,I/SystemUI[Framework](  865): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  865): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  865): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  865): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  865): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d329440,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  865): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  865): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  865): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  865): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  865): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  865): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d329440,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  865): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  865): Focus entered window: Window{13f1480a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1375): handleShortcutListChanged...
I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1881): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
D/administrator(  865): Handling package changes for user 0
I/[LGHome]EVENT( 1881): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]EVENT( 1881): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1881): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1375): handleShortcutListChanged...
,W/ResourcesManager( 7915): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7915): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7915): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/InputMethodManagerService(  865): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/LGEmail ( 7915): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/InputMethodManagerService(  865): Got RemoteException sending setActive(false) notification to pid 5537 uid 10316
D/LGEmail ( 7915): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/art     (  865): Explicit concurrent mark sweep GC freed 7365(404KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 16.063ms total 317.857ms
,I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/Timeline(  865): Timeline: Activity_windows_visible id: ActivityRecord{95f7320 u0 com.lge.launcher2/.Launcher t221} time:297544
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/IInputConnectionWrapper( 1881): getTextBeforeCursor on inactive InputConnection
,I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1637): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1881): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1881): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1881): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
I/NotificationService(  865): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  865): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  865): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
D/TaskPersister(  865): removeObsoleteFile: deleting file=222_task.xml
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1881): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,D/AndroidRuntime( 7883): Shutting down VM
D/LCardEmulationManager( 1790): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1790): getDefaultRoute
,I/PackageChangeReceiver( 7915): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,D/AppUp4:PreloadHelper( 7556): added Exclude : com.test.thalitest
,W/ResourcesManager(  865): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  865): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7942 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  865): Killing 7575:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/ResourceType(  865): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1881): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  865): failed to open /acct/uid_10023/pid_7575/cgroup.procs: No such file or directory
,I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]EVENT( 1881): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1881): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1881): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1881): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/SharedPreferencesImpl( 1881): Couldn't rename file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml to backup file /data/user/0/com.lge.launcher2/shared_prefs/broadcast.numberbadge.counter.xml.bak

```
