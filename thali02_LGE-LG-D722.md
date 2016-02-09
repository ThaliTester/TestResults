#### Test 587523534d3a10e_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/NotificationManager( 3804): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3804): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3804): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3804): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3804): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3804): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3804): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3804): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
--------- beginning of system
I/ActivityManager(  936): Killing 4273:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  936): failed to open /acct/uid_10006/pid_4273/cgroup.procs: No such file or directory
V/AlarmManager(  936): ELAPSED_WAKEUP set : Alarm{3c4fc762 type 2 when 80512 android} when 80512
,D/AlarmScheduler( 3804): No events found starting within 1 week.
I/ActivityManager(  936): Killing 5276:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  936): failed to open /acct/uid_10009/pid_5276/cgroup.procs: No such file or directory
I/ActivityManager(  936): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5520 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/UpdateIcingCorporaServi( 1934): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 1934): UpdateCorporaTask done [took 156 ms] updated apps [took 156 ms] 
D/AndroidRuntime( 5511): 
D/AndroidRuntime( 5511): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5511): CheckJNI is OFF
D/Finsky  ( 5520): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/AndroidRuntime( 5511): Calling main entry com.android.commands.am.Am
I/ActivityManager(  936): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  936): setTaskToReturnTo : TaskRecord{33e6f7ae #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  936): setTaskToReturnTo : TaskRecord{33e6f7ae #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  936): AppWindowTokenEx init.. 
D/ContextHelper(  936): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  936): Focus left window: Window{23e39334 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/AndroidRuntime( 5511): Shutting down VM
D/SplitWindow(  936): check instance of lgWin Window{3f7a26c8 u0 Starting com.test.thalitest}
I/ActivityManager(  936): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5571 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/Finsky  ( 5520): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
W/Settings( 5520): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5520): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/HotwordDetector( 1934): Closing mic
I/NotificationManager( 5520): com.android.vending: cancel(-1050172287) by com.android.vending
I/WindowStateAnimator(  936): Starting window displayed
I/MicrophoneInputStream( 1934): mic_close com.google.android.apps.gsa.speech.audio.u@12f04247
V/AudioRecord( 1934): stop()
D/AudioRecord( 1934): AudioRecord->stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
I/SystemUI[Framework](  936): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/AudioFlinger(  278): Record stopped OK
V/AudioPolicyManager(  278): stopInput() input 17
V/AudioPolicyService(  278): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  278): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  278): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  278): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  278): ThreadBase::setParameters() routing=0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb4318000
D/audio_hw_primary(  278): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
W/PhoneWindowManagerEx(  936): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  936): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  936): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  936): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3341c5ef,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  936): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1371): draw background and invalidate : color = 13000000
D/BarTransitions( 1371): draw background and invalidate : color = 18171717
V/audio_hw_primary(  278): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  278): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  278): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  278): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  278): disable_audio_route: exit
E/audio_hw_primary(  278): disable_snd_device: enter 144
D/hardware_info(  278): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  278): disable_snd_device: snd_device(144: lg-vr-handset-mic)
,V/audio_hw_primary(  278): stop_input_stream: exit: status(0)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioPolicyManager(  278): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  278): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  278): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  278): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioPolicyService(  278): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  278): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  278): setParameters(): io 17, keyvalue hotword_active=0, calling pid 278
V/AudioFlinger(  278): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  278): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  278): in_set_parameters: exit: status(0)
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb4318000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioRecord( 1934): stop()
V/AudioRecord( 1934): stop()
V/AudioRecord( 1934): stop()
V/AudioFlinger(  278): releasing 16 from 1934 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioPolicyManager(  278): releaseInput() 17
V/AudioPolicyManager(  278): closeInput(17)
V/AudioFlinger(  278): closeInput() 17
V/AudioSystem(  278): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): ThreadBase::exit
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioFlinger(  278): RecordThread 0xb4318000 exiting
V/AudioSystem(  936): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  278): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  278): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioSystem( 3173): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1748): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2719): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1977): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1934): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyManager(  278): releaseInput() exit
V/AudioSystem( 1371): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  278): removeClient_l() pid 1934, calling pid 278
I/HotwordRecognitionRnr( 1934): Hotword detection finished
I/HotwordRecognitionRnr( 1934): Stopping hotword detection.
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@e2ff1c1 on behalf of 5520
I/NotificationManager( 5520): com.android.vending: cancel(1003285959) by com.android.vending
D/Finsky  ( 5520): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Ads     ( 5520): Skipping gmscore version check
D/Finsky  ( 5520): [1] Libraries$2.run: Finished loading 1 libraries.
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  936): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5606 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/ContextHelper( 5571): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/Finsky  ( 5520): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 5520): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5520): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  936): Killing 5298:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  936): failed to open /acct/uid_10011/pid_5298/cgroup.procs: No such file or directory
W/ResourcesManager( 5606): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5606): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/WebViewFactory( 5571): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/MultiDex( 5606): VM with version 2.1.0 has multidex support
I/MultiDex( 5606): install
I/MultiDex( 5606): VM has multidex support, MultiDex support library is disabled.
I/LibraryLoader( 5571): Time to load native libraries: 5 ms (timestamps 2138-2143)
I/LibraryLoader( 5571): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5571): Binding Chromium to main looper Looper (main, tid 1) {3403eb30}
I/LibraryLoader( 5571): Expected native library version number "",actual native library version number ""
I/chromium( 5571): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5571): Initializing chromium process, singleProcess=true
W/art     ( 5571): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5571): ApplicationContext is null in ApplicationStatus
W/chromium( 5571): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5571): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5571): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5571): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5571): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5571): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5571): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5571): Remote Branch: 
I/Adreno-EGL( 5571): Local Patches: 
I/Adreno-EGL( 5571): Reconstruct Branch: 
V/JNIHelp ( 5606): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
V/AudioPolicyService(  278): registerClient() client 0xb4027140, uid 10316
,D/BluetoothManagerService(  936): Message: 20
D/BluetoothManagerService(  936): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@299fe810:true
,D/BluetoothAdapterService(527731292)( 1977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7164a92
W/ActivityThread( 5606): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5606): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@24b12508: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5606): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5606): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5606): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5606): Reading stored module config
,D/PackageBroadcastService( 5606): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 5606): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5606): Loading module APK com.google.android.play.games
,W/art     ( 5571): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5571): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 5571): CordovaWebView is running on device made by: LGE
,W/art     ( 5571): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5571): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5606): Suspending all threads took: 5.553ms
,I/Activity( 5571): Activity.onPostResume() called 
,D/OpenGLRenderer( 5571): Render dirty regions requested: true
I/OpenGLRenderer( 5571): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5571): Enabling debug mode 0
D/Atlas   ( 5571): Validating map...
,D/SplitWindow(  936): check instance of lgWin Window{f4ac58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5571): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/NativeLibraryUtils( 5606): Install completed successfully. count=14 extracted=0
,D/InputDispatcher(  936): Focus entered window: Window{f4ac58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/art     ( 5606): CheckpointMarkThreadRoots callback created = 0xb042d3b0
,W/InputMethodManagerService(  936): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/art     ( 5606): CheckpointMarkThreadRoots callback created = 0xb042d390
I/ActivityManager(  936): Displayed com.test.thalitest/.MainActivity: +1s341ms
I/Timeline(  936): Timeline: Activity_windows_visible id: ActivityRecord{3762a94f u0 com.test.thalitest/.MainActivity t222} time:82898
I/Timeline( 5571): Timeline: Activity_idle id: android.os.BinderProxy@2ec56bbf time:82922
W/art     ( 5606): Suspending all threads took: 7.429ms
,W/BindingManager( 5571): Cannot call determinedVisibility() - never saw a connection for the pid: 5571
,D/ChimeraCfgMgr( 5606): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5606): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 5606): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5606): Submit a task: k
,D/ChimeraCfgMgr( 5606): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 5606): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 5606): Processing package: com.test.thalitest
,D/JsMessageQueue( 5571): Set native->JS mode to OnlineEventsBridgeMode
I/PeopleDatabaseHelper( 5606): cleanUpNonGplusAccounts done.
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
E/MDM     ( 1732): [134] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/GassUtils( 5606): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5606): Found info for package com.test.thalitest in db.
I/art     ( 5606): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5606): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/Icing   ( 5606): Storage manager: low false usage 1.76MB avail 2.38GB capacity 4.06GB
,W/BaseAppContext( 5606): Using Auth Proxy for data requests.
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
D/LocationInitializer( 5606): Restart initialization of location
,I/art     ( 3964): Explicit concurrent mark sweep GC freed 3461(133KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 481us total 29.882ms
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/BaseAppContext( 5606): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
W/BaseAppContext( 5606): Using Auth Proxy for data requests.
,I/ActivityManager(  936): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5694 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 23.350ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 22.697ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 319us total 22.743ms
,W/BaseAppContext( 5606): Using Auth Proxy for data requests.
,W/BaseAppContext( 5606): Using Auth Proxy for data requests.
,W/BaseAppContext( 5606): Using Auth Proxy for data requests.
W/BaseAppContext( 5606): Using Auth Proxy for data requests.
,W/BaseAppContext( 5606): Using Auth Proxy for data requests.
,W/IcingInternalCorpora( 5606): getNumBytesRead when not calculated.
D/jxcore_app_log( 5571): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622977024
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
I/chromium( 5571): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/art     ( 5571): Suspending all threads took: 5.958ms
,I/art     ( 5571): Background sticky concurrent mark sweep GC freed 21813(1694KB) AllocSpace objects, 4(60KB) LOS objects, 7% free, 10MB/11MB, paused 7.397ms total 51.915ms
I/art     ( 5571): CheckpointMarkThreadRoots callback created = 0x9b5dd420
,I/art     ( 5571): CheckpointMarkThreadRoots callback created = 0x9b5dd3f0
,W/ActivityManager(  936): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     ( 5606): Background sticky concurrent mark sweep GC freed 15924(1438KB) AllocSpace objects, 14(224KB) LOS objects, 11% free, 12MB/14MB, paused 6.366ms total 90.635ms
,I/Gmail   ( 5694): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5694): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Icing   ( 5606): updateResources: need to parse f{com.google.android.gms}
,I/art     (  936): Explicit concurrent mark sweep GC freed 20461(956KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.576ms total 194.278ms
W/ActivityManager(  936): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  936): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,E/Gmail   ( 5694): Error finding the version of the Email provider.....
E/Gmail   ( 5694): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5694): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5694): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5694): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5694): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5694): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5694): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5694): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 5694): We do not support migrating this version of the Email provider.
W/ActivityManager(  936): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5694): getAccountsCursor
,I/ActivityManager(  936): Killing 5317:com.android.gallery3d/u0a23 (adj 15): empty #11
I/Gmail   ( 5694): Observing account changes for notifications
,W/libprocessgroup(  936): failed to open /acct/uid_10023/pid_5317/cgroup.procs: No such file or directory
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 5606): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5606): Module APK com.google.android.play.games already loaded
W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@2258ed66 on behalf of 5606
W/InstanceID/Rpc( 5606): Found 10006
,I/art     ( 5606): Background sticky concurrent mark sweep GC freed 12101(930KB) AllocSpace objects, 10(160KB) LOS objects, 6% free, 13MB/14MB, paused 7.196ms total 113.375ms
,I/ActivityManager(  936): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5748 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/InitAlarmsService( 3804): Clearing and rescheduling alarms.
,I/art     ( 5606): Background sticky concurrent mark sweep GC freed 218(19KB) AllocSpace objects, 0(0B) LOS objects, 6% free, 13MB/14MB, paused 10.820ms total 55.914ms
,D/CalendarProvider2( 5467): Scheduling check of next Alarm
,D/CalendarProvider2( 5467): SCHEDULE_ALARM_REMOVE
I/Gmail   ( 5694): notifyAccountChanged
,I/Gmail   ( 5694): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5694): getAccountsCursor
,V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5694): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/PhoneMonitor( 5748): Register our PhoneStateListener
I/Gmail   ( 5694): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5694): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/art     ( 3241): Explicit concurrent mark sweep GC freed 5936(346KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/13MB, paused 922us total 49.830ms
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@3b1658a7 on behalf of 5606
I/ActivityManager(  936): Process com.android.contacts (pid 5339) has died
,V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@2fb0d154 on behalf of 5606
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PhoneMonitor( 5748): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5748): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5748): [parse] Load xml
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/TelephonyAutoProfiling( 5748): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5748): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/Icing   ( 5606): Internal init done: storage state 0
,I/Icing   ( 5606): Post-init done
I/NotificationManager( 5606): com.google.android.gms: cancel(10436) by com.google.android.gms
D/PhoneMonitor( 5748): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 5606): Checkin interval check for package: unspecified last checkin: 1455029363456 min interval config: 0 actual interval: 7117
,I/CheckinService( 5606): Disabling old GoogleServicesFramework version
,I/ActivityManager(  936): Process com.android.calendar (pid 3804) has died
,I/CheckinService( 5606): Checking schedule, now: 1455029370696 next: 1455029393426
I/CheckinService( 5606): active receiver: disabled
,I/ActivityManager(  936): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5779 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/Gmail   ( 5694): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5779): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/jxcore-log( 5571): Initializing JXcore engine
,W/jxcore-log( 5571): JXcore engine is ready
,W/Thread-671( 5718): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5644]" dev="sockfs" ino=5644 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-671( 5718): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-671( 5718): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6456]" dev="sockfs" ino=6456 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-671( 5718): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-671( 5718): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-671( 5718): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[27662]" dev="sockfs" ino=27662 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,W/jxcore-log( 5571): Starting JXcore engine
,I/ActivityManager(  936): Process com.lge.bnr (pid 5402) has died
,I/CalendarProvider2( 5467): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5467): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/Babel_SMS( 5779): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5779): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5779): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5779): MmsConfig.loadFromDatabase
I/art     ( 5779): CheckpointMarkThreadRoots callback created = 0xaaf24e20
,E/Babel_SMS( 5779): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5779): MmsConfig.loadFromResources
E/Babel_SMS( 5779): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5779): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/art     ( 5779): CheckpointMarkThreadRoots callback created = 0xaaf24e00
,D/SensorManager( 5779): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5779): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5779): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5779): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5779): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5779): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5779): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5779): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5779): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5779): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5779): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5779): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5779): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5779): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5779): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5779): found sensor: Motion Accel, handle=46
W/jxcore-log( 5571): Platform android
W/jxcore-log( 5571): 
W/jxcore-log( 5571): Process ARCH arm
W/jxcore-log( 5571): 
W/Settings( 5779): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5779): startup - clean
I/Babel   ( 5779): deleted: false for 0
,W/AudioCapabilities( 5779): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5779): Unsupported mime audio/adpcm
W/AudioCapabilities( 5779): Unsupported mime audio/g726
W/AudioCapabilities( 5779): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5779): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5779): Unsupported mime video/mjpg
W/VideoCapabilities( 5779): Unsupported mime video/theora
W/AudioCapabilities( 5779): Unsupported mime audio/evrc
,W/AudioCapabilities( 5779): Unsupported mime audio/qcelp
W/VideoCapabilities( 5779): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  936): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5807 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 5606): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/AudioManager( 5127): getMode name:com.lge.qremote
W/AudioCapabilities( 5779): Unsupported mime audio/amr-wb-plus
I/AudioManager( 5127): getMode name:com.lge.qremote
,I/AudioManager( 5127): getMode name:com.lge.qremote
W/AudioCapabilities( 5779): Unsupported mime audio/qcelp
W/AudioCapabilities( 5779): Unsupported mime audio/evrc
,W/ActivityManager(  936): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  936): RTC_WAKEUP set : Alarm{1a1ff9ea type 0 when 1454942922662 com.android.providers.contacts} when 1454942922662
V/AlarmManager(  936): ELAPSED_WAKEUP set : Alarm{12bee4db type 2 when 59803 com.google.android.talk} when 59803
V/AlarmManager(  936): RTC_WAKEUP set : Alarm{2269b251 type 0 when 1455029371823 com.google.android.googlequicksearchbox} when 1455029371823
I/AudioManager( 5127): getMode name:com.lge.qremote
,I/AudioManager( 5127): getMode name:com.lge.qremote
E/MDM     ( 1732): [83] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5606): Restart initialization of location
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/VideoCapabilities( 5779): Unsupported mime video/mp4v-esdp
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 5807): Quickset Services start...
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
I/UEI.SmartControl( 5807): Manufacture = LGE
D/UEI.SmartControl( 5807): File observer start...
E/UEI.SmartControl( 5807): IR Port is disabled: false
,W/GCoreFlp( 1732): No location to return for getLastLocation()
D/UEI.SmartControl( 5807): Starting file observer...
D/UEI.SmartControl( 5807): Extracting JNI libs...
D/UEI.SmartControl( 5807): --- this system supports 32-bit or 64-bit only
W/FusedLocationProvider( 1732): location=null
I/AudioManager( 5127): getMode name:com.lge.qremote
,D/Icing   ( 5606): Loaded CLD2 Version V2.0 - 20141016
I/VideoCapabilities( 5779): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5779): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5779): Unrecognized profile 2130706433 for video/avc
I/Icing   ( 5606): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/VideoCapabilities( 5779): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5779): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5779): onServiceConnected
,W/Babel   ( 5779): Attempted to change video mute state without an active call.
I/ActivityManager(  936): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5837 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/jxcore-log( 5571): JXcore Cordova bridge is ready!
I/jxcore-log( 5571): 
,W/jxcore-log( 5571): JXcore engine is started
I/NotificationManager( 5779): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5779): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
I/NotificationManager( 5779): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 5779): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppUp4:AppBoxCP( 5837): onCreate
,W/AppUp4:DB( 5837):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5837):  setFingerPrint start
,I/AppUp4:DB( 5837):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
V/JNIHelp ( 5779): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:DB( 5837):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5837):  SDK version = 0
I/AppUp4:DB( 5837):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5837): AppBoxApplication onCreate()
D/UEI.SmartControl( 5807): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
I/AppUp4:CustModeStarterReceiver( 5837): onReceive
I/AppUp4:CustModeStarterReceiver( 5837): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/UEI.SmartControl( 5807): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5807): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,D/AppUp4:CustFacade( 5837): Context : android.app.ReceiverRestrictedContext@23a6e4e2
D/AppUp4:CustFacade( 5837): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5837): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5837): begin check event
I/AppUp4:CustModeStarterReceiver( 5837): Event For Nothing, skip.
I/UEI.SmartControl( 5807): --- Selecting new region: 2
I/UEI.SmartControl( 5807): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5807): Platform has CIR...
D/UEI.SmartControl( 5807): NO CIR support, need to check package...
I/UEI.SmartControl( 5807): Model: LG-D722 uses JNI
W/System  ( 5779): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5779): Installed default security provider GmsCore_OpenSSL
D/UEI.SmartControl( 5807): QS Service created
I/ActivityManager(  936): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5859 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/jxcore-log( 5571): Toggling radios to true
I/jxcore-log( 5571): 
,D/BluetoothAdapter( 5571): enable(): BT is already enabled..!
I/ActivityManager(  936): Process com.google.android.apps.docs (pid 5419) has died
,D/WifiServiceImplEx(  936): setWifiEnabled: true pid=5571, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  936): setWifiEnabled: true pid=5571, uid=10316
D/WifiServiceImplEx(  936): disconnect pid=5571, uid=10316, packageName=com.test.thalitest
,D/WifiServiceImplEx(  936): reconnect pid=5571, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5571): Radios toggled
I/jxcore-log( 5571): 
I/jxcore-log( 5571): My device name is: LGE-LG-D722
I/jxcore-log( 5571): 
,I/wpa_supplicant( 2840): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
,I/wpa_supplicant( 2840): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
E/WifiStateMachine(  936): WifiStateMachine: Leaving Connected state
W/ResourcesManager( 5859): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5859): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5859): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/WfdsMonitor( 1802): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/UEI.SmartControl( 5807): QS start get config
E/WifiConfigStore(  936): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  936): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  936): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  274): Clearing all IP addresses on wlan0
,D/DhcpStateMachine(  936): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1732): Read error: ssl=0xb045c600: I/O error during system call, Connection timed out
,V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xb045c600: I/O error during system call, Broken pipe
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
D/WifiHS20(  936): hidePasspointNotification off =false
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/WifiStateMachine(  936): Start Disconnecting Watchdog 1
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:32.56 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/wpa_supplicant( 2840): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  936): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  936): ignoring duplicate network state non-change
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:32.568 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  936): hidePasspointNotification off =false
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/ConnectivityService(  936): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  936): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/LGWifiP2pService(  936): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  936): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): ValidatedState{ when=-3ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): DefaultState{ when=-10ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): Forcing reevaluation
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
,D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/UEI.SmartControl( 5807): Loading JNI Libs...
D/UEI.SmartControl( 5807):  configuring local db...
,D/CommandListener(  274): Clearing all IP addresses on wlan0
,D/ConnectivityService(  936): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  936): disableDataServiceNotify
D/DSQN    (  936): stop dsqn bin
D/ConnectivityService(  936): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  936):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  936):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DhcpStateMachine(  936): StoppedState
D/DhcpStateMachine(  936): StoppedState{ when=-149ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  936): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): Disconnected - quitting
D/Nat464Xlat(  936): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/CSLegacyTypeTracker(  936): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  936): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  936): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/ActivityManager(  936): Process com.android.vending (pid 5520) has died
,D/ConnectivityService(  936): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  936): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiHS20(  936): hidePasspointNotification off =false
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:32.769 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
V/NetworkPolicy(  936): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  936): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  936): MasterInitialState.processMessage what=3
D/Tethering(  936): MasterInitialState.processMessage what=3
D/ConnectivityService(  936): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
W/QCNEJ   ( 1839): |CORE| No family connected
D/ConnectivityService(  936): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  936): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkManagementService(  936): Removing idletimer
D/TelephonyNetworkFactory-1( 1748): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
,I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
W/Settings(  936): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNetworkAgent(  936): NetworkAgent: NetworkAgent channel lost
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:32.784 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  936): hidePasspointNotification off =false
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WIFI    (  936): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  936):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:32.788 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  936): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  936): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  936): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  936): setSupplicantStateSCANNING
I/AppConfig( 5859): Total System Memory = 906309632
I/GalleryUtils( 5859): Application Heap = 96 MB
I/AppConfig( 5859): App Tier : NOT_DEF
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
D/SystemHelper( 5859): region [EU], country [EU], operator [OPEN], sub-operator []
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
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
,I/ActivityManager(  936): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5883 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/UEI.SmartControl( 5807):  ---- Has DB8: true
D/UEI.SmartControl( 5807): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5807): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5807): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5807): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5807): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5807): IrrcClient ++ 
D/irrcClient( 5807): getIrrcService ++ 
,D/irrcClient( 5807): getIrrcService -- 
D/irrcClient( 5807): IrrcClient -- 
W/irrc_jni( 5807): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5807): Services init done
I/UEI.SmartControl( 5807): Device manager: loading config....
,D/UEI.SmartControl( 5807): QS Service init finished
,D/UEI.SmartControl( 5807): QS Service version name: 0.1.73
D/UEI.SmartControl( 5807): QS Service version code: 1073
D/UEI.SmartControl( 5807): Service requested: Control
D/UEI.SmartControl( 5807): Config is loaded...
W/ResourcesManager( 5883): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5883): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5883): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 5883): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5883): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5807):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5807): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5807): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5807): Internal service binding...
D/UEI.SmartControl( 5807): -----IControl: 11
,D/UEI.SmartControl( 5807): Caller: com.lge.qremote
D/UEI.SmartControl( 5807): ------------ IControl registerCallback...
I/UEI.SmartControl( 5807): Registering callback...
D/UEI.SmartControl( 5807): -----IControl: 19
D/UEI.SmartControl( 5807): Caller: com.lge.qremote
I/UEI.SmartControl( 5807): Registering Services Ready callback...
I/UEI.SmartControl( 5807): Notify client services are ready...
D/UEI.SmartControl( 5807): -----IControl: 8
D/UEI.SmartControl( 5807): Caller: com.lge.qremote
I/ActivityManager(  936): Killing 5365:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  936): failed to open /acct/uid_10069/pid_5365/cgroup.procs: No such file or directory
,I/SystemConfig( 5883): BUILD Country: EU
I/SystemConfig( 5883): BUILD Operator: OPEN
,I/ActivityManager(  936): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5911 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  936): Killing 5385:com.lge.eula/1000 (adj 15): empty #11
,W/libprocessgroup(  936): failed to open /acct/uid_1000/pid_5385/cgroup.procs: No such file or directory
,I/SystemConfig( 5883): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5883): existFile = false
I/SystemConfig( 5883): canReadFile = false
I/SystemConfig( 5883): systemFeature RCS result false
D/SystemConfig( 5883): refreshRcsSupport() :false
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
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
I/InputReader(  936): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,D/administrator(  936): Handling package changes for user 0
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2840): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     (  936): Explicit concurrent mark sweep GC freed 36066(1702KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 14.575ms total 318.511ms
,I/ActivityManager(  936): Process com.google.android.gm (pid 5694) has died
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:33.778 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/wpa_supplicant( 2840): wlan0: Associated with c0:ff:d4:d3:aa:48
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:33.792 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:33.804 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:33.811 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/wpa_supplicant( 2840): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2840): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/WifiServiceExtension(  936): setVHTCapabilityType  : false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/WifiServerServiceExt(  936): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  936): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  936): setSecurityType  : 2
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:33.868 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:33.874 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
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
D/ConnectivityService(  936): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  936): Got NetworkAgent Messenger
D/ConnectivityService(  936): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/ConnectivityService(  936): NetworkAgent connected
E/WifiConfigStore(  936): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/NotificationService(  936): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  936): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  936): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  936): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,E/WifiConfigStore(  936): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LocSvc_java(  936): onReceive
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  936): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  936): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  936): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  936): setSupplicantStateASSOCIATED
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  936): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  936): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  936): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  936): setSupplicantStateGROUP_HANDSHAKE
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
V/BackupManagerService(  936): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/BackupManagerService(  936): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1d833557
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
E/WifiStateMachine(  936): Start Dhcp Watchdog 2
I/LockScreenSettings( 5911): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/DhcpStateMachine(  936): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  936): WaitBeforeStartState
D/ConnectivityService(  936): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,D/LockScreenSettings( 5911): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5911): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5911): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5911): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5911): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,W/ResourcesManager(  936): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/WifiStateMachine(  936): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  936): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  936): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@20304503 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  936): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@20304503 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  936): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  936): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  936): DHCP Start wake lock is acquired.
D/CommandListener(  274): Setting iface cfg
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Trying to bring up wlan0
,V/LgDhcpStateMachineHelper(  936): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  936): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  936): setSupplicantStateCOMPLETED
I/UpdateIcingCorporaServi( 1934): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/WifiServerServiceExt(  936): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  936): setSupplicantStateCOMPLETED
D/ConnectivityService(  936): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  936): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  936): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  936): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  936): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  936): ignoring duplicate network state non-change
I/ActivityManager(  936): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5944 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityService(  936): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/ConnectivityService(  936): Adding iface wlan0 to network 101
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20(  936): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  936): [PASSPOINT] passpointNotification: hs20AP list is checked
,W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine(  936): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/ConnectivityService(  936): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  936): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  936): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  274): netlink response contains error (File exists)
D/ConnectivityService(  936): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  936): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  936): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  936): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:34.137 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/Nat464Xlat(  936): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  936): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  936): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  936): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  936):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  936):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  936):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  936):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  936):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  936): currentScore = 0, newScore = 20
D/ConnectivityService(  936):    accepting network in place of null
D/ConnectivityService(  936): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:34.14 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WIFI    (  936): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  936):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/ConnectivityService(  936): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTr,acker(  936): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  936): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  936): MasterInitialState.processMessage what=3
D/TelephonyNetworkFactory-1( 1748): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  936): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  936): [e] list.add(nai) empty : false size: 1
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  936): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:34.143 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  936): validation of new default Network = false
D/ConnectivityService(  936): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  936): enableDataServiceNotify 
D/DSQN    (  936): start dsqn bin
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:34.152 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): [LWD] wait 500ms before dns check
D/ConnectivityService(  936): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  936):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  936):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  936): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/DSQN    ( 5966): DSQN samuel.seo ver 141203
E/DSQN    ( 5966): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5966): created command queue thread
I/DSQN    ( 5966): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5966): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
V/NetworkPolicy(  936): [LG_RESTRICTED] checkMobilePolicy_type()
I/CheckinService( 5606): Checkin interval check for package: unspecified last checkin: 1455029363456 min interval config: 0 actual interval: 10754
I/UpdateIcingCorporaServi( 1934): UpdateCorporaTask done [took 182 ms] updated apps [took 182 ms] 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
,I/[SystemUI]StatusBar.NetworkController( 1371): mWifiConnected = true, mWifiLevel = 2
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1371): Remote
D/DhcpStateMachine(  936): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  936): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  936): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5972): version 5.5.6 starting
E/dhcpcd  ( 5972): get_duid: Read-only file system
,W/ResourceType(  936): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  936): Process com.google.process.gapps (pid 3964) has died
I/dhcpcd  ( 5972): wlan0: rebinding lease of 192.168.1.134
,I/CheckinService( 5606): Checking schedule, now: 1455029374327 next: 1455029393426
I/CheckinService( 5606): active receiver: disabled
D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  936): Start proc com.google.process.gapps for content provider com.google.android.gsf/.settings.GoogleSettingsProvider: pid=5980 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GservicesProvider( 5980): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 5980): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5980): GMS http client unavailable, use old client
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): [LWD] DNSResolver start dns
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/LocationProviderProxy(  936): applying state to connected service
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out(  936): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/DSQN    ( 5966): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5966): restart monitoring
I/DSQN    ( 5966): dsqn report finish
,D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  936): DSQM DsqnNotification wlan0  1
D/DSQN    (  936): start to monitor internet connection
I/ActivityManager(  936): Process com.lge.qremote (pid 5127) has died
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 14:49:34 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455029374831], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455029374779]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  936): Validated
D/ConnectivityService(  936): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  936): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  936):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  936):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  936):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  936): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  936): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  936):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  936):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  936): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  936): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524290
D/ConnectivityService(  936): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  936): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  936):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1748): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiDataContinuityService(  936): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/TelephonyNetworkFactory-1( 1748):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/WifiServerServiceExt(  936): set CMD_CAPTIVE_CHECK_COMPLETED
,D/TelephonyIcons( 1371): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1371): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/Finsky  ( 5944): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  936): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  936): identical MTU - not setting
D/Nat464Xlat(  936): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  936): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  936):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  936):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  936): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  936): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  936): enableDataServiceNotify 
D/DSQN    (  936): start dsqn bin
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityManager.CallbackHandler( 1371): CM callback handler got msg 524295
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-59 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:34.974 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/DSQN    (  936): dsqn is running restart
,I/DSQN    ( 6017): DSQN samuel.seo ver 141203
E/DSQN    ( 6017): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6017): created command queue thread
I/DSQN    ( 6017): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6017): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Finsky  ( 5944): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5944): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5944): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  936): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
I/NotificationManager( 5944): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@2908e8fd on behalf of 5944
D/Ads     ( 5944): Skipping gmscore version check
I/ActivityManager(  936): Process com.uei.lg.quicksetsdk.lite (pid 5807) has died
,V/AlarmManager(  936): ELAPSED_WAKEUP set : Alarm{25531f1a type 2 when 90160 com.android.providers.calendar} when 90160
I/dhcpcd  ( 5972): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
D/Finsky  ( 5944): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5944): [1] Libraries$2.run: Finished loading 1 libraries.
D/PackageBroadcastService( 5606): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/dhcpcd  ( 5972): wlan0: leased 192.168.1.134 for 86400 seconds
D/Finsky  ( 5944): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  936): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6044 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 5606): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 5606): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 5944): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/ResourcesManager( 6044): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ProcessCpuTracker(  936): Skipping unknown process pid 6082
,D/ConnectivityService(  936): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  936): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  936): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  936): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  936): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  936): onReceive
D/LocSvc_java(  936): got connectivity action
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  936): broadcast - no network connections
D/LocSvc_java(  936): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  936): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  936): onReceive
D/LocSvc_java(  936): got connectivity action
D/LocSvc_java(  936): broadcast - no network connections
D/LocSvc_java(  936): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  936): Sending msg: 4 arg1:0 arg2:1
D/GpsLocationProvider(  936): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LocSvc_java(  936): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  936): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  936): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  936): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  936): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  936): ignore wifi update if we are not in OPENING or CLOSING
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  936): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  936): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  936): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  936): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  936): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  936): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  936): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  936): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  936): RunningState
,D/BluetoothManagerService(  936): Message: 20
D/BluetoothManagerService(  936): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12c182ca:true
,D/BluetoothAdapterService(527731292)( 1977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7164a92
D/BluetoothAdapterService(527731292)( 1977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7164a92
I/ActivityManager(  936): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6091 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6044): Create singleton instance
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 22.295ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 30.356ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 33.543ms
,I/AudioManager( 6044): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6091): Quickset Services start...
I/UEI.SmartControl( 6091): Manufacture = LGE
D/UEI.SmartControl( 6091): File observer start...
,E/UEI.SmartControl( 6091): IR Port is disabled: false
D/UEI.SmartControl( 6091): Starting file observer...
D/UEI.SmartControl( 6091): Extracting JNI libs...
D/UEI.SmartControl( 6091): --- this system supports 32-bit or 64-bit only
I/AudioManager( 6044): getMode name:com.lge.qremote
D/UEI.SmartControl( 6091): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6091): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 6091): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/SetupWizard( 5748): Connected to Gservices successfully
I/UEI.SmartControl( 6091): --- Selecting new region: 2
,I/UEI.SmartControl( 6091): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6091): Platform has CIR...
D/UEI.SmartControl( 6091): NO CIR support, need to check package...
I/UEI.SmartControl( 6091): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6091): QS Service created
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/MDM     ( 1732): [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/LocationInitializer( 5606): Restart initialization of location
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/UEI.SmartControl( 6091): QS start get config
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 1732): propertyValue:false
I/ActivityManager(  936): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6120 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6091): Loading JNI Libs...
D/UEI.SmartControl( 6091):  configuring local db...
I/DSQN    ( 6017): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6017): restart monitoring
D/LGDataListener(  274): argv[0]=dsqncommand
,D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6017): dsqn report finish
D/DSQN    (  936): DSQM DsqnNotification wlan0  1
D/DSQN    (  936): start to monitor internet connection
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/UEI.SmartControl( 6091):  ---- Has DB8: true
,D/UEI.SmartControl( 6091): QS start statue = true Error code = 0
D/UEI.SmartControl( 6091): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6091): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6091): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6091): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6091): IrrcClient ++ 
D/irrcClient( 6091): getIrrcService ++ 
D/irrcClient( 6091): getIrrcService -- 
D/irrcClient( 6091): IrrcClient -- 
W/irrc_jni( 6091): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6091): Services init done
,I/UEI.SmartControl( 6091): Device manager: loading config....
D/UEI.SmartControl( 6091): QS Service init finished
D/UEI.SmartControl( 6091): QS Service version name: 0.1.73
D/UEI.SmartControl( 6091): Config is loaded...
D/UEI.SmartControl( 6091): QS Service version code: 1073
D/UEI.SmartControl( 6091): Service requested: Control
D/UEI.SmartControl( 6091): Internal service binding...
D/UEI.SmartControl( 6091): -----IControl: 11
,D/UEI.SmartControl( 6091): Caller: com.lge.qremote
D/UEI.SmartControl( 6091): ------------ IControl registerCallback...
I/UEI.SmartControl( 6091): Registering callback...
D/UEI.SmartControl( 6091): -----IControl: 19
D/UEI.SmartControl( 6091): Caller: com.lge.qremote
I/UEI.SmartControl( 6091): Registering Services Ready callback...
I/UEI.SmartControl( 6091): Notify client services are ready...
D/UEI.SmartControl( 6091): -----IControl: 8
D/UEI.SmartControl( 6091): Caller: com.lge.qremote
I/ActivityManager(  936): Killing 5467:com.android.providers.calendar/u0a14 (adj 15): empty #11
,D/UEI.SmartControl( 6091):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6091): Notify AllClients services are ready: 0
W/ActivityManager(  936): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup(  936): failed to open /acct/uid_10014/pid_5467/cgroup.procs: No such file or directory
I/Gmail   ( 6120): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6120): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Icing   ( 5606): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  936): Process com.android.gallery3d (pid 5859) has died
,W/ActivityManager(  936): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 15:49:36.977 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ActivityManager(  936): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6120): Observing account changes for notifications
W/ActivityManager(  936): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/WifiInternetCheck(  936): Single check msg out of sync, ignoring.
,I/ActivityManager(  936): Process com.android.contacts (pid 5883) has died
E/Gmail   ( 6120): Error finding the version of the Email provider.....
E/Gmail   ( 6120): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6120): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6120): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6120): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6120): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6120): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6120): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6120): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6120): We do not support migrating this version of the Email provider.
I/Gmail   ( 6120): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 5606): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/NotificationManager( 1934): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
D/ConnectivityService(  936): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  936): onReceive
D/LocSvc_java(  936): got connectivity action
D/LocSvc_java(  936): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  936): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  936): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  936): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  936): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  936): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1371): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  936): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  936): Explicit concurrent mark sweep GC freed 74066(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.449ms total 170.165ms
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 31776(2MB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 13MB/22MB, paused 4.501ms total 119.285ms
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Gmail   ( 6120): notifyAccountChanged
,I/Gmail   ( 6120): getAccountsCursor
I/Gmail   ( 6120): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6120): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6120): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6120): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  936): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6172 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6172): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6172): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6172): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6172): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@4bd69ad, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@23a6e4e2, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@30988073, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@3403eb30, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2e73f3a9, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@39526d2e, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@24f0b0cf, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1f748a5c, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@5ef2165, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@1c1c2e3a, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@8f18aeb, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3edf048, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@b356ee1, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@308ef406, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3ddbeac7, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3515c8f4, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1e39181d, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@7164a92, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@e226c63, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@39408060, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@31d41919, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@194a7dde, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2ec56bbf, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@259d428c, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@32842dd5, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@ffc99ea, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3a6f04db, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@1121fb78, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1ce6d251, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1e026ab6, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@24f13b7, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@a375724, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3ff5428d, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3bc27c42, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@10b73453, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3b24c190, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@27007a89, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@f801a8e, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3976c2af, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@293c66bc, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@276d3645, lg_preferences_recent,_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@e67519a, 
,D/GeneralPreferenceUtils( 6172): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6172): [init]
I/Config  ( 6172): LGCalendar ver.4.40.17
I/Config  ( 6172): start check model
I/Config  ( 6172): start check native_ca
I/Config  ( 6172): Config Operator=OPEN, Country=EU
,D/Config  ( 6172): [setDefaultValuesToPref]
D/Config  ( 6172): [parseProfiles]
D/ProfilesParser( 6172): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6172): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6172): [updateProfiletoCountryInfo]
D/GeneralPreference( 6172): [checkAndMigrateOldPreference]
D/AlertReceiver( 6172): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6172): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6172): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/Gmail   ( 6120): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AlertUtils( 6172): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6172): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6172): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6172): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6172): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6172): onHandleIntent
,D/HolidayDataLoader( 6172): readJsonAsset : holiday.json
D/AlertService( 6172): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6172): [updateWidgets] 
,D/MonthWidgetProvider( 6172): [onReceive]
D/CalendarWidgetProvider( 6172): [onReceive]
D/CalendarWidgetProvider( 6172): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6172): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6172): [onReceive]
D/CalendarWidgetProvider( 6172): [onReceive]
D/CalendarWidgetProvider( 6172): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6172): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6172): onHandleIntent:holiday data empty
,I/ActivityManager(  936): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6199 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/ResourcesManager( 5779): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5779): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
W/ResourcesManager( 6199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6199): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6199): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6199): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6199): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  936): propertyValue:false
,D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  936): propertyValue:false
V/WifiInternetCheck(  936): isHttpConnectionAvailable - We got a valid response : 204
,V/AlarmManager(  936): RTC_WAKEUP set : Alarm{32ba3e71 type 0 when 1455029378419 com.android.vending} when 1455029378419
,D/Finsky  ( 5944): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/IndexDatabaseHelper( 6199): Using schema version: 115
,I/IndexDatabaseHelper( 6199): Index is fine
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  936): android: cancelAsUser(2) by android
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
D/libc-netbsd( 5944): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5944): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5944): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5944): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 5944): propertyValue:false
D/libc-netbsd( 5944): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5944): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
I/ActivityManager(  936): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6231 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/libc-netbsd( 5944): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5944): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/PCSuite ( 6231): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6231): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6231): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
I/PCSuite ( 6231): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6231): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6231): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
I/PCSuite ( 6231): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6231): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6231): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
I/NotificationManager(  936): android: cancelAsUser(2) by android
I/PCSuite ( 6231): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6231): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6231): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
,I/AudioManager( 6044): getMode name:com.lge.qremote
I/AppUp4:CustModeStarterReceiver( 5837): onReceive
I/AppUp4:CustModeStarterReceiver( 5837): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5837): Context : android.app.ReceiverRestrictedContext@23a6e4e2
D/AppUp4:CustFacade( 5837): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5837): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5837): begin check event
I/AppUp4:CustModeStarterReceiver( 5837): Event For Nothing, skip.
I/NotificationManager( 5779): com.google.android.talk: cancel(8) by com.google.android.talk
I/qtaguid ( 5944): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5944): Untagging socket 41 failed errno=-22
,W/NetworkManagementSocketTagger( 5944): untagSocket(41) failed with errno -22
,I/ActivityManager(  936): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6259 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/Finsky  ( 5944): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,W/ResourcesManager( 6259): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6259): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6259): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/ActivityManager(  936): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6278 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  936): android: cancelAsUser(2) by android
,W/ResourcesManager( 6278): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6278): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppConfig( 6259): Total System Memory = 906309632
,I/GalleryUtils( 6259): Application Heap = 96 MB
I/AppConfig( 6259): App Tier : NOT_DEF
,D/SystemHelper( 6259): region [EU], country [EU], operator [OPEN], sub-operator []
,I/MultiDex( 6278): VM with version 2.1.0 has multidex support
I/MultiDex( 6278): install
I/MultiDex( 6278): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  936): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6297 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  936): Killing 5911:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/qtaguid ( 5944): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5944): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5944): untagSocket(41) failed with errno -22
,I/ActivityManager(  936): Process com.google.android.gm (pid 6120) has died
,W/libprocessgroup(  936): failed to open /acct/uid_10069/pid_5911/cgroup.procs: No such file or directory
V/JNIHelp ( 6278): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 6297): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6297): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6297): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6297): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6297): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/art     ( 5944): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,W/ActivityThread( 6278): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6278): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@207679f2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6278): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6278): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6278): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 5944): CheckpointMarkThreadRoots callback created = 0xaafd1bc0
,D/ChimeraCfgMgr( 6278): Reading stored module config
,I/SystemConfig( 6297): BUILD Country: EU
I/SystemConfig( 6297): BUILD Operator: OPEN
,D/ChimeraCfgMgr( 6278): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/ActivityManager(  936): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6329 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,D/sensors_hal_Time(  936): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  936): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  936): tsOffsetIs: Apps: 95099366634; DSPS: 3215015; Offset : -3024902639
,I/SystemConfig( 6297): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6297): existFile = false
,I/SystemConfig( 6297): canReadFile = false
I/SystemConfig( 6297): systemFeature RCS result false
D/SystemConfig( 6297): refreshRcsSupport() :false
D/CAR.SERVICE( 6278): Connecting to CarCallService...
,D/NativeLibraryUtils( 6278): Install completed successfully. count=14 extracted=0
,I/art     ( 6278): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6278): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/LockScreenSettings( 6329): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/LockScreenSettings( 6329): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6329): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6329): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6329): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6329): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/CAR.SERVICE( 6278): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager(  936): Process com.android.settings (pid 6199) has died
,D/CAR.TEL.Service( 6278): Creating a new CarCallService.
,I/UpdateIcingCorporaServi( 1934): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/CAR.TEL.PhoneAdapter( 6278): Creating a new PhoneAdapter instance
W/ActivityManager(  936): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6278): setListener: com.google.android.gms.car.dn@3c99f169
W/ActivityManager(  936): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6278): Returning an existing PhoneAdapter instance.
,D/PackageBroadcastService( 5606): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/CAR.TEL.Service( 6278): Starting CarCallService with initial phone null
I/ActivityManager(  936): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6355 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PackageBroadcastService( 5606): Null package name or gms related package.  Ignoreing.
I/UpdateIcingCorporaServi( 1934): UpdateCorporaTask done [took 94 ms] updated apps [took 94 ms] 
D/CAR.SERVICE( 6278): Package validated; name: com.android.vending
,I/NotificationManager( 6278): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 5944): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5944): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/ResourcesManager( 6355): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6355): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6355): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6355): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6355): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6355): Using schema version: 115
I/IndexDatabaseHelper( 6355): Index is fine
,I/art     (  936): Explicit concurrent mark sweep GC freed 14989(760KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.801ms total 174.263ms
,I/Icing   ( 5606): updateResources: need to parse f{com.google.android.gms}
V/WiFiOffLoadBroadcast( 6355): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6355): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6355): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6355): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6355): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6355): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6355): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6355): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6355): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6355): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6355): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6355): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6355): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6355): MCCMNC not supported: null
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/WiFiOffLoadBroadcast( 6355): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6355): MCCMNC not supported: null
I/NotificationManager(  936): android: cancelAsUser(2) by android
V/WiFiOffLoadBroadcast( 6355): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6355): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6355): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6355): MCCMNC not supported: null
I/PCSuite ( 6231): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6231): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6355): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6355): MCCMNC not supported: null
,I/PCSuite ( 6231): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6231): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  936): Killing 5837:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  936): failed to open /acct/uid_10011/pid_5837/cgroup.procs: No such file or directory
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/jxcore-log( 5571): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5571): 
,I/ActivityManager(  936): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6382 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6382): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6382): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@103dddd7
,D/CalendarProvider2( 6382): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6382): Created com.android.providers.calendar.CalendarAlarmManager@3403eb30(com.android.providers.calendar.CalendarProvider2@103dddd7)
D/CalendarProviderBroadcastReceiver( 6382): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6382): [IntentService] WakeLock acquire, start IntentSerivce
,D/CalendarProvider2( 6382): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6382): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6382): [getOrCreateCalendarAlarmManager]
D/UEI.SmartControl( 6091): Internal timer expired: 1
,I/ActivityManager(  936): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6404 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 281us total 21.016ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.469ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.705ms
,D/CalendarProvider2( 6382): [IntentService] Release Lock
,D/CalendarProvider2( 6382): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  936): Killing 6259:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  936): failed to open /acct/uid_10023/pid_6259/cgroup.procs: No such file or directory
I/qtaguid ( 5944): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5944): Untagging socket 41 failed errno=-22
,W/NetworkManagementSocketTagger( 5944): untagSocket(41) failed with errno -22
I/Icing   ( 5606): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/MusicStore( 6404): Database version: 120
,I/Icing   ( 5606): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  936): Killing 6297:com.android.contacts/u0a18 (adj 15): empty #11
,W/ResourcesManager( 5944): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5944): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  936): failed to open /acct/uid_10018/pid_6297/cgroup.procs: No such file or directory
V/AlarmManager(  936): RTC_WAKEUP set : Alarm{265302ee type 0 when 1455029382156 com.google.android.googlequicksearchbox} when 1455029382156
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6404): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5944): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5944): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  936): RTC_WAKEUP set : Alarm{22626cb4 type 0 when 1455029382287 com.android.vending} when 1455029382287
,D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
D/Finsky  ( 5944): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6404): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6404): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/Finsky  ( 5944): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  936): Killing 6329:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  936): failed to open /acct/uid_10069/pid_6329/cgroup.procs: No such file or directory
,W/ResourcesManager( 6404): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6404): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6404): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/jxcore-log( 5571): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5571): 
,W/ActivityThread( 6404): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6404): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30863795: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6404): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6404): GMSCore installation verified
I/ConfigStore( 6404): Config Database version: 1
,I/jxcore-log( 5571): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5571): 
,I/jxcore-log( 5571): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5571): 
I/MediaRouter( 6404): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6404): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6404): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  936): Killing 5450:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/jxcore-log( 5571): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5571): 
,I/jxcore-log( 5571): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5571): 
,W/libprocessgroup(  936): failed to open /acct/uid_10086/pid_5450/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6404): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  936): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6447 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/AlertService( 6172): Beginning updateAlertNotification
,I/GHttpClientFactory( 6404): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6404): Using platform SSLCertificateSocketFactory
,D/AlertService( 6172): No fired or scheduled alerts
I/NotificationManager( 6172): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 6172): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(5) by com.android.calendar
,I/NotificationManager( 6172): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(17) by com.android.calendar
,I/NotificationManager( 6404): com.google.android.music: cancel(1061) by com.google.android.music
I/NotificationManager( 6172): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6172): com.android.calendar: cancel(20) by com.android.calendar
I/ActivityManager(  936): Killing 6355:com.android.settings/1000 (adj 15): empty #11
,D/AlertService( 6172): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
W/ResourcesManager( 6447): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6447): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6447): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  936): failed to open /acct/uid_1000/pid_6355/cgroup.procs: No such file or directory
,D/AlarmScheduler( 6172): No events found starting within 1 week.
I/ActivityManager(  936): Killing 6172:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  936): failed to open /acct/uid_10013/pid_6172/cgroup.procs: No such file or directory
,I/LGEmail ( 6447): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6447): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,D/eas_req ( 6447): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  936): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6479 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6447): JNI_OnLoad()
I/HubEmail( 6447): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6447): registerNatives()
I/HubEmail( 6447): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6447): registerNativeMethods()
I/HubEmail( 6447): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6447): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6447): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  936): Killing 6091:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6044): android.os.DeadObjectException
,W/System.err( 6044): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6044): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6044): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6044): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6044): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6044): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6044): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6044): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6044): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6044): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6044): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6044): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6044): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6044): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6044): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6044): android.os.DeadObjectException
W/System.err( 6044): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6044): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6044): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6044): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6044): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6044): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6044): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6044): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6044): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6044): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6044): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6044): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6044): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6044): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6044): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  936): failed to open /acct/uid_10089/pid_6091/cgroup.procs: No such file or directory
W/ActivityManager(  936): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  936): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6498 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  936): Killing 5779:com.google.android.talk/u0a61 (adj 15): empty #11
,D/LGDMClient( 6479): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6479): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6479): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6479): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/libprocessgroup(  936): failed to open /acct/uid_10061/pid_5779/cgroup.procs: No such file or directory
,I/ActivityManager(  936): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6515 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/UEI.SmartControl( 6498): Quickset Services start...
I/UEI.SmartControl( 6498): Manufacture = LGE
D/LGDMClient( 6479): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6479): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/UEI.SmartControl( 6498): File observer start...
,E/UEI.SmartControl( 6498): IR Port is disabled: false
D/UEI.SmartControl( 6498): Starting file observer...
D/UEI.SmartControl( 6498): Extracting JNI libs...
D/UEI.SmartControl( 6498): --- this system supports 32-bit or 64-bit only
D/LGDMClient( 6479): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,D/UEI.SmartControl( 6498): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6498): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6498): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/LGDMClient( 6479): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6479): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6479): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6479): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6479): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6479): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6479): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/UEI.SmartControl( 6498): --- Selecting new region: 2
I/UEI.SmartControl( 6498): -- Running on KitKat(19) and above! JNI will be used.
I/ActivityManager(  936): Killing 6231:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6498): Platform has CIR...
,D/UEI.SmartControl( 6498): NO CIR support, need to check package...
I/UEI.SmartControl( 6498): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6498): QS Service created
I/AppUp4:AppBoxCP( 6515): onCreate
,W/AppUp4:DB( 6515):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6515):  setFingerPrint start
I/AppUp4:DB( 6515):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6515):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6515):  SDK version = 0
I/AppUp4:DB( 6515):  beforefinger == newfinger no write in DB
W/libprocessgroup(  936): failed to open /acct/uid_1000/pid_6231/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 6515): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6515): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6515): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6515): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6515): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6515): onReceive
I/AppUp4:CustModeStarterReceiver( 6515): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
E/UEI.SmartControl( 6498): QS start get config
D/AppUp4:CustFacade( 6515): Context : android.app.ReceiverRestrictedContext@2e73f3a9
,D/AppUp4:CustFacade( 6515): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6515): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6515): begin check event
I/AppUp4:CustModeStarterReceiver( 6515): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6515): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6515): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6515): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6515): handleAsyncCustNotification do not startCustService
I/ActivityManager(  936): Killing 6044:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6498): Loading JNI Libs...
,D/UEI.SmartControl( 6498):  configuring local db...
W/libprocessgroup(  936): failed to open /acct/uid_10106/pid_6044/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3173): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3173): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3173): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 5748): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5748): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3241): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3241): DownloadService onCreate
,I/DownloadManager( 3241): in removeSpuriousFiles
I/NotificationManager( 3241): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@207679f2 on behalf of 3241
,I/DownloadManager( 3241): in trimDatabase
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@2ec5d843 on behalf of 3241
I/ActivityManager(  936): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6544 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,D/UEI.SmartControl( 6498):  ---- Has DB8: true
,V/DownloadManager( 3241): DownloadService onStartCommand
V/DownloadManager( 3241): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/UEI.SmartControl( 6498): QS start statue = true Error code = 0
D/UEI.SmartControl( 6498): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6498): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@1c6e433e on behalf of 3241
D/UEI.SmartControl( 6498): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6498): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6498): IrrcClient ++ 
D/irrcClient( 6498): getIrrcService ++ 
D/irrcClient( 6498): getIrrcService -- 
D/irrcClient( 6498): IrrcClient -- 
W/irrc_jni( 6498): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6498): Services init done
I/UEI.SmartControl( 6498): Device manager: loading config....
D/UEI.SmartControl( 6498): QS Service init finished
D/UEI.SmartControl( 6498): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6498): QS Service version code: 1073
D/UEI.SmartControl( 6498): Service requested: Control
D/UEI.SmartControl( 6498): Config is loaded...
D/UEI.SmartControl( 6498):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6498): Notify AllClients services are ready: 0
V/DownloadManager( 3241): DownloadService onDestroy
I/ActivityManager(  936): Killing 6382:com.android.providers.calendar/u0a14 (adj 15): empty #11
,D/UEI.SmartControl( 6498): Request IControl service: devices are loaded...
W/libprocessgroup(  936): failed to open /acct/uid_10014/pid_6382/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6498): Service.onUnbind: IControl
D/UEI.SmartControl( 6498): Service.onDestroy
,D/UEI.SmartControl( 6498): Shutdown IRRCPlayer... 
D/WeatherAncestor( 2680): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:49:45
,D/UpdateThreadPoolManager( 2680): 2 : This is isUpdating : false
D/WeatherAncestor( 2680): connectivity changed - connection : true
D/Weather_cast( 2680): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2680): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:49:45
D/WeatherService( 2680): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/irrc_jni( 6498): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6498): ~IrrcClient ++ 
D/irrcClient( 6498): ~IrrcClient -- 
W/irrc_jni( 6498): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6498): Blaster closed
D/UEI.SmartControl( 6498): Blaster closed
D/UEI.SmartControl( 6498): Shut down QS...
D/UEI.SmartControl( 6498): Stopped file observer...
I/UEI.SmartControl( 6498): QS lib stop result = true
,D/UEI.SmartControl( 6498): QS shutdown complete
D/UEI.SmartControl( 6498): QS Service created
E/UEI.SmartControl( 6498): QS start get config
,I/ActivityManager(  936): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6569 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  936): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/UEI.SmartControl( 6498):  configuring local db...
D/Weather.Utils( 2680): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2680): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2680): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6569): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6498):  ---- Has DB8: true
,D/UEI.SmartControl( 6498): QS start statue = true Error code = 0
D/UEI.SmartControl( 6498): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6498): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6498): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6498): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6498): IrrcClient ++ 
D/irrcClient( 6498): getIrrcService ++ 
D/irrcClient( 6498): getIrrcService -- 
D/irrcClient( 6498): IrrcClient -- 
W/irrc_jni( 6498): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6498): Services init done
D/UEI.SmartControl( 6498): QS Service init finished
D/UEI.SmartControl( 6498): QS Service version name: 0.1.73
D/UEI.SmartControl( 6498): QS Service version code: 1073
D/UEI.SmartControl( 6498): Service requested: Control
,I/ActivityManager(  936): Killing 6278:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/UEI.SmartControl( 6498): Device manager: loading config....
D/UEI.SmartControl( 6498): Config is loaded...
D/UEI.SmartControl( 6498):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6498): Notify AllClients services are ready: 0
,W/libprocessgroup(  936): failed to open /acct/uid_10006/pid_6278/cgroup.procs: No such file or directory
,W/ActivityManager(  936): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
E/ActivityThread( 6498): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1f748a5c that was originally bound here
E/ActivityThread( 6498): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1f748a5c that was originally bound here
E/ActivityThread( 6498): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6498): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6498): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6498): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6498): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6498): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6498): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6498): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6498): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6498): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6498): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6498): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6498): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6498): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6498): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6498): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6498): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6498): Internal service binding...
,I/Babel_SMS( 6569): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6569): MmsConfig.loadMmsSettings
I/Babel_SMS( 6569): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6569): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6569): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6569): MmsConfig.loadFromResources
E/Babel_SMS( 6569): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6569): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6569): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6569): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6569): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6569): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6569): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6569): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6569): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6569): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6569): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6569): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6569): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6569): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6569): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6569): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6569): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6569): found sensor: Motion Accel, handle=46
,I/art     ( 6569): CheckpointMarkThreadRoots callback created = 0xaaf3b830
,W/Settings( 6569): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6569): startup - clean
,I/art     ( 6569): CheckpointMarkThreadRoots callback created = 0xaaf3b800
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Babel   ( 6569): deleted: false for 0
,I/ActivityManager(  936): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6602 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6569): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6569): Unsupported mime audio/adpcm
W/AudioCapabilities( 6569): Unsupported mime audio/g726
W/AudioCapabilities( 6569): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6569): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6569): Unsupported mime video/mjpg
,W/VideoCapabilities( 6569): Unsupported mime video/theora
,W/AudioCapabilities( 6569): Unsupported mime audio/evrc
,W/AudioCapabilities( 6569): Unsupported mime audio/qcelp
W/VideoCapabilities( 6569): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6569): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6569): Unsupported mime audio/qcelp
W/AudioCapabilities( 6569): Unsupported mime audio/evrc
W/VideoCapabilities( 6569): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6569): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6569): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6569): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6569): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6569): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6569): onServiceConnected
W/Babel   ( 6569): Attempted to change video mute state without an active call.
,I/NotificationManager( 6569): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6569): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6569): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6569): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6569): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6569): propertyValue:false
I/Babel   ( 6569): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  936): Killing 5944:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  936): failed to open /acct/uid_10036/pid_5944/cgroup.procs: No such file or directory
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6602): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6602): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6602): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6602): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6602): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6602):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6602):   adb logcat -s GAv4
,W/GAv4    ( 6602): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6602): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6602): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     (  936): Explicit concurrent mark sweep GC freed 21772(1031KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.372ms total 141.661ms
I/WebViewFactory( 6602): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6602): Time to load native libraries: 2 ms (timestamps 2373-2375)
I/LibraryLoader( 6602): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6602): Binding Chromium to main looper Looper (main, tid 1) {1cbd43a2}
I/LibraryLoader( 6602): Expected native library version number "",actual native library version number ""
I/chromium( 6602): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6602): Initializing chromium process, singleProcess=true
W/art     ( 6602): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6602): ApplicationContext is null in ApplicationStatus
,W/chromium( 6602): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6602): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6602): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6602): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6602): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6602): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6602): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6602): Remote Branch: 
I/Adreno-EGL( 6602): Local Patches: 
I/Adreno-EGL( 6602): Reconstruct Branch: 
V/AudioPolicyService(  278): registerClient() client 0xb551c660, uid 10079
,W/AudioManagerAndroid( 6602): Requires BLUETOOTH permission
I/NSApplication( 6602): Starting up...
,I/ActivityManager(  936): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6670 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  936): Killing 6404:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
W/libprocessgroup(  936): failed to open /acct/uid_10081/pid_6404/cgroup.procs: No such file or directory
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ActivityManager(  936): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6689 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  936): Killing 6447:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  936): failed to open /acct/uid_10021/pid_6447/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6689): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,I/iu.SyncManager( 5606): SYNC; picasa accounts
,D/NetworkLogImpl( 5606): Loaded NetworkSpeedPredictor
I/iu.Environment( 5606): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  936): Killing 6479:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/iu.UploadsManager( 5606): num queued entries: 0
I/iu.UploadsManager( 5606): num updated entries: 0
I/iu.SyncManager( 5606): NEXT; no task
,W/libprocessgroup(  936): failed to open /acct/uid_1000/pid_6479/cgroup.procs: No such file or directory
,I/ActivityManager(  936): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6725 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/MusicStore( 6725): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6725): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6725): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6725): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6725): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6725): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6725): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,E/UEI.SmartControl( 6498): file observer is disposed!
,W/ActivityThread( 6725): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6725): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30863795: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6725): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6725): GMSCore installation verified
,I/ConfigStore( 6725): Config Database version: 1
,I/MediaRouter( 6725): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6725): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6725): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6725): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  936): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6753 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.141ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 20.772ms
,I/GHttpClientFactory( 6725): Using our fixed implementation of GMSCore's GoogleHttpClient
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.601ms
,I/GoogleURLConnFactory( 6725): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 6753): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  936): Killing 6515:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6753): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6753): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  936): failed to open /acct/uid_10011/pid_6515/cgroup.procs: No such file or directory
,I/NotificationManager( 6725): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6753): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/LGEmail ( 6753): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6753): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  936): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6786 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6753): JNI_OnLoad()
I/HubEmail( 6753): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6753): registerNatives()
I/HubEmail( 6753): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6753): registerNativeMethods()
I/HubEmail( 6753): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6753): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6753): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  936): Killing 5748:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,D/UEI.SmartControl( 6498): Internal timer expired: 2
,W/libprocessgroup(  936): failed to open /acct/uid_10038/pid_5748/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6498): Service.onUnbind: IControl
D/UEI.SmartControl( 6498): Service.onDestroy
D/UEI.SmartControl( 6498): Shutdown IRRCPlayer... 
W/irrc_jni( 6498): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6498): ~IrrcClient ++ 
D/irrcClient( 6498): ~IrrcClient -- 
W/irrc_jni( 6498): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6498): Blaster closed
D/UEI.SmartControl( 6498): Blaster closed
D/UEI.SmartControl( 6498): Shut down QS...
I/UEI.SmartControl( 6498): QS lib stop result = true
D/UEI.SmartControl( 6498): QS shutdown complete
D/LGDMClient( 6786): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6786): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6786): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6786): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/CheckinService( 5606): Done disabling old GoogleServicesFramework version
D/LGDMClient( 6786): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6786): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6786): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6786): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  936): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6813 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6786): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6786): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6786): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6786): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6786): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6786): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  936): Killing 6544:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  936): failed to open /acct/uid_10051/pid_6544/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6813): onCreate
,W/AppUp4:DB( 6813):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6813):  setFingerPrint start
I/AppUp4:DB( 6813):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6813):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6813):  SDK version = 0
I/AppUp4:DB( 6813):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6813): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6813): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6813): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6813): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6813): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6813): onReceive
I/AppUp4:CustModeStarterReceiver( 6813): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6813): Context : android.app.ReceiverRestrictedContext@2e73f3a9
D/AppUp4:CustFacade( 6813): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6813): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6813): begin check event
I/AppUp4:CustModeStarterReceiver( 6813): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6813): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6813): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6813): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6813): handleAsyncCustNotification do not startCustService
I/ActivityManager(  936): Killing 6498:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/libprocessgroup(  936): failed to open /acct/uid_10089/pid_6498/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3173): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3173): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3173): networkInfo.isConnected() = false
I/ActivityManager(  936): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6837 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6837): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6837): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6837): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  936): Killing 6569:com.google.android.talk/u0a61 (adj 15): empty #11
,I/jxcore-log( 5571): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5571): 
,W/libprocessgroup(  936): failed to open /acct/uid_10061/pid_6569/cgroup.procs: No such file or directory
V/DownloadManager( 3241): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3241): DownloadService onCreate
I/jxcore-log( 5571): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5571): 
,I/DownloadManager( 3241): in removeSpuriousFiles
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3241): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@1ac4f6ec on behalf of 3241
I/DownloadManager( 3241): in trimDatabase
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/PhoneMonitor( 6837): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,I/jxcore-log( 5571): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5571): 
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@2487554a on behalf of 3241
V/TelephonyAutoProfiling( 6837): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6837): [parse] Load xml
V/TelephonyAutoProfiling( 6837): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6837): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6837): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  936): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6869 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3241): DownloadService onStartCommand
V/DownloadManager( 3241): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 5606): Checkin interval check for package: unspecified last checkin: 1455029363456 min interval config: 0 actual interval: 28181
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@58095d8 on behalf of 3241
I/CheckinService( 5606): Checking schedule, now: 1455029391654 next: 1455029393426
I/CheckinService( 5606): active receiver: disabled
,V/DownloadManager( 3241): DownloadService onDestroy
,I/ActivityManager(  936): Killing 6602:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,E/libprocessgroup(  936): failed to kill 1 processes for processgroup 6602
,D/WeatherAncestor( 2680): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:49:51
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/UpdateThreadPoolManager( 2680): 2 : This is isUpdating : false
D/WeatherAncestor( 2680): connectivity changed - connection : true
D/Weather_cast( 2680): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2680): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:49:52
D/WeatherService( 2680): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  936): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6890 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  936): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2680): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2680): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2680): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6890): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6890): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6890): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6890): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6890): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6890): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6890): MmsConfig.loadFromResources
E/Babel_SMS( 6890): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6890): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6890): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6890): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6890): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6890): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 6890): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6890): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6890): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6890): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6890): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6890): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6890): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6890): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6890): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6890): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6890): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6890): found sensor: Motion Accel, handle=46
W/Settings( 6890): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6890): startup - clean
I/art     ( 6890): CheckpointMarkThreadRoots callback created = 0xaaf386e0
,I/Babel   ( 6890): deleted: false for 0
,I/art     ( 6890): CheckpointMarkThreadRoots callback created = 0xaaf386c0
,I/ActivityManager(  936): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6927 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 5571): Test app app.js loaded
I/jxcore-log( 5571): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5571): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5571): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5571): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5571): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5571): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5571): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5571): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5571): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5571): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5571): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c89cf43 added. We now have 1 listener(s)
W/AudioCapabilities( 6890): Unsupported mime audio/x-lg-flac
D/BluetoothAdapterService(527731292)( 1977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7164a92
W/AudioCapabilities( 6890): Unsupported mime audio/adpcm
I/jxcore-log( 5571): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5571): 
W/AudioCapabilities( 6890): Unsupported mime audio/g726
W/AudioCapabilities( 6890): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6890): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6890): Unsupported mime video/mjpg
W/VideoCapabilities( 6890): Unsupported mime video/theora
,I/chromium( 5571): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/AudioCapabilities( 6890): Unsupported mime audio/evrc
W/AudioCapabilities( 6890): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6890): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6890): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6890): Unsupported mime audio/qcelp
W/AudioCapabilities( 6890): Unsupported mime audio/evrc
W/VideoCapabilities( 6890): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6890): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6890): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6890): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6890): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6890): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6890): onServiceConnected
W/Babel   ( 6890): Attempted to change video mute state without an active call.
,D/libc-netbsd( 6890): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6890): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6890): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6890): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6890): propertyValue:false
I/NotificationManager( 6890): com.google.android.talk: cancel(10436) by com.google.android.talk
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6927): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6927): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6927): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6927):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6927):   adb logcat -s GAv4
I/Babel   ( 6890): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  936): Killing 6670:com.android.chrome/u0a48 (adj 15): empty #11
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6927): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6927): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/libprocessgroup(  936): failed to open /acct/uid_10048/pid_6670/cgroup.procs: No such file or directory
,W/GAv4    ( 6927): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6927): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6927): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6927): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6927): Time to load native libraries: 2 ms (timestamps 8365-8367)
I/LibraryLoader( 6927): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6927): Binding Chromium to main looper Looper (main, tid 1) {1cbd43a2}
I/LibraryLoader( 6927): Expected native library version number "",actual native library version number ""
I/chromium( 6927): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6927): Initializing chromium process, singleProcess=true
,W/art     ( 6927): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6927): ApplicationContext is null in ApplicationStatus
W/chromium( 6927): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6927): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6927): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6927): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6927): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6927): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6927): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6927): Remote Branch: 
I/Adreno-EGL( 6927): Local Patches: 
I/Adreno-EGL( 6927): Reconstruct Branch: 
I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,I/art     (  936): Explicit concurrent mark sweep GC freed 19593(1002KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.487ms total 141.684ms
V/AudioPolicyService(  278): registerClient() client 0xb57e8580, uid 10079
,W/AudioManagerAndroid( 6927): Requires BLUETOOTH permission
I/NSApplication( 6927): Starting up...
I/ActivityManager(  936): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6992 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  936): Killing 6689:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  936): failed to open /acct/uid_10086/pid_6689/cgroup.procs: No such file or directory
,I/ActivityManager(  936): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7011 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  936): Killing 6725:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  936): failed to open /acct/uid_10081/pid_6725/cgroup.procs: No such file or directory
,W/ResourcesManager( 7011): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  936): Killing 6753:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  936): failed to open /acct/uid_10021/pid_6753/cgroup.procs: No such file or directory
,I/ActivityManager(  936): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7038 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7038): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  936): Message: 20
D/BluetoothManagerService(  936): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@357f5320:true
,D/BluetoothAdapterService(527731292)( 1977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7164a92
D/BluetoothAdapterService(527731292)( 1977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7164a92
I/ActivityManager(  936): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7056 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7038): Create singleton instance
,D/UEI.SmartControl( 7056): Quickset Services start...
,I/UEI.SmartControl( 7056): Manufacture = LGE
D/UEI.SmartControl( 7056): File observer start...
E/UEI.SmartControl( 7056): IR Port is disabled: false
D/UEI.SmartControl( 7056): Starting file observer...
,D/UEI.SmartControl( 7056): Extracting JNI libs...
D/UEI.SmartControl( 7056): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7038): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7056): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7056): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7056): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7056): --- Selecting new region: 2
,I/UEI.SmartControl( 7056): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7056): Platform has CIR...
D/UEI.SmartControl( 7056): NO CIR support, need to check package...
I/UEI.SmartControl( 7056): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7056): QS Service created
I/AudioManager( 7038): getMode name:com.lge.qremote
,E/UEI.SmartControl( 7056): QS start get config
,I/ActivityManager(  936): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7081 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7056): Loading JNI Libs...
I/art     (  310): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 274us total 23.599ms
,D/UEI.SmartControl( 7056):  configuring local db...
I/art     (  310): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 20.642ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 20.484ms
W/ActivityManager(  936): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/UEI.SmartControl( 7056):  ---- Has DB8: true
,D/UEI.SmartControl( 7056): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7056): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7056): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7056): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7056): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7056): IrrcClient ++ 
D/irrcClient( 7056): getIrrcService ++ 
,D/irrcClient( 7056): getIrrcService -- 
D/irrcClient( 7056): IrrcClient -- 
W/irrc_jni( 7056): IRRCPlayer_nativeInit -- 
I/ActivityManager(  936): Process com.lge.appbox.client (pid 6813) has died
I/UEI.SmartControl( 7056): Device manager: loading config....
D/UEI.SmartControl( 7056): Services init done
,D/UEI.SmartControl( 7056): Config is loaded...
D/UEI.SmartControl( 7056): QS Service init finished
D/UEI.SmartControl( 7056): QS Service version name: 0.1.73
D/UEI.SmartControl( 7056): QS Service version code: 1073
D/UEI.SmartControl( 7056): Service requested: Control
D/UEI.SmartControl( 7056): Internal service binding...
D/UEI.SmartControl( 7056): -----IControl: 11
D/UEI.SmartControl( 7056): Caller: com.lge.qremote
,D/UEI.SmartControl( 7056): ------------ IControl registerCallback...
I/UEI.SmartControl( 7056): Registering callback...
D/UEI.SmartControl( 7056): -----IControl: 19
D/UEI.SmartControl( 7056): Caller: com.lge.qremote
I/UEI.SmartControl( 7056): Registering Services Ready callback...
I/UEI.SmartControl( 7056): Notify client services are ready...
D/UEI.SmartControl( 7056): -----IControl: 8
D/UEI.SmartControl( 7056): Caller: com.lge.qremote
I/Gmail   ( 7081): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7056):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7056): Notify AllClients services are ready: 0
W/GAV2    ( 7081): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  936): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ActivityManager(  936): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7081): Observing account changes for notifications
,W/ActivityManager(  936): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  936): Killing 6786:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  936): failed to open /acct/uid_1000/pid_6786/cgroup.procs: No such file or directory
,E/Gmail   ( 7081): Error finding the version of the Email provider.....
E/Gmail   ( 7081): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7081): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7081): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7081): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7081): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7081): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7081): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7081): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7081): We do not support migrating this version of the Email provider.
I/Gmail   ( 7081): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  936): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7121 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  936): Killing 6837:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  936): failed to open /acct/uid_10038/pid_6837/cgroup.procs: No such file or directory
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/MusicStore( 7121): Database version: 120
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7121): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/Gmail   ( 7081): notifyAccountChanged
,I/Gmail   ( 7081): getAccountsCursor
I/Gmail   ( 7081): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7081): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7081): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7081): calculateUnknownSyncRationalesAndPurgeInBackground: running
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7121): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7121): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7121): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7121): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Gmail   ( 7081): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/JNIHelp ( 7121): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7121): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7121): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30863795: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7121): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7121): GMSCore installation verified
,I/ConfigStore( 7121): Config Database version: 1
,V/AlarmManager(  936): RTC_WAKEUP set : Alarm{228b6f86 type 0 when 1455029393426 com.google.android.gms} when 1455029393426
,I/ActivityManager(  936): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7153 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  936): RTC_WAKEUP set : Alarm{38fd8047 type 0 when 1455029395768 com.android.vending} when 1455029395768
,I/MediaRouter( 7121): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7121): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7121): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7121): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  936): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7174 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  936): Process com.google.android.apps.magazines (pid 6927) has died
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/GHttpClientFactory( 7121): Using our fixed implementation of GMSCore's GoogleHttpClient
I/art     (  936): Explicit concurrent mark sweep GC freed 14364(685KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.336ms total 154.656ms
,I/GoogleURLConnFactory( 7121): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 7174): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7174): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7174): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationManager( 7121): com.google.android.music: cancel(1061) by com.google.android.music
,D/Finsky  ( 7153): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/LGEmail ( 7174): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7174): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/Finsky  ( 7153): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7153): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7153): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7153): com.android.vending: cancel(-1050172287) by com.android.vending
,D/eas_req ( 7174): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/Ads     ( 7153): Skipping gmscore version check
D/Finsky  ( 7153): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7153): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@326d7c16 on behalf of 7153
I/ActivityManager(  936): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7230 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7174): JNI_OnLoad()
I/HubEmail( 7174): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7174): registerNatives()
I/HubEmail( 7174): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7174): registerNativeMethods()
I/HubEmail( 7174): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7174): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 7174): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  936): Killing 6869:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  936): failed to open /acct/uid_10051/pid_6869/cgroup.procs: No such file or directory
,D/Finsky  ( 7153): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 7153): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/LGDMClient( 7230): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7230): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 7230): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7230): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7230): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7230): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7230): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7230): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  936): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7257 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 7230): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7230): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7230): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7230): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 7230): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7230): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  936): Killing 6992:com.android.chrome/u0a48 (adj 15): empty #11
D/Finsky  ( 7153): [910] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7153): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
W/libprocessgroup(  936): failed to open /acct/uid_10048/pid_6992/cgroup.procs: No such file or directory
,I/ActivityManager(  936): Killing 7011:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/AppUp4:AppBoxCP( 7257): onCreate
W/AppUp4:DB( 7257):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7257):  setFingerPrint start
I/AppUp4:DB( 7257):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
W/libprocessgroup(  936): failed to open /acct/uid_10086/pid_7011/cgroup.procs: No such file or directory
,I/AppUp4:DB( 7257):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7257):  SDK version = 0
I/AppUp4:DB( 7257):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7257): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7257): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7257): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7257): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7257): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7257): onReceive
,I/AppUp4:CustModeStarterReceiver( 7257): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7257): Context : android.app.ReceiverRestrictedContext@2e73f3a9
D/AppUp4:CustFacade( 7257): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7257): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7257): begin check event
I/AppUp4:CustModeStarterReceiver( 7257): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7257): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7257): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7257): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7257): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  936): Killing 7056:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 7038): android.os.DeadObjectException
,W/System.err( 7038): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7038): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 7038): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7038): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7038): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7038): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7038): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7038): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7038): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7038): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7038): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7038): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7038): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7038): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7038): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7038): android.os.DeadObjectException
W/System.err( 7038): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7038): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7038): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7038): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7038): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7038): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7038): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7038): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7038): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7038): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7038): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7038): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7038): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7038): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7038): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  936): failed to open /acct/uid_10089/pid_7056/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3173): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3173): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3173): networkInfo.isConnected() = true
D/PhoneState( 3173): setPdpRejectCasuse : false
,I/ActivityManager(  936): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7277 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  936): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7294 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7277): Quickset Services start...
I/UEI.SmartControl( 7277): Manufacture = LGE
D/UEI.SmartControl( 7277): File observer start...
E/UEI.SmartControl( 7277): IR Port is disabled: false
D/UEI.SmartControl( 7277): Starting file observer...
D/UEI.SmartControl( 7277): Extracting JNI libs...
D/UEI.SmartControl( 7277): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 7277): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7277): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 7277): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/PhoneMonitor( 7294): Register our PhoneStateListener
D/MobileConnectivityChangeReceiver( 7294): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7294): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  936): Killing 6890:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 7294): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7294): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7294): [parse] Load xml
,V/TelephonyAutoProfiling( 7294): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7294): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/UEI.SmartControl( 7277): --- Selecting new region: 2
I/UEI.SmartControl( 7277): -- Running on KitKat(19) and above! JNI will be used.
D/PhoneMonitor( 7294): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/UEI.SmartControl( 7277): Platform has CIR...
D/UEI.SmartControl( 7277): NO CIR support, need to check package...
I/UEI.SmartControl( 7277): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7277): QS Service created
W/libprocessgroup(  936): failed to open /acct/uid_10061/pid_6890/cgroup.procs: No such file or directory
,V/DownloadManager( 3241): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3241): DownloadService onCreate
,I/DownloadManager( 3241): in removeSpuriousFiles
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3241): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@2370b997 on behalf of 3241
I/DownloadManager( 3241): in trimDatabase
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@c4b0b6d on behalf of 3241
,E/UEI.SmartControl( 7277): QS start get config
,I/ActivityManager(  936): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7320 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3241): DownloadService onStartCommand
D/UEI.SmartControl( 7277): Loading JNI Libs...
D/UEI.SmartControl( 7277):  configuring local db...
I/CheckinService( 5606): Checkin interval check for package: unspecified last checkin: 1455029363456 min interval config: 0 actual interval: 34012
V/DownloadManager( 3241): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@187d5833 on behalf of 3241
,I/CheckinService( 5606): Checking schedule, now: 1455029397492 next: 1455029393426
I/CheckinService( 5606): active receiver: enabled
,V/DownloadManager( 3241): DownloadService onDestroy
I/CheckinService( 5606): Preparing to send checkin request
I/EventLogService( 5606): Accumulating logs since 1455029354736
,D/WeatherAncestor( 2680): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:49:57
D/UpdateThreadPoolManager( 2680): 2 : This is isUpdating : false
D/WeatherAncestor( 2680): connectivity changed - connection : true
D/Weather_cast( 2680): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2680): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:49:57
D/WeatherService( 2680): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  936): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7339 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  936): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2680): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2680): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,D/WeatherService( 2680): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7339): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 7277):  ---- Has DB8: true
,I/art     ( 5980): Explicit concurrent mark sweep GC freed 2352(101KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 449us total 42.244ms
D/UEI.SmartControl( 7277): QS start statue = true Error code = 0
D/UEI.SmartControl( 7277): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7277): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7277): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7277): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7277): IrrcClient ++ 
D/irrcClient( 7277): getIrrcService ++ 
D/irrcClient( 7277): getIrrcService -- 
D/irrcClient( 7277): IrrcClient -- 
W/irrc_jni( 7277): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7277): Services init done
I/UEI.SmartControl( 7277): Device manager: loading config....
,D/UEI.SmartControl( 7277): QS Service init finished
D/UEI.SmartControl( 7277): QS Service version name: 0.1.73
D/UEI.SmartControl( 7277): QS Service version code: 1073
D/UEI.SmartControl( 7277): Service requested: Control
D/UEI.SmartControl( 7277): Config is loaded...
,D/UEI.SmartControl( 7277):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7277): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7277): Request IControl service: devices are loaded...
,I/ActivityManager(  936): Killing 7038:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 7277): Internal service binding...
,W/libprocessgroup(  936): failed to open /acct/uid_10106/pid_7038/cgroup.procs: No such file or directory
I/CheckinRequestBuilder( 5606): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 5606): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 7339): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7339): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7339): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7339): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7339): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7339): MmsConfig.loadFromResources
E/Babel_SMS( 7339): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7339): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7339): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7339): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7339): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7339): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7339): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7339): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7339): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7339): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7339): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7339): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7339): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7339): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7339): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7339): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7339): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7339): found sensor: Motion Accel, handle=46
,W/Settings( 7339): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7339): startup - clean
,I/art     ( 7339): CheckpointMarkThreadRoots callback created = 0xb042d870
,I/Babel   ( 7339): deleted: false for 0
,I/art     ( 7339): CheckpointMarkThreadRoots callback created = 0xb042d850
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout,
I/ActivityManager(  936): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7379 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7339): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7339): Unsupported mime audio/adpcm
W/AudioCapabilities( 7339): Unsupported mime audio/g726
W/AudioCapabilities( 7339): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7339): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7339): Unsupported mime video/mjpg
W/VideoCapabilities( 7339): Unsupported mime video/theora
,W/AudioCapabilities( 7339): Unsupported mime audio/evrc
,W/AudioCapabilities( 7339): Unsupported mime audio/qcelp
W/VideoCapabilities( 7339): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7339): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7339): Unsupported mime audio/qcelp
W/AudioCapabilities( 7339): Unsupported mime audio/evrc
W/VideoCapabilities( 7339): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7339): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7339): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7339): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7339): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7339): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  936): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7396 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 310us total 21.327ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.866ms
I/vclib   ( 7339): onServiceConnected
W/Babel   ( 7339): Attempted to change video mute state without an active call.
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 322us total 21.241ms
I/NotificationManager( 7339): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 7339): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7339): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7339): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7339): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 7339): propertyValue:false
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ResourcesManager( 7396): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7396): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ContextImpl( 7379): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7379): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7379): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7379):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7379):   adb logcat -s GAv4
,E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7379): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/Babel   ( 7339): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  936): Killing 7081:com.google.android.gm/u0a53 (adj 15): empty #11
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7379): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/libprocessgroup(  936): failed to open /acct/uid_10053/pid_7081/cgroup.procs: No such file or directory
,W/GAv4    ( 7379): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/MultiDex( 7396): VM with version 2.1.0 has multidex support
,I/MultiDex( 7396): install
I/MultiDex( 7396): VM has multidex support, MultiDex support library is disabled.
I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
W/GAv4    ( 7379): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7379): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
V/JNIHelp ( 7396): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7396): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7396): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@207679f2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7396): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7396): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7396): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 7396): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7396): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/WebViewFactory( 7379): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7379): Time to load native libraries: 3 ms (timestamps 3781-3784)
I/LibraryLoader( 7379): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7379): Binding Chromium to main looper Looper (main, tid 1) {1cbd43a2}
I/LibraryLoader( 7379): Expected native library version number "",actual native library version number ""
,I/chromium( 7379): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7379): Initializing chromium process, singleProcess=true
W/art     ( 7379): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7379): ApplicationContext is null in ApplicationStatus
,W/chromium( 7379): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7379): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7379): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7379): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7379): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7379): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7379): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7379): Remote Branch: 
I/Adreno-EGL( 7379): Local Patches: 
I/Adreno-EGL( 7379): Reconstruct Branch: 
D/NativeLibraryUtils( 7396): Install completed successfully. count=14 extracted=0
V/AudioPolicyService(  278): registerClient() client 0xb551cca0, uid 10079
W/AudioManagerAndroid( 7379): Requires BLUETOOTH permission
,I/NSApplication( 7379): Starting up...
,D/WVCdm   (  278): Instantiating CDM.
I/WVCdm   (  278): CdmEngine::OpenSession
I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  278): L1 library not specified. Falling Back to L3
,I/ActivityManager(  936): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7461 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  936): Killing 7121:com.google.android.music:main/u0a81 (adj 15): empty #11
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=3617587614
,W/libprocessgroup(  936): failed to open /acct/uid_10081/pid_7121/cgroup.procs: No such file or directory
,I/art     (  936): Explicit concurrent mark sweep GC freed 20587(947KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.605ms total 141.940ms
,I/art     ( 7396): CheckpointMarkThreadRoots callback created = 0xaaf0b320
,I/ActivityManager(  936): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7481 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  936): Killing 7174:com.lge.email/u0a21 (adj 15): empty #11
,I/art     ( 7396): CheckpointMarkThreadRoots callback created = 0xaaf0b310
W/libprocessgroup(  936): failed to open /acct/uid_10021/pid_7174/cgroup.procs: No such file or directory
,W/ResourcesManager( 7481): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/WVCdm   (  278): CdmEngine::OpenSession
,I/ActivityManager(  936): Killing 7153:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  936): failed to open /acct/uid_10036/pid_7153/cgroup.procs: No such file or directory
,I/ActivityManager(  936): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7510 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
,I/[SystemUI]DateView( 1371): called onTimeUpdated()
W/ResourcesManager( 7510): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[SystemUI]DateView( 1371): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/BluetoothManagerService(  936): Message: 20
,D/BluetoothManagerService(  936): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@efbf751:true
D/BluetoothAdapterService(527731292)( 1977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7164a92
D/WeatherService( 2680): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:50:0
,D/WeatherService( 2680): 2 : TimeTick Intent And Screen On
D/WeatherService( 2680): 2 : SDK version : 21
W/ActivityManager(  936): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2680): 2 : Utils getTopActivity com.lge.launcher2 / true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/WeatherService( 2680): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2680): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2680): 2 : requestRefreshAppWidget, isUpdateStart : false
D/BluetoothAdapterService(527731292)( 1977): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7164a92
D/UpdateThreadPoolManager( 2680): 2 : This is isUpdating : false
D/WeatherService( 2680): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2680): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2680): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2680): 2 : Fixed theme : optimus
D/sensors_hal_Time(  936): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  936): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  936): tsOffsetIs: Apps: 115100957720; DSPS: 3870428; Offset : -3024927656
D/WeatherReflect( 2680): 2 : Map key string is -2
,I/AudioManager( 7510): getMode name:com.lge.qremote
D/lim     ( 2680): 2 : time = 15:50
,I/WeatherReflect( 2680): Model Name : LG-D722
D/WeatherTheme( 2680): 2 : Different view - status_min_formatted : 49 != 50
D/WeatherTheme( 2680): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2680): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2680): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2680): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2680): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2680): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2680): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2680): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2680): forecast size is 0
D/Theme   ( 2680): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2680): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2680): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2680): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2680): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2680): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2680): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2680): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2680): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2680): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2680): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2680): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2680): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2680): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2680): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2680): url is : null
D/Theme   ( 2680): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2680): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2680): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2680): 2 : update view, appWidgetId: 2
,D/WeatherService( 2680): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:50:0
I/AudioManager( 7510): getMode name:com.lge.qremote
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,D/LocationInitializer( 5606): Restart initialization of location
E/MDM     ( 1732): [83] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  936): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7539 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/Finsky  ( 7539): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7539): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7539): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7539): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7539): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@3c99f169 on behalf of 7539
D/Finsky  ( 7539): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7539): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7539): Skipping gmscore version check
D/Finsky  ( 7539): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/Finsky  ( 7539): [979] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7539): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicWidget( 2578): mDelayedStopHandler : unbind
,I/NotificationManager(  936): android: cancelAsUser(2) by android
,V/LGMDMManager( 7510): Create singleton instance
I/MusicBrowser( 2719): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2719): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2719): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/MusicBrowser( 2719): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2719): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2719): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2719): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  936):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2ec56bbfcom.lge.music.MediaPlaybackService$6@259d428c
,D/MusicBrowser( 2719): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@5ef2165
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
,I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2719): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2719): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2719): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2719): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2719): reset
,I/AudioManager( 7510): getMode name:com.lge.qremote
V/MediaPlayer[Native]( 2719): setListener
V/MediaPlayer[Native]( 2719): disconnect
,V/MediaPlayer[Native]( 2719): destructor
D/UEI.SmartControl( 7277): -----IControl: 11
D/UEI.SmartControl( 7277): Caller: com.lge.qremote
D/UEI.SmartControl( 7277): ------------ IControl registerCallback...
I/UEI.SmartControl( 7277): Registering callback...
D/UEI.SmartControl( 7277): -----IControl: 19
V/AudioFlinger(  278): releasing 19 from 2719 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
D/UEI.SmartControl( 7277): Caller: com.lge.qremote
V/MediaPlayer[Native]( 2719): disconnect
I/UEI.SmartControl( 7277): Registering Services Ready callback...
I/UEI.SmartControl( 7277): Notify client services are ready...
D/MusicBrowser( 2719): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
,D/UEI.SmartControl( 7277): -----IControl: 8
D/UEI.SmartControl( 7277): Caller: com.lge.qremote
D/libc-netbsd( 7539): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7539): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7539): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7539): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/SmartShareClient( 2719): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2719): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2719): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2719): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2719): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2719): [SmartShareManagerClient] unregisterListener: 847523285
W/SmartShareClient( 2719): [SmartShareManagerClient] unregisterListener invalid listener: 847523285
I/SmartShareClient( 2719): [SmartShareManagerClient] terminate service: 2719/MediaPlaybackService/815300723
E/HomeCloudIF( 2719): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2719): [SmartShareManagerClient] unbindService context:android.app.Application@ffc99ea
I/ActivityManager(  936): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7593 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 7539): propertyValue:false
I/ActivityManager(  936): Killing 7230:com.lge.lgdmsclient/1000 (adj 15): empty #11
V/CloudHub( 2719): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2719): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2719): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2719): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2719): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  936): failed to open /acct/uid_1000/pid_7230/cgroup.procs: No such file or directory
,I/ActivityManager(  936): Killing 7257:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/CloudHub( 2719): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29948
,I/WVCdm   (  278): CdmEngine::CloseSession
,W/libprocessgroup(  936): failed to open /acct/uid_10011/pid_7257/cgroup.procs: No such file or directory
W/ActivityManager(  936): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=946619987
,I/Gmail   ( 7593): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 7593): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  936): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  936): Killing 7320:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  936): failed to open /acct/uid_10051/pid_7320/cgroup.procs: No such file or directory
,W/ActivityManager(  936): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 7593): Error finding the version of the Email provider.....
E/Gmail   ( 7593): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7593): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7593): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7593): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7593): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7593): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7593): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7593): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7593): We do not support migrating this version of the Email provider.
I/Gmail   ( 7593): Observing account changes for notifications
,I/Gmail   ( 7593): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 7510): getMode name:com.lge.qremote
I/CheckinService( 5606): Checkin interval check for package: unspecified last checkin: 1455029363456 min interval config: 0 actual interval: 38105
,W/ActivityManager(  936): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  936): Killing 7339:com.google.android.talk/u0a61 (adj 15): empty #11
E/MDM     ( 1732): [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ContextImpl( 3602): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
W/libprocessgroup(  936): failed to open /acct/uid_10061/pid_7339/cgroup.procs: No such file or directory
,D/LocationInitializer( 5606): Restart initialization of location
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 7510): getMode name:com.lge.qremote
W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
I/AudioManager( 7510): getMode name:com.lge.qremote
,I/AudioManager( 7510): getMode name:com.lge.qremote
,I/AudioManager( 7510): getMode name:com.lge.qremote
I/AudioManager( 7510): getMode name:com.lge.qremote
,I/AudioManager( 7510): getMode name:com.lge.qremote
,I/Gmail   ( 7593): notifyAccountChanged
,I/Gmail   ( 7593): getAccountsCursor
I/Gmail   ( 7593): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7593): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7593): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7593): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7593): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  936): Explicit concurrent mark sweep GC freed 22476(1011KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.282ms total 146.043ms
,D/UEI.SmartControl( 7277): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/WVCdm   (  278): CdmEngine::CloseSession
,I/WVCdm   (  278): L3 Terminate.
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/dex2oat ( 7672): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=38 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7672): dex2oat took 102.961ms (threads: 4)
,I/Adreno-EGL( 7396): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7396): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7396): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7396): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7396): Remote Branch: 
I/Adreno-EGL( 7396): Local Patches: 
I/Adreno-EGL( 7396): Reconstruct Branch: 
,I/Adreno-EGL( 7396): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7396): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7396): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7396): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7396): Remote Branch: 
I/Adreno-EGL( 7396): Local Patches: 
I/Adreno-EGL( 7396): Reconstruct Branch: 
,I/Adreno-EGL( 7396): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7396): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7396): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7396): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7396): Remote Branch: 
I/Adreno-EGL( 7396): Local Patches: 
I/Adreno-EGL( 7396): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/CheckinRequestBuilder( 5606): Classify the device as Phone.
,D/libc-netbsd( 5606): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5606): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5606): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5606): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5606): propertyValue:false
D/libc-netbsd( 5606): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5606): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5606): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5606): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5606): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5606): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5606): Sending checkin request (9856 bytes)
,I/CheckinRequestBuilder( 5606): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5606): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5606): Classify the device as Phone.
,I/CheckinTask( 5606): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinService( 5606): Checking schedule, now: 1455029406167 next: 1455556655157
I/CheckinService( 5606): active receiver: disabled
,I/CheckinService( 5606): Checking schedule, now: 1455029406200 next: 1455556655157
I/CheckinService( 5606): active receiver: disabled
,D/CheckinService( 5606): Recording last checkin time for package unspecified as 1455029406209
V/SetupWizard( 7294): Connected to Gservices successfully
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/GAV2    ( 7593): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 5606): Google Analytics 8.4.89 is starting up.
,I/art     ( 5980): Explicit concurrent mark sweep GC freed 3189(130KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.399ms total 41.563ms
,I/ActivityManager(  936): Killing 7461:com.android.chrome/u0a48 (adj 15): empty #11
,I/ActivityManager(  936): Killing 7379:com.google.android.apps.magazines/u0a79 (adj 15): empty #12
,W/libprocessgroup(  936): failed to open /acct/uid_10048/pid_7461/cgroup.procs: No such file or directory
,W/libprocessgroup(  936): failed to open /acct/uid_10079/pid_7379/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  936): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/ActivityManager(  936): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7715 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  936): Handling package changes for user 0
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7715): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  936): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  936): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  936): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  936): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  936): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  936): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2844b01a
W/ResourcesManager(  936): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Babel_SMS( 7715): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7715): MmsConfig.loadMmsSettings
I/Babel_SMS( 7715): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7715): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7715): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7715): MmsConfig.loadFromResources
E/Babel_SMS( 7715): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7715): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,I/art     ( 7715): CheckpointMarkThreadRoots callback created = 0xaaf58360
,D/SensorManager( 7715): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7715): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 7715): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 7715): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7715): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7715): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7715): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7715): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7715): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7715): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7715): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7715): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7715): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7715): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7715): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7715): found sensor: Motion Accel, handle=46
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/Settings( 7715): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7715): startup - clean
I/art     ( 7715): CheckpointMarkThreadRoots callback created = 0xaaf58350
,I/Babel   ( 7715): deleted: false for 0
,W/ResourceType(  936): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager(  936): Process com.google.android.apps.plus (pid 7481) has died
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  936): applying state to connected service
,W/AudioCapabilities( 7715): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7715): Unsupported mime audio/adpcm
W/AudioCapabilities( 7715): Unsupported mime audio/g726
W/AudioCapabilities( 7715): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7715): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7715): Unsupported mime video/mjpg
W/VideoCapabilities( 7715): Unsupported mime video/theora
I/ActivityManager(  936): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7755 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 7715): Unsupported mime audio/evrc
,W/AudioCapabilities( 7715): Unsupported mime audio/qcelp
W/VideoCapabilities( 7715): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7715): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7715): Unsupported mime audio/qcelp
W/AudioCapabilities( 7715): Unsupported mime audio/evrc
W/VideoCapabilities( 7715): Unsupported mime video/mp4v-esdp
,I/AppUp4:AppBoxCP( 7755): onCreate
W/AppUp4:DB( 7755):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7755):  setFingerPrint start
I/AppUp4:DB( 7755):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7755):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 7755):  SDK version = 0
I/AppUp4:DB( 7755):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7755): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7755): onReceive
I/AppUp4:CustModeStarterReceiver( 7755): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 7755): Context : android.app.ReceiverRestrictedContext@23a6e4e2
D/AppUp4:CustFacade( 7755): isCustomizationCompleted : false
,I/VideoCapabilities( 7715): Unsupported profile 4 for video/mp4v-es
D/AppUp4:CustFacade( 7755): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7755): begin check event
I/AppUp4:CustModeStarterReceiver( 7755): Event For Nothing, skip.
W/VideoCapabilities( 7715): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7715): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7715): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7715): Unrecognized profile 2130706433 for video/avc
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,I/ActivityManager(  936): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7774 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationManager( 7715): com.google.android.talk: cancel(8) by com.google.android.talk
I/vclib   ( 7715): onServiceConnected
,W/Babel   ( 7715): Attempted to change video mute state without an active call.
,W/ResourcesManager( 7774): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7774): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7774): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 7715): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7715): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7715): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  936): Process com.android.vending (pid 7539) has died
,W/System  ( 7715): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7715): Installed default security provider GmsCore_OpenSSL
I/AppConfig( 7774): Total System Memory = 906309632
I/GalleryUtils( 7774): Application Heap = 96 MB
I/NotificationManager( 7715): com.google.android.talk: cancel(10436) by com.google.android.talk
I/AppConfig( 7774): App Tier : NOT_DEF
D/SystemHelper( 7774): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  936): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7798 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7798): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7798): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7798): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7798): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7798): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7798): BUILD Country: EU
I/SystemConfig( 7798): BUILD Operator: OPEN
,I/ActivityManager(  936): Process com.google.android.gm (pid 7593) has died
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  936): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7823 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7798): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7798): existFile = false
I/SystemConfig( 7798): canReadFile = false
I/SystemConfig( 7798): systemFeature RCS result false
D/SystemConfig( 7798): refreshRcsSupport() :false
,I/LockScreenSettings( 7823): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7823): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7823): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7823): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7823): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7823): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  936): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7840 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  936): Killing 2719:com.lge.music/u0a28 (adj 15): empty #11
I/art     (  310): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 358us total 22.625ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.572ms
,V/AudioFlinger(  278): 2719 died, releasing its sessions
V/AudioFlinger(  278):  pid 1748 @ 0
V/AudioFlinger(  278):  pid 3173 @ 1
V/AudioFlinger(  278):  pid 3173 @ 2
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 21.391ms
,W/libprocessgroup(  936): failed to open /acct/uid_10028/pid_2719/cgroup.procs: No such file or directory
,W/ResourcesManager( 7840): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1934): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1934): UpdateCorporaTask done [took 47 ms] updated apps [took 47 ms] 
,I/ActivityManager(  936): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7875 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  936): Killing 7277:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7510): android.os.DeadObjectException
,W/System.err( 7510): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7510): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7510): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7510): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7510): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7510): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7510): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7510): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7510): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7510): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7510): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7510): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7510): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7510): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7510): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7510): android.os.DeadObjectException
W/System.err( 7510): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7510): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7510): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7510): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7510): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7510): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7510): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7510): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7510): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7510): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7510): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7510): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7510): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7510): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7510): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  936): failed to open /acct/uid_10089/pid_7277/cgroup.procs: No such file or directory
W/ActivityManager(  936): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  936): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7895 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7895): Quickset Services start...
,I/UEI.SmartControl( 7895): Manufacture = LGE
D/UEI.SmartControl( 7895): File observer start...
E/UEI.SmartControl( 7895): IR Port is disabled: false
D/UEI.SmartControl( 7895): Starting file observer...
D/UEI.SmartControl( 7895): Extracting JNI libs...
D/UEI.SmartControl( 7895): --- this system supports 32-bit or 64-bit only
D/Finsky  ( 7875): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 7895): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7895): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7895): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7895): --- Selecting new region: 2
I/UEI.SmartControl( 7895): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7895): Platform has CIR...
D/UEI.SmartControl( 7895): NO CIR support, need to check package...
I/UEI.SmartControl( 7895): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7895): QS Service created
E/UEI.SmartControl( 7895): QS start get config
,D/UEI.SmartControl( 7895): Loading JNI Libs...
,D/UEI.SmartControl( 7895):  configuring local db...
D/Finsky  ( 7875): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7875): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7875): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7875): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3241): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3241): created cursor android.database.sqlite.SQLiteCursor@154ff7ee on behalf of 7875
D/Finsky  ( 7875): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7875): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7875): Skipping gmscore version check
D/Finsky  ( 7875): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5606): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5606): Null package name or gms related package.  Ignoreing.
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/Finsky  ( 7875): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/UEI.SmartControl( 7895):  ---- Has DB8: true
,D/UEI.SmartControl( 7895): QS start statue = true Error code = 0
D/UEI.SmartControl( 7895): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7895): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7895): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7895): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7895): IrrcClient ++ 
D/irrcClient( 7895): getIrrcService ++ 
,D/irrcClient( 7895): getIrrcService -- 
D/irrcClient( 7895): IrrcClient -- 
W/irrc_jni( 7895): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7895): Services init done
I/art     (  936): Explicit concurrent mark sweep GC freed 28132(1432KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.360ms total 169.341ms
I/UEI.SmartControl( 7895): Device manager: loading config....
D/UEI.SmartControl( 7895): QS Service init finished
,D/UEI.SmartControl( 7895): QS Service version name: 0.1.73
D/UEI.SmartControl( 7895): QS Service version code: 1073
D/UEI.SmartControl( 7895): Config is loaded...
D/UEI.SmartControl( 7895): Service requested: Control
D/UEI.SmartControl( 7895): -----IControl: 11
D/UEI.SmartControl( 7895): Internal service binding...
D/UEI.SmartControl( 7895): Caller: com.lge.qremote
,D/UEI.SmartControl( 7895): ------------ IControl registerCallback...
I/UEI.SmartControl( 7895): Registering callback...
D/UEI.SmartControl( 7895): -----IControl: 19
D/UEI.SmartControl( 7895): Caller: com.lge.qremote
I/UEI.SmartControl( 7895): Registering Services Ready callback...
I/UEI.SmartControl( 7895): Notify client services are ready...
D/UEI.SmartControl( 7895): -----IControl: 8
,D/UEI.SmartControl( 7895): Caller: com.lge.qremote
I/Icing   ( 5606): updateResources: need to parse f{com.google.android.gms}
,I/AudioManager( 7510): getMode name:com.lge.qremote
I/ActivityManager(  936): Killing 7294:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/UEI.SmartControl( 7895):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7895): Notify AllClients services are ready: 0
W/libprocessgroup(  936): failed to open /acct/uid_10038/pid_7294/cgroup.procs: No such file or directory
,I/AudioManager( 7510): getMode name:com.lge.qremote
I/AudioManager( 7510): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Icing   ( 5606): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5606): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  936): Killing 7755:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  936): failed to open /acct/uid_10011/pid_7755/cgroup.procs: No such file or directory
,D/charger_monitor(  479): init target 500000
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
D/charger_monitor(  479): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 305, mChargingStatus=5, mChargingStop=false
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 305
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 305
D/WifiController(  936): battery changed pluggedType: 2
D/HeadsetStateMachine( 1977): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,I/ActivityManager(  936): Killing 7774:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  936): failed to open /acct/uid_10023/pid_7774/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7895): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,D/sensors_hal_Time(  936): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  936): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  936): tsOffsetIs: Apps: 135101891099; DSPS: 4525818; Offset : -3024909675
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  936): ELAPSED_WAKEUP set : Alarm{33208cf5 type 2 when 145524 com.google.android.gms} when 145524
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1732): Vacuum at: now=1455029430846 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 3673 seconds from now (1455029431297)
,D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 43888(2MB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 13MB/22MB, paused 1.854ms total 120.842ms
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  936): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  936): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  936): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  936): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  936): ALS enabled for SRE
D/PowerManagerServiceEx(  936): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (30573 ms ago)
,D/qdlights(  936): set_light_backlight: 252
,D/qdlights(  936): set_light_backlight: 249
D/qdlights(  936): set_light_backlight: 246
,D/qdlights(  936): set_light_backlight: 242
,D/qdlights(  936): set_light_backlight: 239
,D/qdlights(  936): set_light_backlight: 236
,D/qdlights(  936): set_light_backlight: 232
,D/qdlights(  936): set_light_backlight: 229
,D/qdlights(  936): set_light_backlight: 226
,D/qdlights(  936): set_light_backlight: 222
,D/qdlights(  936): set_light_backlight: 219
,D/qdlights(  936): set_light_backlight: 216
,D/qdlights(  936): set_light_backlight: 212
,D/qdlights(  936): set_light_backlight: 209
,D/qdlights(  936): set_light_backlight: 206
,D/qdlights(  936): set_light_backlight: 202
,D/qdlights(  936): set_light_backlight: 199
,D/qdlights(  936): set_light_backlight: 196
,D/qdlights(  936): set_light_backlight: 192
,D/qdlights(  936): set_light_backlight: 189
,D/qdlights(  936): set_light_backlight: 186
,D/qdlights(  936): set_light_backlight: 182
,D/qdlights(  936): set_light_backlight: 179
,D/qdlights(  936): set_light_backlight: 176
,D/qdlights(  936): set_light_backlight: 172
,D/qdlights(  936): set_light_backlight: 169
,D/qdlights(  936): set_light_backlight: 166
,D/qdlights(  936): set_light_backlight: 162
,D/qdlights(  936): set_light_backlight: 159
,D/qdlights(  936): set_light_backlight: 156
,D/qdlights(  936): set_light_backlight: 152
,D/qdlights(  936): set_light_backlight: 149
,D/qdlights(  936): set_light_backlight: 146
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/qdlights(  936): set_light_backlight: 142
D/qdlights(  936): set_light_backlight: 139
,D/qdlights(  936): set_light_backlight: 136
,D/qdlights(  936): set_light_backlight: 132
,D/qdlights(  936): set_light_backlight: 129
,D/qdlights(  936): set_light_backlight: 126
,D/qdlights(  936): set_light_backlight: 122
,D/qdlights(  936): set_light_backlight: 119
,D/qdlights(  936): set_light_backlight: 116
,D/qdlights(  936): set_light_backlight: 112
,D/qdlights(  936): set_light_backlight: 109
,D/qdlights(  936): set_light_backlight: 106
,D/qdlights(  936): set_light_backlight: 102
,D/qdlights(  936): set_light_backlight: 99
,D/qdlights(  936): set_light_backlight: 96
,D/qdlights(  936): set_light_backlight: 92
,D/qdlights(  936): set_light_backlight: 89
,D/qdlights(  936): set_light_backlight: 86
,D/qdlights(  936): set_light_backlight: 82
,D/qdlights(  936): set_light_backlight: 79
,D/qdlights(  936): set_light_backlight: 76
,D/qdlights(  936): set_light_backlight: 72
,D/qdlights(  936): set_light_backlight: 69
,D/qdlights(  936): set_light_backlight: 66
,D/qdlights(  936): set_light_backlight: 62
,D/qdlights(  936): set_light_backlight: 59
,D/qdlights(  936): set_light_backlight: 56
,D/qdlights(  936): set_light_backlight: 52
,D/qdlights(  936): set_light_backlight: 49
,D/qdlights(  936): set_light_backlight: 46
,D/qdlights(  936): set_light_backlight: 42
,D/qdlights(  936): set_light_backlight: 39
,D/qdlights(  936): set_light_backlight: 36
,D/qdlights(  936): set_light_backlight: 32
,D/qdlights(  936): set_light_backlight: 29
,D/qdlights(  936): set_light_backlight: 26
,D/qdlights(  936): set_light_backlight: 22
,D/qdlights(  936): set_light_backlight: 19
,D/qdlights(  936): set_light_backlight: 16
,D/qdlights(  936): set_light_backlight: 13
,D/qdlights(  936): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  936): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  936): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  936): tsOffsetIs: Apps: 155102636455; DSPS: 5181203; Offset : -3024927414
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  936): ALS enabled for SRE
D/PowerManagerServiceEx(  936): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (37562 ms ago)
I/PowerManagerService(  936): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  936): ALS enabled for SRE
D/PowerManagerServiceEx(  936): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (37577 ms ago)
,W/ContextImpl(  936): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  936): Sleeping (uid 1000)...
D/LPWGController(  936): [updateScreenState] screen on = false
,D/LPWGController(  936): disable proximity sensor
D/LPWGController(  936): enable proximity sensor
I/SensorManager(  936): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@24d141d] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  936): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  936): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  936): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  936): activate: handle is 48, enable
,V/sensors_hal_Ctx(  936): activate sensors is 1400000000000
D/sensors_hal_Thresh(  936): enable: handle=48
I/sensors_hal_SAM(  936): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  936): waitForResponse: timeout=1000
V/sensors_hal_SAM(  936): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  936): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  936): enable: Received response: 0
D/PowerManagerServiceEx(  936): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (37646 ms ago)
I/Adreno-EGL(  936): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  936): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  936): Build Date: 03/02/15 Mon
I/Adreno-EGL(  936): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  936): Remote Branch: 
I/Adreno-EGL(  936): Local Patches: 
I/Adreno-EGL(  936): Reconstruct Branch: 
,D/PermissionCache(  244): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1172 us)
,I/Sensors (  411): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  936): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  936): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  936): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  936): processInd: handle 48, count=1
V/sensors_hal_Thresh(  936): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  936): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  936): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  936): poll: count: 256
I/sensors_hal_Ctx(  936): poll: released wakelock sensor_ind
D/sensors_hal_Util(  936): waitForResponse: timeout=0
D/LPWGController(  936): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  936): current mode = 1  value = 1 1
I/LPWGController(  936): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  936): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  936): set_light_backlight: 0
,I/SensorManager(  936): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  936): activate: handle is 46, disable
V/sensors_hal_Ctx(  936): activate sensors is 1000000000000
D/sensors_hal_LP2(  936): enable: handle=46
D/sensors_hal_LP2(  936): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  936): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  244): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  244): hwc_blank: Blanking display: 0
I/DisplayManagerService(  936): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  936): Display changed displayId=0
,V/sensors_hal_SAM(  936): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  936): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1748): Display #0 changed.
,D/qdhwcomposer(  244): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  936): Excessive delay in setPowerMode(): 168ms
I/qdhwcomposer(  244): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  936): Got set_interactive hint
,D/KeyguardViewMediator( 1371): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1371): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,D/KeyguardViewMediator( 1371): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1371): handleNotifyScreenOff
D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
,D/ScreenTurnOffBySensor( 1371): unregisterProximitySensor
,D/StatusBarWindowView( 1371): onScreenTurnedOff why = 3
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiServerServiceExt(  936): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 936
,I/WifiServerServiceExt(  936): set CMD_KT_SCAN_INTERVAL
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
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/GpsLocationProvider(  936): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1802): stopPatternFlashing()
D/Cliptray Service( 1802): lockStatus = 0
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): updateLightsLocked : turn off led
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
D/LEDHandler( 1802): RESTART MSG
D/Ulp_jni (  936): JNI:system_update. Event-0
,D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
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
D/SplitWindow(  936): check instance of lgWin Window{3471ac60 u0 SearchPanel}
,D/InputDispatcher(  936): Window went away: Window{1dd9dff5 u0 SearchPanel}
,I/[SystemUI]Clock( 1371): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1371): time changed, timezoneChanged : false
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2680): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:50:44
,D/WeatherService( 2680): 2 : ACTION screen on
D/WeatherService( 2680): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2680): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2680): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:50:44
,W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): ACTION_SCREEN_ON
D/AppCleanupService( 4082): android.intent.action.SCREEN_ON
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 936
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=off
,V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
D/WifiController(  936): CMD_SCREEN_OFF 
D/WifiController(  936): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  936): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1802): clear
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1802): updateLightsLocked : turn on led
E/LEDService( 1802): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1802): Can't handle this request of patternId:0
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
D/LEDHandler( 1802): RESTART MSG
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1875): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2680): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:50:44
D/WeatherService( 2680): 2 : ACTION screen off
D/WeatherService( 2680): 2 : TimeTick Receiver Unregister
D/WeatherService( 2680): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:50:44
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  936): ACTION_SCREEN_OFF
D/AppCleanupService( 4082): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4082): AppUsageStatsSaveTask
,I/Sensors (  411): sns_pwr.c(301):releasing wakelock
E/NxpNfcJni( 1785): getReconnectState = 0x0
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
,D/KeyguardViewMediator( 1371): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  936): ELAPSED_WAKEUP set : Alarm{292bd519 type 2 when 163487 com.android.systemui} when 163487
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1748): getCallState : 0
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1371): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1371): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  936): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  936): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  936): tsOffsetIs: Apps: 175103310041; DSPS: 5836585; Offset : -3024924928
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,D/PowerManagerServiceEx(  936): acquireWakeLockInternal: lock=216893918, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=936
,V/AlarmManager(  936): ELAPSED_WAKEUP set : Alarm{20d987bf type 2 when 183341 android} when 183341
D/PowerManagerServiceEx(  936): releaseWakeLockInternal: lock=216893918 [*alarm*], flags=0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/charger_monitor(  479): init target 500000
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 301
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 301
,D/HeadsetStateMachine( 1977): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 301, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  936): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  936): ELAPSED_WAKEUP set : Alarm{b52e8c type 2 when 189357 com.google.android.gms} when 189357
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  936): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  936): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  936): tsOffsetIs: Apps: 195104063627; DSPS: 6491970; Offset : -3024934412
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  936): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  936): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  936): tsOffsetIs: Apps: 215104823567; DSPS: 7147355; Offset : -3024937203
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  936): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  936): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  936): tsOffsetIs: Apps: 235105493664; DSPS: 7802736; Offset : -3024908287
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  479): init target 500000
,D/charger_monitor(  479): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1977): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 298, mChargingStatus=5, mChargingStop=false
W/Settings(  936): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  936): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  936): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  936): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  936): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  936): tsOffsetIs: Apps: 255106174854; DSPS: 8458119; Offset : -3024928508
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  936): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  936): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  936): tsOffsetIs: Apps: 275106842503; DSPS: 9113501; Offset : -3024932427
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/jxcore-log( 5571): --= Surplus to requirements =--
I/jxcore-log( 5571): 
I/jxcore-log( 5571): ****TEST TOOK:  ms ****
I/jxcore-log( 5571): 
I/jxcore-log( 5571): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5571): 
,D/AndroidRuntime( 8080): 
D/AndroidRuntime( 8080): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8080): CheckJNI is OFF
,D/AndroidRuntime( 8080): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  936): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  936): Killing 5571:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  936): WIN DEATH: Window{f4ac58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/InputDispatcher(  936): Focus left window: Window{f4ac58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  936): Window went away: Window{f4ac58 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  936): Skipping PackageSetting{2e15e4c2 com.example.hello/10317} due to missing metadata
,I/ActivityManager(  936):   Force finishing activity ActivityRecord{3762a94f u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  936): Display changed displayId=0
D/DSDPConnection( 1748): Display #0 changed.
,W/ActivityManager(  936): Spurious death for ProcessRecord{d9ba9d5 5571:com.test.thalitest/u0a316}, curProc for 5571: null
,I/ActivityManager(  936): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  936):   Force finishing activity ActivityRecord{3762a94f u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  936): Duplicate finish request for ActivityRecord{3762a94f u0 com.test.thalitest/.MainActivity t222 f}
,I/[LGHome]EVENT( 1875): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/System.err( 3602): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
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
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
I/[LGHome]EVENT( 1875): [Launcher.java:776:onResume()]onResume
,I/InputReader(  936): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  936): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8114 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     ( 1934): Explicit concurrent mark sweep GC freed 21902(1372KB) AllocSpace objects, 4(95KB) LOS objects, 40% free, 12MB/20MB, paused 2.542ms total 119.446ms
I/art     ( 5606): Explicit concurrent mark sweep GC freed 6686(347KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 13MB/17MB, paused 762us total 126.915ms
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
I/[LGHome]LGActivityUtil( 1875): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1875): [Launcher.java:929:onResume()]onResume end
I/Activity( 1875): Activity.onPostResume() called 
,D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/KeyguardModel( 1371): handleShortcutListChanged...
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1875): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1875): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
I/art     (  936): Explicit concurrent mark sweep GC freed 48551(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 5.628ms total 258.262ms
I/art     (  936): WaitForGcToComplete blocked for 93.201ms for cause Explicit
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
I/SystemUI[Framework](  936): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  936): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  936): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  936): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  936): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3341c5ef,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  936): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  936): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,D/InputDispatcher(  936): Focus entered window: Window{23e39334 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  936): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  936): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  936): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  936): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3341c5ef,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  936): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourcesManager( 8114): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8114): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/ResourcesManager( 8114): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
,D/KeyguardModel( 1371): handleShortcutListChanged...
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
,I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1875): [setNavigationBarColor] color=0x 0
D/administrator(  936): Handling package changes for user 0
,I/LGEmail ( 8114): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8114): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/InputMethodManagerService(  936): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  936): Got RemoteException sending setActive(false) notification to pid 5571 uid 10316
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline(  936): Timeline: Activity_windows_visible id: ActivityRecord{3b21348b u0 com.lge.launcher2/.Launcher t221} time:288679
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/IInputConnectionWrapper( 1875): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/b       ( 1599): Unable to connect to the editor to retrieve text... will retry later
,I/PackageChangeReceiver( 8114): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1875): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/NotificationService(  936): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  936): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  936): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     (  936): Explicit concurrent mark sweep GC freed 8642(505KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 5.811ms total 410.972ms
,I/ActivityManager(  936): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8141 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  936): Killing 7715:com.google.android.talk/u0a61 (adj 15): empty #11
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
,W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1875): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
,W/libprocessgroup(  936): failed to open /acct/uid_10061/pid_7715/cgroup.procs: No such file or directory
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,D/TaskPersister(  936): removeObsoleteFile: deleting file=222_task.xml
D/AndroidRuntime( 8080): Shutting down VM
,I/AppUp4:AppBoxCP( 8141): onCreate
,W/AppUp4:DB( 8141):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 8141):  setFingerPrint start
I/AppUp4:DB( 8141):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8141):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8141):  SDK version = 0
I/AppUp4:DB( 8141):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 8141): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 8141): added Exclude : com.test.thalitest
,W/ResourcesManager(  936): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  936): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8158 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  936): Killing 7798:com.android.contacts/u0a18 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1875): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourceType(  936): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/libprocessgroup(  936): failed to open /acct/uid_10018/pid_7798/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1875): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1875): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager( 8158): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
